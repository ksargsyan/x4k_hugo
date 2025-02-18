---
title: Embedded Framework for Model Error Quantification and Propagation
authors: ["Khachik Sargsyan"]
event: Second USACM Thematic Conference on Uncertainty Quantification for Machine Learning Integrated Physics Modeling (UQ-MLIP 2024)
event_url: https://uq-mlip2.usacm.org/
location: Arlington, VA
summary: Talk
abstract: "Model error estimation remains one of the key challenges in uncertainty quantification and
predictive science. While accounting for data noise and parametric uncertainties has become routine
in the uncertainty quantification context, the same cannot be said about model errors, also known as
model structural error, model inadequacy, or model misspecification. In fact, for computational
models of complex physical systems, model error is often the largest contributor to the overall
predictive uncertainty. Nevertheless, model calibration often ignores model errors by assuming that
the computational model replicates the exact physics behind data generation. As a result, calibrated
model parameters are often biased, leading to reduced predictive skill. Conventional external
methods [1] of augmenting model outputs with statistical correction terms may remove the
predictive bias, but they can violate physical laws, make the calibrated model ineffective for
predicting non-observable quantities, and experience identifiability challenges in distinguishing
between data noise and model error.
This work will present a Bayesian framework for representing, quantifying, and propagating
uncertainties due to model structural errors by embedding statistical representations in the model
instead of external corrections [2]. The physical inputs and correction parameters are then
simultaneously inferred within a Bayesian paradigm via surrogate-enabled Markov chain Monte
Carlo sampling. With a polynomial chaos characterization of the correction term, the approach
allows for efficient propagation and decomposition of uncertainty that includes contributions from
data noise, parameter posterior uncertainty, and model error. The embedded approach ensures
physical constraints are satisfied and renders calibrated model predictions meaningful with respect
to structural errors over multiple, even unobservable, quantities of interest.
Further, we will recast the methodology and draw parallels to model uncertainty quantification for
neural networks, specifically methods employing approximate Bayesian computation and functional
variational inference. Throughout the talk, key strengths and challenges of the embedded model
error quantification method will be demonstrated on synthetic examples and practical applications
ranging from chemical modeling to climate science.

<br> 
[1] Kennedy, M.C. and O’Hagan, A., “Bayesian calibration of computer models”. Journal of the
Royal Statistical Society: Series B (Statistical Methodology), 63: 425-464. 2001.
<br>
[2] K. Sargsyan, X. Huan, H. N. Najm. “Embedded Model Error Representation for Bayesian Model
Calibration”, International Journal of Uncertainty Quantification, 9:4, pp. 365–394, 2019.<br>"
date: "2024-08-14"
publishDate: "2024-08-14"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2024_08_uqmlip.pdf"
loc: "$WW/repos/merr_dist/doc/uq_mlip24"
---
