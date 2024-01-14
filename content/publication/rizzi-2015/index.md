---
title: "Partial differential equations preconditioner resilient to soft and hard faults"
date: 2015-09-01
publishDate: 2024-01-14T17:52:59.913165Z
authors: ["F. Rizzi", "K. Morris", "K. Sargsyan", "P. Mycek", "C. Safta", "O. LeMaı̂tre", "O. Knio", "B. Debusschere"]
publication_types: ["1"]
abstract: "We present a domain-decomposition-based pre-conditioner for the solution of partial differential equations (PDEs) that is resilient to both soft and hard faults. The algorithm is based on the following steps: first, the computational domain is split into overlapping subdomains, second, the target PDE is solved on each subdomain for sampled values of the local current boundary conditions, third, the subdomain solution samples are collected and fed into a regression step to build maps between the subdomains' boundary conditions, finally, the intersection of these maps yields the updated state at the subdomain boundaries. This reformulation allows us to recast the problem as a set of independent tasks. The implementation relies on an asynchronous server-client framework, where one or more reliable servers hold the data, while the clients ask for tasks and execute them. This framework provides resiliency to hard faults such that if a client crashes, it stops asking for work, and the servers simply distribute the work among all the other clients alive. Erroneous subdomain solves (e.g. due to soft faults) appear as corrupted data, which is either rejected if that causes a task to fail, or is seamlessly filtered out during the regression stage through a suitable noise model. Three different types of faults are modeled: hard faults modeling nodes (or clients) crashing, soft faults occurring during the communication of the tasks between server and clients, and soft faults occurring during task execution. We demonstrate the resiliency of the approach for a 2D elliptic PDE, and explore the effect of the faults at various failure rates."
featured: false
publication: "*2015 IEEE International Conference on Cluster Computing (CLUSTER)*"
doi: "10.1109/CLUSTER.2015.103"
---

