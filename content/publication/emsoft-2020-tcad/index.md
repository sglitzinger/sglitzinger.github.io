---
title: Static Scheduling of Moldable Streaming Tasks With Task Fusion for Parallel
  Systems With DVFS
authors:
- Christoph Kessler
- Sebastian Litzinger
- Jörg Keller
date: '2020-01-06'
publishDate: '2024-08-19T12:43:31.596094Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Computer-Aided Design of Integrated Circuits and
  Systems*'
doi: 10.1109/TCAD.2020.3013054
abstract: We consider the problem of statically scheduling a task graph of moldable
  streaming tasks (i.e., the actor network) to a multicore or many-core CPU with discrete
  dynamic voltage and frequency scaling (DVFS). We employ an integer linear programming
  (ILP) approach that combines allocating cores to tasks, mapping tasks to core subsets,
  selecting a DVFS level for each task, and considering all options for task fusion
  as provided by a cost model, given data throughput and latency requirements and
  targeting low energy consumption. We also propose a partly decoupled approach that
  applies greedy prefusion before running an ILP-based scheduler considering the other
  three subproblems together. We use microbenchmarking on an ARM big.LITTLE architecture
  to quantify the advantage of task fusion in the above setting, and evaluate the
  use of task fusion in terms of energy savings, latency improvement, and scheduling
  time for three real-world applications. We confirm the scheduling results by running
  the applications with and without task fusions on the ARM big.LITTLE. Results indicate
  that streaming applications can profit from task fusion, as we achieve a significant
  reduction of energy consumption in most cases, while scheduling time is only moderately
  increased.
---
