---
title: "Performance scaling variability and energy analysis for a resilient ULFM-based PDE solver"
date: 2016-11-01
publishDate: 2024-01-14T04:46:17.689440Z
authors: ["K. Morris", "F. Rizzi", "B. Cook", "P. Mycek", "O. Le Maître", "O. Knio", "K. Sargsyan", "K. Dahlgren", "B. Debusschere"]
publication_types: ["1"]
abstract: "We present a resilient task-based domain-decomposition preconditioner for partial differential equations (PDEs) built on top of User Level Fault Mitigation Message Passing Interface (ULFM-MPI). The algorithm reformulates the PDE as a sampling problem, followed by a robust regression-based solution update that is resilient to silent data corruptions (SDCs). We adopt a server-client model where all state information is held by the servers, while clients only serve as computational units. The task-based nature of the algorithm and the capabilities of ULFM complement each other to support missing tasks, making the application resilient to clients failing.We present weak and strong scaling results on Edison, National Energy Research Scientific Computing Center (NERSC), for a nominal and a fault-injected case, showing that even in the presence of faults, scalability tested up to 50k cores is within 90%. We then quantify the variability of weak and strong scaling due to the presence of faults. Finally, we discuss the performance of our application with respect to subdomain size, server/client configuration, and the interplay between energy and resilience."
featured: false
publication: "*7th Workshop on Latest Advances in Scalable Algorithms for Large-Scale Systems (ScalA)*"
doi: "10.1109/ScalA.2016.010"
---

