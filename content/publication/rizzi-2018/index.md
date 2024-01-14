---
title: "Exploring the interplay of resilience and energy consumption for a task-based partial differential equations preconditioner"
date: 2018-01-01
publishDate: 2024-01-14T19:27:19.587952Z
authors: ["F. Rizzi", "K. Morris", "K. Sargsyan", "P. Mycek", "C. Safta", "O. Le Maître", "O. M. Knio", "B. J. Debusschere"]
publication_types: ["2"]
abstract: "We discuss algorithm-based resilience to silent data corruptions (SDCs) in a task-based domain-decomposition preconditioner for partial differential equations (PDEs). The algorithm exploits a reformulation of the PDE as a sampling problem, followed by a solution update through data manipulation that is resilient to SDCs. The implementation is based on a server-client model where all state information is held by the servers, while clients are designed solely as computational units. Scalability tests run up to ∼51K cores show a parallel efficiency greater than 90%. We use a 2D elliptic PDE and a fault model based on random single and double bit-flip to demonstrate the resilience of the application to synthetically injected SDC. We discuss two fault scenarios: one based on the corruption of all data of a target task, and the other involving the corruption of a single data point. We show that for our application, given the test problem considered, a four-fold increase in the number of faults only yields a 2% change in the overhead to overcome their presence, from 7% to 9%. We then discuss potential savings in energy consumption via dynamic voltage/frequency scaling, and its interplay with fault-rates, and application overhead."
featured: false
publication: "*Parallel Computing*"
tags: ["resiliency", "server-client programming model", "dynamic voltage/frequency scaling", "pde", "domain-decomposition", "silent data corruption"]
doi: "https://doi.org/10.1016/j.parco.2017.05.005"
---

