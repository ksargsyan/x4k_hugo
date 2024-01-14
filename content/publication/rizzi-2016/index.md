---
title: "ULFM-MPI implementation of a resilient task-based partial differential equations preconditioner"
date: 2016-05-01
publishDate: 2024-01-14T19:27:19.587039Z
authors: ["F. Rizzi", "K. Morris", "K. Sargsyan", "P. Mycek", "C. Safta", "B. Debusschere", "O. Le Maı̂tre", "O. Knio"]
publication_types: ["1"]
abstract: "We present a task-based domain-decomposition preconditioner for partial differential equations (PDEs) resilient to silent data corruption (SDC) and hard faults.  The algorithm exploits a reformulation of the PDE as a sampling problem, followed by a regression-based solution update that is resilient to SDC. We adopt a server-client model implemented using the User Level Fault Mitigation MPI (MPI-ULFM). All state information is held by the servers, while clients only serve as computational units. The task-based nature of the algorithm and the capabilities of ULFM are complemented at the algorithm level to support missing tasks, making the application resilient to hard faults affecting the clients.  Weak and strong scaling tests up to ~115k cores show an excellent performance of the application with efficiencies above 90%, demonstrating the suitability to run at large scale. We demonstrate the resilience of the application for a 2D elliptic PDE by injecting SDC using a random single bit-flip model, and hard faults in the form of clients crashing. We show that in all cases, the application converges to the right solution. We analyze the overhead caused by the faults, and show that, for the test problem considered, the overhead incurred due to SDC is minimal compared to that from the hard faults."
featured: false
publication: "*Proceedings of the ACM Workshop on Fault-Tolerance for HPC at Extreme Scale*"
doi: "10.1145/2909428.2909429"
---

