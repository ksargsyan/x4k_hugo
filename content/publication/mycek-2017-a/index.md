---
title: "A resilient domain decomposition polynomial chaos solver for uncertain elliptic PDEs"
date: 2017-07-01
publishDate: 2024-01-14T04:09:23.178229Z
authors: ["P. Mycek", "A. Contreras", "O. Le Maı̂tre", "K. Sargsyan", "F. Rizzi", "K. Morris", "C. Safta", "B. Debusschere", "O. Knio"]
publication_types: ["2"]
abstract: "A resilient method is developed for the solution of uncertain elliptic PDEs on extreme scale platforms. The method is based on a hybrid domain decomposition, polynomial chaos (PC) framework that is designed to address soft faults. Specifically, parallel and independent solves of multiple deterministic local problems are used to define PC representations of local Dirichlet boundary-to-boundary maps that are used to reconstruct the global solution. A LAD-lasso type regression is developed for this purpose. The performance of the resulting algorithm is tested on an elliptic equation with an uncertain diffusivity field. Different test cases are considered in order to analyze the impacts of correlation structure of the uncertain diffusivity field, the stochastic resolution, as well as the probability of soft faults. In particular, the computations demonstrate that, provided sufficiently many samples are generated, the method effectively overcomes the occurrence of soft faults."
featured: false
publication: "*Computer Physics Communications*"
doi: "10.1016/j.cpc.2017.02.015"
---

