---
title: Reduced-Dimensional Neural Network Surrogate Construction and Calibration of the E3SM Land Model
authors: ["Khachik Sargsyan, Daniel Ricciuto"]
event: AGU Fall Meeting 2023
event_url: https://agu.confex.com/agu/fm23/meetingapp.cgi/Search/0
location: San Francisco, CA
summary: Talk
abstract: "Prediction uncertainties in the Energy Exascale Earth System (E3SM) land model (ELM) are caused in part by uncertain parameters related to ecosystem processes that control fluxes of carbon and energy. Uncertainty quantification and calibration methods hinge on the development of surrogate models that replicate the ELM output behavior with respect to these uncertain input parameters. A particular challenge is the high dimensionality of the output spatio-temporal fields.<br>
In this work, we used Karhunen-Loève (KL) expansion to reduce a large number of spatio-temporal outputs to a handful of eigen-features or latent variables. This is followed by a neural network (NN) surrogate construction for all the latent variables with respect to input parameters of the model. Specifically, we employ Residual NNs with layer-parameterized weights that regularize the training and show improved performance in approximating the input-output maps. The resulting KLNN surrogate serves as an inexpensive approximation for the ELM spatio-temporal output of gross primary productivity (GPP). The surrogate is then employed for global sensitivity analysis via variance-based decomposition. Finally, using gridded observational datasets, we perform Markov-chain Monte Carlo based Bayesian calibration using the KLNN surrogate in place of the ELM. We construct Bayesian likelihoods via model/data discrepancy in the KL latent space instead of the full spatio-temporal space. We investigate the behavior of the calibrated parameters with respect to plant functional types (PFTs) of each land cell and propose a reparameterization strategy that incorporates parameter dependence on these PFTs.<br>
We demonstrate the spatio-temporal surrogate construction and subsequent calibration for ELM with 275 training simulations at 2x2 degree spatial resolution and monthly temporal resolution over a 15-year time period while perturbing 10 uncertain parameters of the model."
date: "2023-12-11"
publishDate: "2023-12-11"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2023_12_agu.pdf"
loc: "$WW/projects/E3SM/Land_model_UQ/talks/AGU_2023"
---
