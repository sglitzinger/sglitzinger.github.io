---
title: Energy-Efficient Execution of Streaming Task Graphs with Parallelizable Tasks
  on Multicore Platforms with Core Failures
authors:
- Jörg Keller
- Sebastian Litzinger
date: '2022-01-03'
publishDate: '2024-08-19T12:43:31.522166Z'
publication_types:
- paper-conference
publication: '*Euro-Par 2021: Parallel Processing Workshops*'
doi: 10.1007/978-3-031-06156-1_26
abstract: Real-time applications often take the form of streaming applications, where
  a stream of inputs such as camera images is processed by an application represented
  as a task graph. The workload together with the required throughput often necessitates
  processing on a multicore system and also demands parallelization of large tasks.
  We extend a scheduling algorithm for such applications, originally devised to handle
  varying task workloads, to also cover varying core count, e.g. caused by failure
  of a core. We use frequency scaling to accelerate processing when the necessity
  to re-execute tasks from the crashed core arises, to maintain throughput. We evaluate
  the algorithm by scheduling synthetic task graphs that represent corner cases and
  a real streaming application.
---
