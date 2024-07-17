---
title: "Active Learning for SNAP Interatomic Potentials via Bayesian Predictive Uncertainty"
date: 2024-01-01
publishDate: 2024-07-17T17:07:40.142711Z
authors: ["Logan Williams", "Khachik Sargsyan", "Andrew Rohskopf", "Habib N. Najm"]
publication_types: ["2"]
abstract: "Bayesian inference with a simple Gaussian error model is used to efficiently compute prediction variances for energies, forces, and stresses in the linear SNAP interatomic potential. The prediction variance is shown to have a strong correlation with the absolute error over approximately 24 orders of magnitude. Using this prediction variance, an active learning algorithm is constructed to iteratively train a potential by selecting the structures with the most uncertain properties from a pool of candidate structures. The relative importance of the energy, force, and stress errors in the objective function is shown to have a strong impact upon the trajectory of their respective net error metrics when running the active learning algorithm. Batched training of different batch sizes is also tested against singular structure updates, and it is found that batches can be used to significantly reduce the number of retraining steps required with only minor impact on the active learning trajectory."
featured: false
publication: "*Computational Materials Science*"
tags: ["interatomic potentials", "bayesian inference", "uncertainty quantification", "active learning"]
doi: "https://doi.org/10.1016/j.commatsci.2024.113074"
---

