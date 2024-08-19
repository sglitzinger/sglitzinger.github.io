---
title: Systematic search space design for energy-efficient static scheduling of moldable
  tasks
authors:
- Jörg Keller
- Sebastian Litzinger
date: '2022-01-01'
publishDate: '2024-08-19T12:43:31.528532Z'
publication_types:
- article-journal
publication: '*Journal of Parallel and Distributed Computing*'
doi: https://doi.org/10.1016/j.jpdc.2022.01.004
abstract: Static scheduling of independent, moldable tasks on parallel machines with
  frequency scaling comprises decisions on core allocation, assignment, frequency
  scaling and ordering, to meet a deadline and minimize energy consumption. Constraining
  some of these decisions reduces the solution space, i.e. may increase energy consumption,
  but may also open the path to new, near-optimal approaches. We investigate how constraints
  of different steps influence energy consumption, starting with an unrestricted scheduler
  for moldable tasks. The constraints are partly derived from existing schedulers,
  but also generalized in a systematic way. We present integer linear programs for
  all scheduling variants. We compare energy consumption of schedules for a benchmark
  suite of synthetic task sets of different sizes and for task sets derived from real
  applications. In addition, we check how close the results are to the optimum results
  when the ILP solver meets a timeout. Our results indicate that constraints on task
  execution order, which avoid explicit representation of task order in ILPs, are
  mostly responsible for near-optimal energy consumption among large task sets. Furthermore,
  we find that for all steps except allocation, non-optimal fast heuristics can be
  used without sacrificing too much energy for the resulting schedule. Finally, we
  can show that an ILP for a new scheduler, for which also a heuristic version exists,
  is comparable in quality to more complicated schedulers.
tags:
- Static scheduling
- Energy efficiency
- Moldable tasks
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0743731522000107
---
