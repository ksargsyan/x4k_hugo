---
title: "The Pitfalls of Provisioning Exascale Networks: A Trace Replay Analysis for Understanding Communication Performance"
date: 2018-05-01
publishDate: 2024-01-14T04:46:17.690141Z
authors: ["J. Kenny", "K. Sargsyan", "S. Knight", "G. Michelogiannakis", "J. Wilke"]
publication_types: ["1"]
abstract: "Data movement is considered the main performance concern for exascale, including both on-node memory and off-node network communication. Indeed, many application traces show significant time spent in MPI calls, potentially indicating that faster networks must be provisioned for scalability. However, equating MPI times with network communication delays ignores synchronization delays and software overheads independent of network hardware. Using point-to-point protocol details, we explore the decomposition of MPI time into communication, synchronization and software stack components using architecture simulation. Detailed validation using Bayesian inference is used to identify the sensitivity of performance to specific latency/bandwidth parameters for different network protocols and to quantify associated uncertainties. The inference combined with trace replay shows that synchronization and MPI software stack overhead are at least as important as the network itself in determining time spent in communication routines."
featured: false
publication: "*High Performance Computing*"
doi: "10.1007/978-3-319-92040-5_14"
---

