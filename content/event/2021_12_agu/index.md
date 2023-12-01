---
title: Hit Twice by the Curse of Dimensionality; Spatio-Temporal Land Model Calibration using Karhunen-Loeve and Sparse Polynomial Chaos Expansions
authors: ["Khachik Sargsyan, Daniel Ricciuto, Cosmin Safta"]
event: AGU Fall Meeting
event_url: https://www.agu.org/fall-meeting-2021
location: (virtual) New Orleans, LA
summary: Poster
abstract: "This work is focused on the land component of the Energy Exascale Earth System Model (E3SM). Prediction uncertainties in the E3SM land model (ELM) are caused in part by a large number of uncertain parameters related to ecosystem processes that control fluxes of carbon and energy. Studying the ELM performance with respect to variations in these parameters is an essential task of forward uncertainty quantification (UQ) and is challenged by a large number of such uncertain parameters as well as the ELM computational expense. Besides this curse of dimensionality in the input, calibrating these parameters (inverse UQ), is challenged by the high-dimensional, spatio-temporal output fields of model evaluations and observational data.<br><br>We will demonstrate Bayesian calibration of ELM parameters using gridded observation datasets. The work incorporates a range of dimensionality reduction techniques, including Karhunen-Loeve (KL) expansions of spatio-temporal outputs and sparse polynomial chaos representations of KL modes. Accordingly, a surrogate-based likelihood function is constructed with an additional statistical representation corresponding to model structural error. The resulting embedded model-error strategy disambiguates model error from data noise and leads to predictions with attributable uncertainties. Bayesian inference via adaptive Markov chain Monte Carlo sampling reveals that the dominant component of predictive uncertainty is model structural error highlighting the need for augmenting model parameters with a spatio-temporal structure in order to improve predictability. The developed workflow heavily relies on capabilities available in UQ Toolkit (www.sandia.gov/uqtoolkit)."
date: "2021-12-13"
publishDate: "2021-12-13"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2021_12_agu.pdf"
loc: "${WW}/projects/OSCM/repos/cluq/doc/talk/agu21/calib"
---
