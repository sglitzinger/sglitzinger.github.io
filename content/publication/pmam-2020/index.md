---
title: Generating Energy-Efficient Code for Parallel Applications Specified by Streaming
  Task Graphs with Dynamic Elements
authors:
- Sebastian Litzinger
- Jörg Keller
date: '2020-02-22'
publishDate: '2024-08-19T12:43:31.602796Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 11th International Workshop on Programming Models
  and Applications for Multicores and Manycores (PMAM)*'
doi: 10.1145/3380536.3380544
abstract: Streaming task graphs are a high-level construct used to specify parallel
  applications operating on streams of data, and energy-efficient code meeting data
  throughput requirements can be generated automatically. Tasks can be parallel themselves,
  so that two levels of parallelism are present. Normally, the task graph structure
  is assumed to be static, so that static schedulers can be used to map the (parallel)
  tasks onto a parallel platform to minimize energy consumption for given throughput.
  We propose a formulation that introduces dynamic elements into the task graph structure,
  thus allowing to specify applications that can adapt their behavior at runtime,
  e.g. activating another filter task depending on data quality. This in turn necessitates
  a runtime system that can re-map tasks in case of a dynamic change of the task structure.
  We provide the core of such a runtime system together with a task mapper that is
  able to work incrementally, i.e. that can re-use results from previous mappings
  when computing a new mapping in case of task addition, change or removal, thus minimizing
  runtime overhead. We evaluate our prototype implementation with a set of streaming
  task graphs and compare our results to an optimal static scheduler based on integer
  linear programming. We find that our prototype is able to meet throughput requirements
  with <3.5% energy overhead on average compared to the optimal scheduler.
---
