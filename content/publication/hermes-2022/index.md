---
title: "Sella, an Open-Source Automation-Friendly Molecular Saddle Point Optimizer"
date: 2022-01-01
publishDate: 2024-01-14T20:20:43.269352Z
authors: ["Eric D. Hermes", "Khachik Sargsyan", "Habib N. Najm", "Judit Zádor"]
publication_types: ["2"]
abstract: "We present a new algorithm for the optimization of molecular structures to saddle points on the potential energy surface using a redundant internal coordinate system. This algorithm automates the procedure of defining the internal coordinate system, including the handling of linear bending angles, for example, through the addition of dummy atoms. Additionally, the algorithm supports constrained optimization using the null-space sequential quadratic programming formalism. Our algorithm determines the direction of the reaction coordinate through iterative diagonalization of the Hessian matrix and does not require evaluation of the full Hessian matrix. Geometry optimization steps are chosen using the restricted step partitioned rational function optimization method, and displacements are realized using a high-performance geodesic stepping algorithm. This results in a robust and efficient optimization algorithm suitable for use in automated frameworks. We have implemented our algorithm in Sella, an open-source software package designed to optimize atomic systems to saddle point structures. We also introduce a new benchmark test comprising 500 molecular structures that approximate saddle point geometries and show that our saddle point optimization algorithm outperforms the algorithms implemented in several leading electronic structure theory packages."
featured: false
publication: "*Journal of Chemical Theory and Computation*"
doi: "10.1021/acs.jctc.2c00395"
---

