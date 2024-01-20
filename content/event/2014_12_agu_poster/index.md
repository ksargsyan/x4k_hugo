---
title: Parameter Estimation in High-Dimensional Climate Models
authors: ["Khachik Sargsyan, Cosmin Safta, Bert Debusschere, Habib Najm, Dan Ricciuto, Peter Thornton"]
event: AGU Fall Meeting 2014
event_url: https://agu.confex.com/agu/fm14
location: San Francisco, CA
summary: Poster
abstract: "We highlight and address important challenges with parameter estimation in climate models. We focus on challenges with the estimation of input parameters with quantified uncertainties, specifically for the Community Land Model (CLM).<br>The CLM is moderately expensive from a computational perspective, rendering Monte-Carlo approaches of exploring the input parameter space prohibitive. Instead, we build inexpensive surrogates using uncertainty quantification (UQ) methods employing Polynomial Chaos (PC) expansions that approximate the input-output relationships using as few model evaluations as possible.<br>Further, climate models, generally include many uncertain input parameters and therefore UQ studies suffer from the curse of dimensionality. In particular, our implementation of the CLM includes about 70 parameters, calling for adaptive construction of PC basis terms. To this end, we employ Bayesian Compressive Sensing to learn the most important input parameter relationships for efficient, sparse PC surrogate construction.<br>Having constructed computationally inexpensive surrogates, one can proceed to build time- and space- resolved representations for CLM outputs of interest. The surrogates are employed for forward uncertainty propagation and variance-based sensitivity analysis, as well as to greatly accelerate statistical methods for parameter estimation, where one relies on observational data to estimate input parameters with quantified uncertainty, using Markov Chain Monte Carlo sampling.<br>"
date: "2014-12-15"
publishDate: "2014-12-15"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2014_12_agu_poster.pdf"
loc: "$WW/repos/talk_dist/agu14/clm"
---
