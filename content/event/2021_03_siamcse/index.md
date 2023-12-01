---
title: Dimensionality Reduction and Physics-Informed Neural Networks for Climate Land Models
authors: ["Khachik Sargsyan, Cosmin Safta, Vishagan Ratnaswamy, Daniel M. Ricciuto"]

event: SIAM CSE 21
event_url: https://www.siam.org/conferences/cm/conference/cse21
location: virtual


summary: Talk
abstract: "Complex physical models are computationally expensive, challenging ensemble-intensive studies such as parameter estimation, uncertainty quantification, and optimal experimental design. In order to make such studies tractable, we build efficient and accurate surrogate approximations to maps from input parameters to output quantities of interest (QoIs). The primary model of interest is the land component of the Energy Exascale Earth System Model (E3SM).<br><br>For E3SM, the critical challenge is to create high-fidelity spatio-temporal surrogates with as few model training evaluations as possible. We rely on Karhunen-Loeve expansions to account for spatial correlations of model outputs, while the temporal evolution is best approximated with long-short term memory (LSTM) recurrent neural network. Besides, considering the already known interactions between input processes and output quantities of interest (QoIs), we develop a special LSTM architecture with predefined connections between these QoIs. Such physics-informed architecture with reduced spatial dimensionality is shown to outperform, both in accuracy and efficiency, vanilla LSTM implementations and cell-based independent surrogates. We then employ the resulting spatio-temporal surrogate to extract parameter sensitivity indices, as well as to perform model calibration given global observational data on select QoIs.<br>"
date: "2021-03-04"
publishDate: "2021-03-04"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2021_03_siamcse.pdf"
loc: "$WW/projects/OSCM/repos/cluq/doc/talk/siamcse21"
---
