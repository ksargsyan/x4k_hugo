---
title: "The Network Uncertainty Quantification Method for Uncertainty Propagation in Large-Scale Networks"
date: 2020-01-01
publishDate: 2024-07-17T17:20:03.470438Z
authors: ["Kevin Carlberg", "Sofia Guzzetti", "Mohammad Khalil", "Khachik Sargsyan"]
publication_types: ["2"]
abstract: "This work introduces the network uncertainty quantification (NetUQ) method for performing uncertainty propagation in systems composed of interconnected components. The method assumes the existence of a collection of components, each of which is characterized by exogenous-input random variables, endogenous-input random variables, output random variables, and a local uncertainty-propagation operator that computes output random variables from input random variables. The method assembles the full-system network by connecting components, which is achieved simply by associating endogenous-input random variables for each component with output random variables from other components; no other inter-component compatibility conditions are required. The network uncertainty-propagation problem is: Compute output random variables for all components given all exogenous-input random variables. To solve this problem, the method applies classical relaxation methods (i.e., Jacobi and Gauss--Seidel iteration with Anderson acceleration), which require only black-box evaluations of component uncertainty-propagation operators. Compared with other available methods, this approach is applicable to any network topology, promotes component independence by enabling components to employ tailored uncertainty-propagation operators, supports general functional representations of random variables, and requires no offline preprocessing stage. Also, because the method propagates functional representations of random variables throughout the network (and not, e.g., probability density functions), the joint distribution of any set of random variables throughout the network can be estimated a posteriori in a straightforward manner. We perform supporting convergence and error analysis and execute numerical experiments that demonstrate the weak- and strong-scaling performance of the method."
featured: false
publication: "*Unpublished*"
url_pdf: "https://arxiv.org/abs/1908.11476"
doi: "https://doi.org/10.48550/arXiv.1908.11476"
---

