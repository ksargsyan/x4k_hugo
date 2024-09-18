---
title: Minima-Preserving Neural Networks for Potential Energy Approximation
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

Estimation of partition functions is the essential part of extracting thermodynamic properties of adsorbates on catalytic surfaces. However, the partition function involves integrals that require a large number of density functional theory (DFT) evaluations of potential energy surface (PES). For this reason, we construct neural network (NN) surrogates to approximate PES.  For accurate partition function integration these NN approximations need to be extremely accurate near the PES minima.  We developed minima-preserving NN (MPNN) specialized architecture for the construction of PES surrogates that render the corresponding partition function evaluations accurate and efficient. The routines for training and evaluation of MPNN are released as <a href="https://github.com/sandialabs/MPNN">open source</a>.

We have applied the method and demonstrated its strengths on several catalytic systems of interest [1, 2], and further enhanced the integration routine with truncated-gaussian mixture importance sampling approach [3]. 


<br> <b>Figure </b></br>
Periodic MPNN surrogate PES evaluated at z-slices of three distinct minima of  potential energy of CO on Pt(111) surface.

<br> <b>Acknowledgements </b></br>
The work is supported by DOE Basic Energy Sciences program under the <a href="https://www.ecc-project.org/">Exascale Catalytic Chemistry project</a>.

<br> <b>References </b></br>
[1] K. Blondal, K. Sargsyan, D. Bross, B. Ruscic, C. F. Goldsmith, “Adsorbate Partition Functions via Phase Space Integration: Quantifying the Effect of Translational Anharmonicity on Thermodynamic Properties”, Journal of Physical Chemistry C, 125:37, pp.20249–20260, 2021.

[2] K. Blondal, K. Sargsyan, D. H. Bross, B. Ruscic, C. F. Goldsmith, “Configuration Space Integration for Adsorbate Partition Functions: The Effect of Anharmonicity on the Thermophysical Properties of CO–Pt(111) and CH3OH–Cu(111)”, ACS Catalysis, 13:1, pp.19–32, 2023.

[3] K. Blondal, K. Badger, K. Sargsyan, D. H. Bross, B. Ruscic, C. F. Goldsmith, “Importance sampling within configuration space integration for adsorbate thermophysical properties: a case study for CH3/Ni(111)”, Physical Chemistry Chemical Physics, 26, p17265-17273, 2024.




