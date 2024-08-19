---
title: Crown-scheduling of sets of parallelizable tasks for robustness and energy-elasticity
  on many-core systems with discrete dynamic voltage and frequency scaling
authors:
- Christoph Kessler
- Sebastian Litzinger
- Jörg Keller
date: '2021-01-01'
publishDate: '2024-08-19T12:43:31.575168Z'
publication_types:
- article-journal
publication: '*Journal of Systems Architecture*'
doi: 10.1016/j.sysarc.2021.101999
abstract: Crown scheduling is a static scheduling approach for sets of parallelizable
  tasks with a common deadline, aiming to minimize energy consumption on parallel
  processors with frequency scaling. We demonstrate that crown schedules are robust,
  i.e. that the runtime prolongation of one task by a moderate percentage does not
  cause a deadline transgression by the same fraction. In addition, by speeding up
  some tasks scheduled after the prolonged task, the deadline can still be met at
  a moderate additional energy consumption. We present a heuristic to perform this
  re-scaling online and explore the tradeoff between additional energy consumption
  in normal execution and limitation of deadline transgression in delay cases. We
  evaluate our approach with scheduling experiments on synthetic and application task
  sets. Finally, we consider influence of heterogeneous platforms such as ARM’s big.LITTLE
  on robustness.
tags:
- Adaptive task scheduling
- Robustness of schedules
- Moldable parallel tasks
- Crown scheduling
- Energy optimization
links:
- name: URL
  url: http://www.sciencedirect.com/science/article/pii/S1383762121000175
---
