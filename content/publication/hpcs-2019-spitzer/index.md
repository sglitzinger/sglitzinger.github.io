---
title: Probabilistic Runtime Guarantees for Statically Scheduled Taskgraphs with Stochastic
  Task Runtimes
authors:
- Jörg Keller
- Sebastian Litzinger
- Wolfgang Spitzer
date: '2019-01-01'
publishDate: '2024-08-19T12:43:31.648655Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 17th International Conference on High Performance
  Computing & Simulation (HPCS)*'
doi: 10.1109/HPCS48598.2019.9188194
abstract: Tasks with stochastic runtimes and dependencies are frequently met in multicore
  applications, but static schedulers need deterministic task runtimes as input. We
  first demonstrate by scheduling experiments that both for binomially and geometrically
  distributed task runtimes, which are often found in taskgraphs, choice of average
  task runtime as scheduler input is sufficient to obtain schedules with good average
  makespan, i.e. that inserting runtime buffers depending on the standard deviation
  of task runtimes is not helpful in the majority of cases. Furthermore, we compute
  discretized makespan distributions for schedules with binomially and geometrically
  distributed runtimes as frequently occuring distributions. Thus, applications where
  probabilistic makespan guarantees with quantiles (vs. worst case execution times)
  are usable can profit from our analysis by starting with sampling their makespan
  distribution to approximate mean and standard deviation, and using our tool to compute
  the makespan distribution. As a side effect, we see that the rule of thumb “makespan
  is below average plus three (one) standard deviations in 99% of cases for binomially
  (geometrically) distributed runtimes” still apply, although makespans are not binomially
  or geometrically distributed but exhibit heavy tails. We also show how to mathematically
  derive makespan distribution for taskgraphs with stochastic task runtimes for different
  distributions, if stronger guarantees are needed.
---
