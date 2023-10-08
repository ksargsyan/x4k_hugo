---
title: Dimensionality Reduction and Physics-Informed Recurrent Neural Networks for Climate Land Models
authors: ["Khachik Sargsyan, Cosmin Safta, Daniel Ricciuto"]
event: AGU Fall Meeting
event_url: https://www.agu.org/fall-meeting-2020
location: virtual
summary: Poster
abstract: "This work focuses on approximating complex land surface models. Such approximations, or surrogates, are necessary for compute-intensive tasks, such as uncertainty quantification or model calibration. The primary model of interest is the land component of the Energy Exascale Earth System Model (E3SM).<br><br>Using an ensemble of model training simulations, the development of a model surrogate is cast as a supervised machine learning (ML) problem. For expensive models with a large number of input parameters, the critical challenge is to create high-fidelity spatio-temporal surrogates with as few model training evaluations as possible. We rely on Karhunen-Loeve expansions to account for spatial correlations of model outputs, while the temporal evolution is best approximated with long-short term memory (LSTM) recurrent neural network. Besides, considering the already known interactions between input processes and output quantities of interest (QoIs), we develop a special LSTM architecture with predefined connections between these QoIs. Such physics-informed architecture with reduced spatial dimensionality is shown to outperform, both in accuracy and efficiency, vanilla LSTM implementations and cell-based independent surrogates. We then employ the resulting spatio-temporal surrogate to extract parameter sensitivity indices, as well as to perform model calibration given global observational data on select QoIs."
date: "2020-12-01"
publishDate: "2020-12-01"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: ""
---
