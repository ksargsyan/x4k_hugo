---
title: "Scalability of Partial Differential Equations Preconditioner Resilient to Soft and Hard Faults"
date: 2016-06-01
publishDate: 2024-01-14T23:36:48.305786Z
authors: ["Karla Morris", "Francesco Rizzi", "Khachik Sargsyan", "K. Dahlgren", "Paul Mycek", "Cosmin Safta", "Olivier Le Maître", "Omar Knio", "Bert Debusschere"]
publication_types: ["1"]
abstract: "We present a resilient domain-decomposition preconditioner for partial differential equations (PDEs). The algorithm reformulates the PDE as a sampling problem, followed by a solution update through data manipulation that is resilient to both soft and hard faults. We discuss an implementation based on a server-client model where all state information is held by the servers, while clients are designed solely as computational units. Servers are assumed to be “sandboxed”, while no assumption is made on the reliability of the clients. We explore the scalability of the algorithm up to ∼12k cores, build an SST/macro skeleton to extrapolate to ~50k cores, and show the resilience under simulated hard and soft faults for a 2D linear Poisson equation."
featured: false
publication: "*Proceedings of High Performance Computing: 31st International Conference, ISC High Performance 2016, Frankfurt, Germany, June 19-23, 2016*"
doi: "10.1007/978-3-319-41321-1_24"
---

