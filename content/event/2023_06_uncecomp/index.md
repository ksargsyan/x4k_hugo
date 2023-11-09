---
title: Quantifying Uncertainties in Residual Neural Networks and Neural ODEs
authors: ["Khachik Sargsyan, Joshua Hudson, Oscar Diaz-Ibarra, Marta D’Elia, Habib N. Najm"]

event: 5th International Conference on Uncertainty Quantification in Computational Science and Engineering
event_url: https://2023.uncecomp.org/
location: Greece, Athens

summary: Talk
abstract: "<br>Neural network (NN) successes have permeated scientific problems, thereby helping computational model development and analysis tremendously. In particular, NNs have been employed as surrogates to replicate input-output maps in complex physical models, accelerating sample-intensive studies such as model calibration and sensitivity analysis. However, in most instances trained NNs are treated as deterministic. They typically do not come with an estimation of uncertainties that may be abundant due to the quality and amount of data, or due to the surrogate approximation itself.<br><br>In the context of uncertainty estimation, Bayesian methods provide an ideal path to infer NN weights while incorporating various sources of uncertainty in a consistent fashion. However, the strongly non-linear nature of NN models, the typically large number of deep NN weights, the lack of meaningful priors, as well as weight symmetries and invariance relations, all render exact Bayesian posterior distributions extremely difficult to compute or sample from. Variational approaches, as well as ensembling methods, provide viable alternatives accepting various degrees of approximation and empiricism.<br><br>This work focuses on special NN architectures, Residual NNs (ResNets) and their continuous counterparts, Neural ODEs (NODEs). ResNets feature extra connections between layers enabling incremental learning between layers. Their infinite-layer limit, NODEs can stand on the shoulders of the mature field of differential equations, opening doors for better training algorithms and improved generalization performance. Inspired by the continuous, NODE analogy, we will examine ResNet weight matrix parameterization as a function of depth. The choice of parameterization affects the capacity of the network, leading to regularization and a subsequent reduction of the generalization gap. More importantly, weight-parameterized ResNets as well as NODEs become more amenable to Bayesian treatment due to the reduction of the number of parameters and overall regularization of the loss, or log-posterior, surface.<br><br>We will demonstrate the performance of various Bayesian NN learning methods, including MCMC sampling, variational approximations and ensembling methods. We will highlight the improvements in training and generalization gained by using weight-parameterized ResNet and NODE architectures. Besides synthetic benchmark problems common in machine learning, we will illustrate the methods on various applications ranging from climate modeling to materials science.<br>"
date: "2023-06-12"
publishDate: "2023-06-12"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2023_06_uncecomp.pdf"
loc: "$WW/projects/NNRDS/repos/nn_rds/doc/uncecomp_2023"
---
