---
title: Weight-parameterized Residual Neural Networks
summary: " "
tags:
- ML
date: "2024-09-01T00:00:00Z"
show_date: false

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  placement: 1
  caption: 
  focal_point: Smart
  alt_text:

profile: false

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: ""
---

We focus on special NN architectures, residual NNs (ResNets) which include shortcut connections, in the context of NN-based regression for scientific ML. Inspired by the continuous, neural ODE analogy, we develop an approach for ResNet weight matrix parameterization as a function of depth. The choice of parameterization affects the capacity of the network, leading to regularization and improved generalization compared to standard multilayer perceptron (MLP) NNs [1]. 

Besides, weight-parameterized (WP) ResNets become more amenable to Bayesian treatment due to the reduction of the number of parameters and overall regularization of the loss, or log-posterior, surface. WP ResNets are implemented in have developed a software library <a href="https://github.com/sandialabs/quinn">Quantification of Uncertainties in NNs (QUiNN)</a> that consists of  probabilistic wrappers around PyTorch NN modules.


<br> <b>Figure </b></br>
Implemented and planned methods in QUiNN. 

<br> <b>Acknowledgements </b></br>
This work is supported by SNL LDRD program.

<br> <b>References </b></br>
[1] O.H. Diaz-Ibarra, K. Sargsyan, H.N. Najm, “Surrogate Construction via Weight Parameterization of Residual Neural Networks”, submitted to Computer Methods in Applied Mechanics and Engineering, 2024.



