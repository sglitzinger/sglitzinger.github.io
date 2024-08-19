---
title: Temperature-Aware Energy-Optimal Scheduling of Moldable Streaming Tasks onto
  2D-Mesh-Based Many-Core CPUs with DVFS
authors:
- Christoph Kessler
- Jörg Keller
- Sebastian Litzinger
date: '2021-01-01'
publishDate: '2024-08-19T12:43:31.549195Z'
publication_types:
- paper-conference
publication: '*Job Scheduling Strategies for Parallel Processing*'
doi: https://doi.org/10.1007/978-3-030-88224-2_9
abstract: We consider the problem of energy-optimally mapping a set of moldable-parallel
  tasks in the steady-state pattern of a software-pipelined streaming computation
  onto a generic many-core CPU architecture with a 2D mesh geometry, where the execution
  voltage and frequency levels of the cores can be selected dynamically from a given
  set of discrete DVFS levels. We extend the Crown Scheduling technique for parallelizable
  tasks to temperature-aware scheduling, taking into account the tasks' heat generation,
  the heat limit for each core, and the heat diffusion along the 2D mesh geometry
  of typical many-core CPU architectures. Our approach introduces a systematic method
  for alternating task executions between disjoint ``buddy'' core groups in subsequent
  iterations of crown schedules to avoid long-time overheating of cores. We present
  two integer linear program (ILP) solutions with different degrees of flexibility,
  and show that these can be solved for realistic problem sizes with today's ILP solver
  technology. Experiments with several streaming task graphs derived from real-world
  applications show that the flexibility for the scheduler can be greatly increased
  by considering buddy-cores, thus finding feasible solutions in scenarios that could
  not be solved otherwise. We also present a fast heuristic for the same problem.
links:
- name: URL
  url: https://link.springer.com/chapter/10.1007/978-3-030-88224-2_9
---
