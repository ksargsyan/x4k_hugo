---
title: Surrogate Models for Parameterized Stochastic Systems
summary: " "
tags:
- UQ
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

Uncertainty quantification (UQ) of complex physical models often relies on creation of surrogate models that mimic the input-output relationships. These surrogates replace the model in sample-intensive UQ studies such as global sensitivity analysis and model calibration. Polynomial chaos (PC) expansions serve as conventional tools for surrogate modeling through rigorous representation of associated uncertain variables [1]. 

However, most surrogate approaches assume the underlying model is deterministic. In this work, motivated by kinetic Monte Carlo (KMC) models for catalytic chemistry, we develop PC-based surrogates to capture stochastic systems that have intrinsic noise associated with each model evaluation.  The method relies on kernel density estimation of the associated Rosenblatt transformation [2]. We also generalized this surrogate construction to capture spatio-temporal stochastic fields, such as coverage fractions of species on a catalytic surface. Specifically, we employ Karhunen-Loève expansions to reduce the dimensionality of the associated stochastic fields, followed by a PC surrogate construction in the latent eigen-space. 

Furthermore, we leverage closed-form solutions for computing PC-based sensitivity indices, thereby quantifying the contribution of intrinsic noise to the overall variance of the model output. The resulting joint PC demonstrates generative capabilities, allowing for the generation of random realizations at any input parameter configuration that statistically approximate realizations from the underlying stochastic model [3, 4].


<br> <b>Figure </b></br>
Demonstration of parametric-stochastic PC surrogate for a bimodal test model. Courtesy of Dr. Joy Bahr-Mueller.

<br> <b>Acknowledgements </b></br>
The work is supported by DOE Basic Energy Sciences program under the <a href="https://www.ecc-project.org/">Exascale Catalytic Chemistry project</a>.

<br> <b>References </b></br>
[1] H. N. Najm, “Uncertainty Quantification and Polynomial Chaos Techniques in Computational Fluid Dynamics”, Annual Review of Fluid Mechanics, 41:35-52, 2009.

[2] K. Sargsyan, B. Debusschere, H. N. Najm and O. Le Maitre, “Spectral Representation and Reduced Order Modeling of the Dynamics of Stochastic Reaction Networks via Adaptive Data Partitioning”. SIAM Journal on Scientific Computing, 31, pp.4395-4421, 2010.

[3] J. Mueller, K. Sargsyan, H. N. Najm, ”Polynomial Chaos Surrogate Construction for Stochastic Models with Parametric Uncertainty”, 14th International Conference on Applications of Statistics and Probability in Civil Engineering (ICASP14), Dublin, Ireland, 2023.

[4] J. Mueller, K. Sargsyan, C. Daniels, H. N. Najm, “Polynomial Chaos Surrogate Construction for Random Fields with Parametric Uncertainty”, SIAM/ASA Journal of Uncertainty Quantification, <a href="https://arxiv.org/abs/2311.00553">in press</a>, 2024.



