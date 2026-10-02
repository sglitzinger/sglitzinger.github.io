---
title: 'Mapping and scheduling swarms of moldable streaming applications for energy-efficient computing in the heterogeneous edge-cloud continuum'
authors:
- Sajad Khosravi
- Sebastian Litzinger
- Christoph Kessler
- Jörg Keller
date: '2026-07-25'
publishDate: '2026-07-25T00:43:31.507864Z'
publication_types:
- article-journal
publication: '*Cluster Computing*'
doi: 10.1007/s10586-026-06234-2
abstract: 'We consider the problem of cost-effectively mapping a swarm of soft real-time stream processing applications with moldable-parallel tasks to multicore resources in the device-edge-cloud continuum, consisting of mobile devices, edge resources and cloud resources. We leverage flexibility from different parallelization degrees and frequency levels (DVFS) for the tasks, keeping application throughput constraints and communication bandwidth limitations while minimizing overall cost (including device/edge resource energy, communication cost and cloud resource renting). We present several offline algorithmic solutions with a global view of the environment: an integer linear program (ILP) extending the crown scheduling approach for multi-layer distributed systems, a variant leveraging symmetries in application and system structure, and a greedy heuristic algorithm. We also expanded the problem formulation to consider the dynamic joining of application task graphs, introducing a dynamic approach based on the proposed ILP and greedy heuristic algorithm. Our experimental evaluation for several real-world and synthetic scenarios shows that the time required for solving the scheduling problem to cost-optimality by the ILP is feasible for nontrivial scenarios. The heuristic achieves about 3% worse cost efficiency on average, yet operates much faster (by 1–2 orders of magnitude), allowing to scale up the problem size more than the ILP approach. The symmetry-folding applied to the ILP approach improves its optimization time by about 1 order of magnitude, at the expense of less than a 5% increase in cost compared to a non-folded static ILP solution. The heuristic is likewise accelerated by leveraging symmetry, though to a minor extent. The dynamic incremental variant of the ILP approach reduces the long optimization time of the static ILP method with a minor cost penalty compared to a clean-slate offline solution.'
links:
- name: URL
  url: https://link.springer.com/article/10.1007/s10586-026-06234-2
---
