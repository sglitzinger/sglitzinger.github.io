---
title: Effects of Continuous vs Discrete Frequency Scaling and Core Allocation on
  Energy Efficiency of Static Schedules for Moldable Tasks
authors:
- Sebastian Litzinger
- Jörg Keller
date: 0-01-01
publishDate: '2024-08-19T12:43:31.542051Z'
publication_types:
- article-journal
publication: '*Parallel Processing Letters*'
doi: 10.1142/S0129626421500250
abstract: ' Models for energy-efficient static scheduling of parallelizable tasks
  with deadlines on frequency-scalable parallel machines comprise moldable vs. malleable
  tasks and continuous vs. discrete frequency levels, plus preemptive vs. non-preemptive
  task execution with or without task migration. We investigate the tradeoff between
  scheduling time and energy efficiency when going from continuous to discrete core
  allocation and frequency levels on a multicore processor, and from preemptive to
  non-preemptive task execution. To this end, we present a tool to convert a schedule
  computed for malleable tasks on machines with continuous frequency scaling [Sanders
  and Speck, Euro-Par (2012)] into one for moldable tasks on a machine with discrete
  frequency levels. We compare the energy efficiency of the converted schedule to
  the energy consumed by a schedule produced by the integrated crown scheduler [Melot
  et al., ACM TACO (2015)] for moldable tasks and a machine with discrete frequency
  levels. Our experiments with synthetic and application-based task sets indicate
  that the converted Sanders Speck schedules, while computed faster, consume more
  energy on average than crown schedules. Surprisingly, it is not the step from malleable
  to moldable tasks that is responsible but the step from continuous to discrete frequency
  levels. One-time frequency scaling during a task’s execution can compensate for
  most of the energy overhead caused by frequency discretization. '
links:
- name: URL
  url: https://doi.org/10.1142/S0129626421500250
---
