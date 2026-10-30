---
title: Fighting the Curse of Dimensionality in Uncertainty Quantification
authors: ["Khachik Sargsyan"]
event: ABOUND UQ Seminar
event_url: https://sc-programs.llnl.gov/fusion-energy-sciences-at-llnl/abound
location: virtual
summary: Talk
abstract: "Uncertainty quantification (UQ) of expensive computational models relies on surrogates, and surrogate construction becomes infeasible when the number of uncertain inputs or the number of model outputs is large. This talk will survey strategies that find and exploit low-dimensional structure in both settings. For high-dimensional inputs, the effective dimension is often low, and can be identified by screening with global sensitivity analysis, sparsifying with (Bayesian) compressive sensing over Polynomial Chaos (PC) bases, or rotating with active subspaces; such reduction also makes neural network and Gaussian process surrogates easier to train and interpret. For high-dimensional outputs, such as spatio-temporal fields, the Karhunen-Loeve (KL) expansion compresses the outputs into a handful of latent features, so that surrogates are built, and calibration is performed, in the latent space; combining KL with PC also gives analytical Sobol sensitivity indices at every spatial or temporal location. Both approaches are illustrated on the E3SM Land Model. The talk then turns to UQ for surrogates: with few model runs available, surrogate error can rival parametric uncertainty, and it needs to be accounted for in calibration likelihoods, active learning and experimental design, as well as in attributing predictive uncertainty to parametric, surrogate, data and model-error contributions. The talk closes with an overview of the PyTUQ and QUiNN software libraries."
date: "2026-10-30"
publishDate: "2026-10-30"
tags: ["surrogate-modeling", "dimensionality-reduction", "sensitivity-analysis", "compressive-sensing", "polynomial-chaos"]
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2026_10_abound.pdf"
loc: "$WW/mytalks/abound_2026"
---

