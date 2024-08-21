---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "5rem"

cascade:
  # Configure publications
  - _target:
      path: /publication/**
    show_date: false
    profile: false
    pager: false
    editable: false
    reading_time: false
    commentable: false
    show_related: false
    show_breadcrumb: false
    share: true
    header:
      navbar:
        enable: false
  # Configure talks
  - _target:
      path: /event/**
    show_date: true
    profile: false
    pager: false
    editable: false
    reading_time: false
    commentable: false
    show_related: false
    show_breadcrumb: false
    share: true
    header:
      navbar:
        enable: false
  # Configure posters
  - _target:
      path: /poster/**
    show_date: true
    profile: false
    pager: false
    editable: false
    reading_time: false
    commentable: false
    show_related: false
    show_breadcrumb: false
    share: true
    header:
      navbar:
        enable: false

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
      count: 0
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
      count: 0
    #design:
      #view: article-grid
      #columns: 1
  - block: collection
    id: posters
    content:
      title: Posters
      filters:
        folders:
          - poster
      count: 0
    #design:
      #view: date-title-summary
      #columns: 1
  - block: markdown
    id: events
    content:
      title: 'Event Attendances'
      subtitle: ''
      text: |-
        - **GI Sicherheit 2024**, Worms, Germany
        - **HPCC 2023**, Melbourne, Australia
        - **eScience 2023**, Limassol, Cyprus
        - **ARES 2022**, Vienna, Austria
        - **EICC 2022**, Barcelona, Spain
        - **Euro-Par 2021**, Lisbon, Portugal (online)
        - **ARC 2021**, Rennes, France (online)
        - **IPDPS 2021**, Portland, USA (online)
        - **DKFT 2021** (online)
        - **MBMV 2021** (online)
        - **HiPEAC 2021**, Budapest, Hungary (online)
        - **PDP 2020**, Västerås, Sweden (online)
        - **PPoPP 2020**, San Diego, USA
        - **HiPEAC 2020**, Bologna, Italy
        - **DKFT 2019**, TU Dortmund, Germany
        - **4th German-Russian Summer School 2019**, htw saar, Saarbrücken, Germany
        - **ICANN 2019**, Munich, Germany
        - **Euro-Par 2019**, Göttingen, Germany
        - **HPCS 2019**, Dublin, Ireland
        - **PUMPS+AI Summer School 2019**, Barcelona, Spain
        - **28th PARS Workshop 2019**, TU Berlin, Germany
        - **Supercomputing Frontiers Europe 2019**, Warsaw, Poland
        - **HiPEAC 2019**, Valencia, Spain
        - **DKFT 2018**, HTW Dresden, Germany
        - **UPMARC Day 2018**, Uppsala Universitet, Sweden
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        At FernUniversität in Hagen, I serve as a teaching assistant for courses on parallel computing, simulation, and computer engineering. Moreover, I take part in supervising bachelor and master theses on topics related to parallel computing.

        As a philosophy student, I have worked as a teaching assistant for introductory courses on logic at Universität Hamburg and at Eberhard Karls Universität Tübingen.
    design:
      columns: '1'
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
