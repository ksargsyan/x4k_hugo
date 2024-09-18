---
title: Uncertainty Propagation and Calibration in E3SM Land Model
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
  focal_point: Smart # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
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

In collaboration with climate modelers from several national laboratories, we develop both forward and inverse UQ methods for the land component of the DOE flagship climate model, <a href="https://e3sm.org">Energy Exascale Earth System Model (E3SM)<a>. The E3SM Land Model (ELM) captures a wide range of processes, including photosynthesis and biogeochemistry, and is associated with a large number of input parameters, making the application of conventional UQ methods challenging. 

We have developed and deployed weighted iterative Bayesian compressive sensing (BCS) algorithm, allowing polynomial chaos surrogate construction in cases with large number of input parameters [1, 2]. Besides the surrogate uncertainty estimate, BCS-enabled PC is also used for extract analytically available sensitivity indices. Further, we generalize the approach to spatio-temporal model outputs by initially reducing the dimensionality of the output by Karhunen-Loève (KL) expansions, followed by building surrogates in the latent eigen-space discovered by KL representation [3]. For more details, see <a href="https://www.youtube.com/watch?v=iS8ee--ZEzM">this presentation<a>.

<br> <b>Figure </b></br>
Illustration of surrogate-enabled calibration of ELM: from left to right, 
(a) ELM nominal before the calibration,  (b) after the calibration, (c) reference data.

<br> <b>Acknowledgements </b></br>
This work is supported by DOE Office of Science BER program.

<br> <b>References </b></br>
[1] K. Sargsyan, C. Safta, H. N. Najm, B. Debusschere, D. Ricciuto, P. Thornton, “Dimensionality Reduction for Complex Models via Bayesian Compressive Sensing”, International Journal of Uncertainty Quantification, 4:1, pp.63–93, 2014.

[2] D. Ricciuto, K. Sargsyan, P. Thornton, “The Impact of Parametric Uncertainties on Biogeochemistry in the E3SM Land Model”, Journal of Advances in Modeling Earth Systems, 10:2, pp.297–319, 2018.

[3] K. Sargsyan, N. Iyengar, D. Ricciuto, “Spatio-temporal surrogate construction and calibration of E3SM land model”, in prep., 2024.




