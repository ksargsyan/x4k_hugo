---
title: "Uncertainty Quantification in MD Simulations. Part I: Stochastic Reformulation of the Forward Problem"
date: 2012-12-01
publishDate: 2024-01-14T20:20:43.278169Z
authors: ["Francesco Rizzi", "Omar Knio", "Habib N. Najm", "Bert Debusschere", "Khachik Sargsyan", "Maher Salloum", "Helgi Adalsteinsson"]
publication_types: ["2"]
abstract: "This work focuses on quantifying the effect of intrinsic (thermal) noise and parametric uncertainty in molecular dynamics (MD) simulations. We consider isothermal, isobaric MD simulations of TIP4P (or four-site) water at ambient conditions, $T=298$ K and $P=1$ atm. Parametric uncertainty is assumed to originate from three force-field parameters that are parametrized in terms of standard uniform random variables. The thermal fluctuations inherent in MD simulations combine with parametric uncertainty to yield nondeterministic, noisy MD predictions of bulk water properties. Relying on polynomial chaos (PC) expansions, we develop a framework that enables us to isolate the impact of parametric uncertainty on the MD predictions and control the effect of the intrinsic noise. We construct the PC representations of quantities of interest (QoIs) using two different approaches: nonintrusive spectral projection (NISP) and Bayesian inference. We verify a priori the legitimacy of the NISP approach by verifying that the MD data satisfy regularity and smoothness conditions in the parameter space. The Bayesian inference approach relies on adaptively sampling the parameter space, based on analyzing the convergence of the PC expansions at different approximation levels. We show that for the present case, the effect of the thermal noise in the atomistic system can be controlled, and the MD predictions for the QoIs can be suitably represented using low-order PC models."
featured: false
publication: "*SIAM J. Multiscale Model. Simul*"
doi: "10.1137/110853169"
---

