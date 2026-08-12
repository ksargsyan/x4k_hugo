---
title: Spatio-Temporal Surrogate Construction and Calibration of E3SM Land Model
authors: ["Khachik Sargsyan, Daniel Ricciuto"]
event: ESCO 2024 - 9th European Seminar on Computing
event_url: https://esco2024.femhub.com/
location: (virtual) Plzen, Czechia
summary: Talk
abstract: "Prediction uncertainties in the Energy Exascale Earth System (E3SM) land model (ELM) are caused in part by uncertain parameters related fluxes of carbon and energy [1]. Uncertainty quantification and calibration methods hinge on the development of surrogate models that replicate the ELM output behavior with respect to these uncertain input parameters. A major challenge is the high dimensionality of the output spatio-temporal fields.
We use Karhunen-Loève (KL) expansion to reduce a large set of spatio-temporal outputs to a small number of latent variables. Neural network (NN) surrogates are then constructed for all latent variables with respect to model input parameters. We employ Residual NNs with layer-parameterized weights that regularize the training and improve performance in approximating the input-output maps. A KLNN surrogate is then interrogated for global sensitivity analysis, as well as in Bayesian calibration using gridded observations of gross primary productivity, the main model output. Bayesian calibration is carried out with Markov chain Monte Carlo, with the likelihoods developed in the latent space to enhance computational feasibility.
We demonstrate the surrogate construction and calibration for ELM with 275 training simulations at 2x2 degree spatial and monthly temporal resolution over a 15-year time period while perturbing 10 model parameters.
<br>
[1] D. Ricciuto and K. Sargsyan and P. Thornton. The Impact of Parametric Uncertainties on Biogeochemistry in the E3SM Land Model. Journal of Advances in Modeling Earth Systems, 10 (2), 297-319, 2018."
date: "2024-06-10"
publishDate: "2024-06-10"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2024_06_esco.pdf"
loc: "$WW/projects/E3SM/Land_model_UQ/talks/ESCO_May2024"
---
