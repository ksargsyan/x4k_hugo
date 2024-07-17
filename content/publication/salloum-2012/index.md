---
title: "A Stochastic Multiscale Coupling Scheme to Account for Sampling Noise in Atomistic-to-Continuum Simulations"
date: 2012-05-01
publishDate: 2024-07-17T17:20:03.486110Z
authors: ["Maher Salloum", "Khachik Sargsyan", "Reese Jones", "Bert Debusschere", "Habib N. Najm", "Helgi Adalsteinsson"]
publication_types: ["2"]
abstract: "We present a methodology to assess the predictive fidelity of multiscale simulations by incorporating uncertainty in the information exchanged between the atomistic and continuum simulation components. Focusing on uncertainty due to finite sampling in molecular dynamics (MD) simulations, we present an iterative stochastic coupling algorithm that relies on Bayesian inference to build polynomial chaos expansions for the variables exchanged across the atomistic-continuum interface. We consider a simple Couette flow model where velocities are exchanged between the atomistic and continuum components. To alleviate the burden of running expensive MD simulations at every iteration, a surrogate model is constructed from which samples can be efficiently drawn as data for the Bayesian inference. Results show convergence of the coupling algorithm at a reasonable number of iterations. The uncertainty associated with the exchanged variables significantly depends on the amount of data sampled from the MD simulations and on the width of the time averaging window used in the MD simulations. Sequential Bayesian updating is also implemented in order to enhance the accuracy of the stochastic algorithm predictions."
featured: false
publication: "*Multiscale Modeling & Simulation*"
doi: "10.1137/110844404"
---

