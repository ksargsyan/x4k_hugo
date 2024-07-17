---
title: Reduced-Dimensional Neural Network Surrogate Construction for the E3SM Land Model
authors: ["Khachik Sargsyan, Daniel Ricciuto"]
event: SIAM Conference on Uncertainty Quantification
event_url: https://www.siam.org/conferences/cm/conference/uq24
location: Trieste, Italy
summary: Talk
abstract: "Prediction uncertainties in the Energy Exascale Earth System (E3SM) land model (ELM) are caused in part by uncertain parameters related fluxes of carbon and energy. Uncertainty quantification and calibration methods hinge on the development of surrogate models that replicate the ELM output behavior with respect to these uncertain input parameters. A major challenge is the high dimensionality of the output spatio-temporal fields. <br> Here we used Karhunen-Loève (KL) expansion to reduce a large number of spatio-temporal outputs to a handful of eigen-features or latent variables. Neural network (NN) surrogates were then constructed for all latent variables with respect to model input parameters. We employ Residual NNs with layer-parameterized weights that regularize the training and improve performance in approximating the input-output maps. A KLNN surrogate is developed for gross primary productivity (GPP) and employed for global sensitivity analysis. We then perform Markov-chain Monte Carlo based Bayesian calibration using gridded GPP observations and the KLNN surrogate. We construct Bayesian likelihoods via model/data discrepancy in the KL latent space. <br> We investigate the behavior of the calibrated parameters with respect to plant functional types (PFTs). We demonstrate the surrogate construction and calibration for ELM with 275 training simulations at 2x2degree spatial and monthly temporal resolution over a 15-year time period while perturbing 10 model parameters."
date: "2024-03-01"
publishDate: "2024-03-01"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2024_03_siamuq.pdf"
loc: "$WW/projects/E3SM/Land_model_UQ/talks/SIAMUQ_Mar2024"
---
