---
title: Physics-informed Machine Learning for Uncertainty Quantification in Land Models
authors: ["Khachik Sargsyan, Cosmin Safta, Vishagan Ratnaswamy, Daniel Ricciuto"]
event: Joint Statistical Meetings
event_url: https://ww2.amstat.org/meetings/jsm/2020/
location: virtual
summary: Talk
abstract: "Complex physical models are computationally expensive, challenging ensemble-intensive studies such as parameter estimation, uncertainty quantification, and optimal experimental design. In order to make such studies tractable, we build efficient and accurate surrogate approximations to maps from input parameters to output quantities of interest (QoIs).<br><br>This study focuses on building neural network surrogates for climate land models. Due to the temporal nature of the model, we construct the surrogate with a recurrent neural network (RNN) architecture with long-short term memory (LSTM) units. We then augment the architecture with a hierarchical structure of the relationships between the various inputs, state variables, and QoIs. The resulting hierarchical LSTM RNN mimics the physical constraints and relationships between the underlying processes and provides a natural structure for temporal evolution. Using the hierarchical LSTM surrogate, we then perform global sensitivity analysis to identify the most influential input parameters for dimensionality reduction and Bayesian model calibration when observational data is provided."
date: "2020-08-05"
publishDate: "2020-08-05"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2020_08_jsm.pdf"
loc: "$WW/projects/OSCM/repos/cluq/doc/talk/jsm20"
---
