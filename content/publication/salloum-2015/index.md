---
title: "Quantifying Sampling Noise and Parametric Uncertainty in Atomistic-to-Continuum Simulations Using Surrogate Models"
date: 2015-08-01
publishDate: 2024-01-14T04:30:54.093915Z
authors: ["M. Salloum", "K. Sargsyan", "R. Jones", "H. Najm", "B. Debusschere"]
publication_types: ["2"]
abstract: "We present a methodology to assess the predictive fidelity of multiscale simulations by incorporating uncertainty in the information exchanged between the components of an atomistic-to-continuum simulation. We account for both the uncertainty due to finite sampling in molecular dynamics (MD) simulations and the uncertainty in the physical parameters of the model. Using Bayesian inference, we represent the expensive atomistic component by a surrogate model that relates the long-term output of the atomistic simulation to its uncertain inputs. We then present algorithms to solve for the variables exchanged across the atomistic-continuum interface in terms of polynomial chaos expansions (PCEs). We consider a simple Couette flow where velocities are exchanged between the atomistic and continuum components, while accounting for uncertainty in the atomistic model parameters and the continuum boundary conditions. Results show convergence of the coupling algorithm at a reasonable number of iterations. The uncertainty in the obtained variables significantly depends on the amount of data sampled from the MD simulations and on the width of the time averaging window used in the MD simulations."
featured: false
publication: "*Multiscale Modeling & Simulation*"
doi: "10.1137/140989601"
---

