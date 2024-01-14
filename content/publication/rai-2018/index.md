---
title: "Compressed sparse tensor based quadrature for vibrational quantum mechanics integrals"
date: 2018-07-01
publishDate: 2024-01-14T17:37:25.158420Z
authors: ["P. Rai", "K. Sargsyan", "H. Najm"]
publication_types: ["2"]
abstract: "A new method for fast evaluation of high dimensional integrals arising in quantum mechanics is proposed. The method is based on sparse approximation of a high dimensional function followed by a low-rank compression. In the first step, we interpret the high dimensional integrand as a tensor in a suitable tensor product space and determine its entries by a compressed sensing based algorithm using only a few function evaluations. Secondly, we implement a rank reduction strategy to compress this tensor in a suitable low-rank tensor format using standard tensor compression tools. This allows representing a high dimensional integrand function as a small sum of products of low dimensional functions. Finally, a low dimensional Gauss–Hermite quadrature rule is used to integrate this low-rank representation, thus alleviating the curse of dimensionality. Numerical tests on synthetic functions, as well as on energy correction integrals for water and formaldehyde molecules demonstrate the efficiency of this method using very few function evaluations as compared to other integration strategies."
featured: false
publication: "*Computer Methods in Applied Mechanics and Engineering*"
doi: "10.1016/j.cma.2018.02.026"
---

