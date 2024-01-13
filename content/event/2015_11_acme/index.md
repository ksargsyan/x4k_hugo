---
title: Parametric Uncertainty Quantification Workflow for ALM
authors: ["Khachik Sargsyan, Daniel Ricciuto, Peter Thornton"]
event: 
event_url: 
location: 
summary: Poster
abstract: "The poster will present Uncertainty Quantification workflow that uses ensemble of ALM simulations at multiple sites to build surrogate approximations to input-output maps as well as to perform global variance-based uncertainty decomposition. A total of 96 FLUXNET sites were chosen for uncertainty analysis, in order to cover major biomes and plant functional types. An ensemble of 3,000 input parameter values was created using specified ranges for 68 parameters determined from a literature, and steady state values for five outputs of interest (GPP, TLAI, TOTVEGC, TOTSOMC, EFLX_LH_TOT) have been extracted. Uncertainty decomposition has been performed, based on global Polynomial Chaos (PC) surrogate construction, using Bayesian Compressive Sensing (BCS) sparse learning technique to select the most relevant polynomial bases. The results indicate some site-to-site variability, but overall coherence of sensitivities across sites covering different climates and PFTs.  The results also suggest that further ensemble studies would be more efficient if they are performed in a much reduced-dimensional parametric space, as only 10-15 parameters have strong enough impact on the outputs across all sites. As a generic UQ workflow, a set of Python scripts is being developed that performs the above uncertainty decomposition task automatically, with an interface to an external UQ toolkit (UQTk), which is a lightweight C++/Python library developed in SNL-CA.<br>"
date: "2015-11-05"
publishDate: "2015-11-05"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2015_11_acme.pdf"
loc: "$WW/projects/E3SM/repos/cm_dist/doc/acme_nov15"
---
