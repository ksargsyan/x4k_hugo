---
title: "Improving the Quasi-Biennial Oscillation via a Surrogate-Accelerated Multi-Objective Optimization"
date: 2025-01-01
publishDate: 2025-12-25T08:28:15.205755Z
authors: ["Luis Damiano", "Walter Hannah", "Chih-Chieh Chen", "James J. Benedict", "Khachik Sargsyan", "Bert J. Debusschere", "Michael S. Eldred"]
publication_types: ["2"]
abstract: "Abstract Accurate simulation of the quasi-biennial oscillation (QBO) is challenging due to uncertainties in representing convectively generated gravity waves. We develop an end-to-end uncertainty quantification workflow that calibrates these gravity wave processes in E3SM for a realistic QBO. Central to our approach is a domain knowledge-informed, compressed representation of high-dimensional spatio-temporal wind fields. By employing a parsimonious statistical model that learns the fundamental frequency from complex observations, we extract interpretable and physically meaningful quantities capturing key attributes. Building on this, we train a probabilistic surrogate model that approximates the fundamental characteristics of the QBO as functions of critical physics parameters governing gravity wave generation. Leveraging the Karhunen–Loève decomposition, our surrogate efficiently represents these characteristics as a set of orthogonal features, capturing cross-correlations among multiple physics quantities evaluated at different pressure levels and enabling rapid surrogate-based inference at a fraction of the computational cost of full-scale simulations. Finally, we analyze the inverse problem using a multi-objective approach. Our study reveals a tension between amplitude and period that constrains the QBO representation, precluding a single optimal solution. To navigate this, we quantify the bi-criteria trade-off and generate a set of Pareto optimal parameter values that balance the conflicting objectives. This integrated workflow improves the fidelity of QBO simulations and offers a versatile template for uncertainty quantification in complex geophysical models."
featured: false
publication: "*Journal of Advances in Modeling Earth Systems*"
tags: ["quasi-biennial oscillation", "model calibration", "fundamental frequency model", "dimension reduction", "probabilistic surrogate", "pareto frontier"]
doi: "https://doi.org/10.1029/2025MS005057"
---

