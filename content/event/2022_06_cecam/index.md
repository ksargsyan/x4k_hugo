---
title: Model Error Estimation and Uncertainty Quantification of Machine Learning Interatomic Potentials
authors: ["Khachik Sargsyan, Logan Williams, Habib N. Najm"]
event: Error control in first-principles modelling
event_url: https://www.cecam.org/workshop-details/1115
location: (virtual) Lausanne, Switzerland
summary: Talk
abstract: "Large scale molecular dynamics (MD) simulations rely on interatomic potentials that are pre-constructed using ab initio data as well as both empirical and physical considerations. Specifically, machine-learned interatomic potentials (MLIAPs) are fitted to data available from expensive quantum chemistry computations. These MLIAPs encapsulate the functional relationship between the atomic configuration and the potential energy of an atomic system, and are trained in a supervised machine learning context. Trained MLIAPs sacrifice some quantum mechanical accuracy due to their model form while allowing study of systems with up to a million atoms.<br><br>Uncertainty quantification (UQ) for MLIAPs is critical for both training data selection and model selection. Besides, MLIAPs equipped with UQ enable the propagation of uncertainty through MD simulations, thereby providing uncertainty estimates on MD simulation outputs and allowing for meaningful comparisons with experimentally observed macroscale quantities of interest.<br><br>In this talk, we will discuss our work on a range of UQ approaches for MLIAPs from the perspective of model error estimation and subsequent propagation of uncertainties through MD simulations. This includes Bayesian inference of MLIAP parameters via both sampling and approximate methods, as well as embedded model error estimation, which augments MLIAP parameters with statistical error terms to be inferred within the Bayesian framework. In the context of Spectral Neighbor Analysis Potential (SNAP), we will demonstrate model error embedded MLIAP construction and its subsequent propagation through MD simulations using polynomial chaos representations."
date: "2022-06-23"
publishDate: "2022-06-23"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2022_06_cecam.pdf"
loc: "$WW/projects/FusMatML/repos/fumat/doc/talk/cecam/khs"
---
