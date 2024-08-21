---
title: Code generation for energy-efficient execution of dynamic streaming task graphs
  on parallel and heterogeneous platforms
authors:
- Sebastian Litzinger
- Jörg Keller
date: '2020-06-11'
publishDate: '2024-08-19T12:43:31.588427Z'
publication_types:
- article-journal
publication: '*Concurrency and Computation: Practice and Experience*'
doi: 10.1002/cpe.6072
abstract: Summary Streaming task graphs are high-level specifications for parallel
  applications operating on streams of data. For a static task graph structure, static
  schedulers can be used to map the tasks onto a parallel platform to minimize energy
  consumption for given throughput. We introduce dynamic elements into the task graph
  structure, thus specifying applications which adapt behavior at runtime, for example,
  switching from check-only to active mode. This in turn necessitates a runtime system
  that can remap tasks and potentially adapt their degree of parallelism in case of
  a dynamic change of the task structure. We provide a toolchain and evaluate our
  prototype with streaming task graphs both synthetic and from a real application.
  We find that we meet throughput requirements with <3.5% energy overhead on average
  compared with an optimal static scheduler based on integer linear programming. Runtime
  overhead for remapping is negligible and application runtime and energy are accurately
  predicted. We also outline how to extend our system to a heterogeneous platform.
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.6072
---
