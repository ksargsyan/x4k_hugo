---
title: "Uncertainty Quantification in MD Simulations. Part II: Inference of force-field parameters"
date: 2012-12-01
publishDate: 2024-01-14T17:37:25.153589Z
authors: ["F. Rizzi", "O. M. Knio", "H. N. Najm", "B. J. Debusschere", "K. Sargsyan", "M. Salloum", "H. Adalsteinsson"]
publication_types: ["2"]
abstract: "This paper explores the inference of small-scale, atomistic parameters, based on the specification of large, or macroscale, observables. Specifically, we focus on estimating a set of force-field parameters for the four-site, TIP4P, water model, based on a synthetic problem involving isothermal, isobaric molecular dynamics (MD) simulations of water at ambient conditions. We exploit the polynomial chaos (PC) expansions developed in Part I as surrogate representations of three macroscale observables, namely density, self-diffusion, and enthalpy, as a function of the force-field parameters. We analyze and discuss the use of two different PC representations in a Bayesian framework for the inference of atomistic parameters, based on synthetic observations of three macroscale observables. The first surrogate is a deterministic PC representation, constructed in Part I using nonintrusive spectral projection (NISP). An alternative strategy exploits a nondeterministic PC representation obtained using Bayesian inference of PC coefficients. We analyze the sensitivity of selected force-field parameters to the macroscale data, namely by exploiting the surrogate models to derive suitable “response” surfaces in the space of random parameters. The performance of both inference strategies is then examined in light of this analysis. The results show that each parameter is very sensitive to certain observables, while being only minimally affected by others. We show that a suitable choice of the observables allows us to recover the presumed “true” set of parameters with high accuracy even with low-order surrogate models."
featured: false
publication: "*SIAM J. Multiscale Model. Simul*"
doi: "10.1137/110853170"
---

