---
title: Overview of Uncertainty Quantification Methods for Complex Models
authors: ["Khachik Sargsyan, Cosmin Safta, Daniel Ricciuto"]
event: Climate Modeling Principal Investigators' Meeting
event_url: https://globalchange.ucdavis.edu/events/2018-doe-modeling-pi-meeting
location: Potomac, MD
summary: Talk
abstract: "Uncertainty quantification (UQ) is a critical part in any computational model development. However, when dealing with complex climate models, canonical UQ methods face a range of challenges including<br>- large number of input parameters<br>- nonlinear input-output maps<br>- computational expense of a single simulation<br>- scarcity of available observational data to constrain the models<br>- spatio-temporal, high-dimensional output fields<br>- structural errors due to oversimplification and missing physics<br><br>This work will highlight state-of-the-art methods for tackling the challenges above, in the context of two major UQ tasks<br>- forward UQ: uncertainty propagation, model surrogate construction and global sensitivity analysis<br>- inverse UQ: model calibration, parameter estimation<br><br>In particular, we will describe polynomial chaos surrogate construction enabling efficient propagation of uncertainty and global sensitivity analysis via variance-based decomposition. Input dimensionality reduction is achieved by sparsity-imposing regularization while high-dimensional spatio-temporal output field is represented by Karhunen-Loeve expansions. The inverse UQ is performed with Bayesian methods, via Markov chain Monte Carlo sampling. Bayesian machinery is well-suited to handle noisy and scarce observational data, while the required multiple model evaluations are alleviated by the pre-constructed surrogate usage. Furthermore, we will enhance the conventional Bayesian machinery to enable representation and propagation of uncertainties due to model structural errors. The overall framework allows efficient automated UQ with predictive uncertainty attributed to various sources such as parameter uncertainty, data noise and structural errors.<br><br>The developed workflow is connected to UQ Toolkit (www.sandia.gov/uqtoolkit). We will demonstrate the application of the methods to the E3SM land model using observational data from selected FLUXNET sites.<br>"
date: "2018-11-06"
publishDate: "2018-11-06"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2018_11_climate.pdf"
loc: "$WW/projects/OSCM/repos/OSCM_SciDAC/presentations/modeling18/talk"
---
