---
title: Quantification of Uncertainties in Neural Networks
summary: " "
tags:
- UQ
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

Neural network (NN) have recently been an extremely popular choice as surrogates to complex physical models. However,  in most instances trained NNs are treated deterministically. Probabilistic approaches to ML, particularly NNs, provide the necessary regularization of the typically overparameterized NNs while leading to predictions with uncertainty that are robust with respect to the amount and quality of input data. 

In the context of probabilistic estimation, Bayesian methods provide an ideal path to infer NN weights while incorporating various sources of uncertainty in a consistent fashion. However, exact Bayesian posterior distributions are extremely difficult to compute or sample from. Variational approaches, as well as ensembling methods, provide viable alternatives accepting various degrees of approximation and empiricism.

We have developed a software library 
<a href="https://github.com/sandialabs/quinn">Quantification of Uncertainties in NNs (QUiNN)</a> that consists of  probabilistic wrappers around 
PyTorch NN modules, to enable exploration of NN loss surfaces and the accuracy of several UQ-for-NN approaches, including Hamiltonian Monte-Carlo, Laplace approximation, variational approximations, ensemble methods.

<br> <b>Figure </b></br>
Implemented and planned methods in QUiNN. 

<br> <b>Acknowledgements </b></br>
This work has been supported by SNL LDRD program, as well as DOE Office of Science ASCR program.

<!-- <br> <b>References </b></br> -->




