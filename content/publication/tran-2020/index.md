---
title: "A Novel Modeling Framework to Secure Efficiency and Accuracy in Real-Time Ensemble Flood Forecasting"
date: 2020-02-01
publishDate: 2024-03-06T22:52:41.191528Z
authors: ["Vinh Ngoc Tran", "M. Chase Dwelle", "Khachik Sargsyan", "Valeriy Ivanov", "Kim Jongho"]
publication_types: ["2"]
abstract: "A novel modeling framework that simultaneously improves accuracy, predictability, and computational efficiency is presented. It embraces the benefits of three modeling techniques integrated together for the first time: surrogate modeling, parameter inference, and data assimilation. The use of polynomial chaos expansion (PCE) surrogates significantly decreases computational time. Parameter inference allows for model faster convergence, reduced uncertainty, and superior accuracy of simulated results. Ensemble Kalman filters (EnKFs) assimilate errors that occur during forecasting. To examine the applicability and effectiveness of the integrated framework, we developed 18 approaches according to how surrogate models are constructed, what type of parameter distributions are used as model inputs, and whether model parameters are updated during the data assimilation procedure. We conclude that (1) PCE must be built over various forcing and flow conditions and, in contrast to previous studies, it does not need to be rebuilt at each time step; (2) model parameter specification that relies on constrained, posterior information of parameters (so-called Selected specification) can significantly improve forecasting performance and reduce uncertainty bounds compared to Random specification using prior information of parameters; and (3) no substantial differences in results exist between single and dual EnKFs, but the latter better simulates flood peaks. The use of PCE effectively compensates for the computational load added by the parameter inference and data assimilation (up to ~80 times faster). Therefore, the presented approach contributes to a shift in modeling paradigm arguing that complex, high-fidelity hydrologic and hydraulic models should be increasingly adopted for real-time and ensemble flood forecasting."
featured: false
publication: "*Water Resources Research*"
doi: "10.1029/2019WR025727"
---

