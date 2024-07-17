---
title: "Pynta-An Automated Workflow for Calculation of Surface and Gas–Surface Kinetics"
date: 2023-01-01
publishDate: 2024-07-17T17:20:03.461134Z
authors: ["Matthew Johnson", "Maciej Gierada", "Eric D. Hermes", "David H. Bross", "Khachik Sargsyan", "Habib N. Najm", "Judit Zádor"]
publication_types: ["2"]
abstract: " Many important industrial processes rely on heterogeneous catalytic systems. However, given all possible catalysts and conditions of interest, it is impractical to optimize most systems experimentally. Automatically generated microkinetic models can be used to efficiently consider many catalysts and conditions. However, these microkinetic models require accurate estimation of many thermochemical and kinetic parameters. Manually calculating these parameters is tedious and error prone, involving many interconnected computations. We present Pynta, a workflow software for automating the calculation of surface and gas–surface reactions. Pynta takes the reactants, products, and atom maps for the reactions of interest, generates sets of initial guesses for all species and saddle points, runs all optimizations, frequency, and IRC calculations, and computes the associated thermochemistry and rate coefficients. It is able to consider all unique adsorption configurations for both adsorbates and saddle points, allowing it to handle high index surfaces and bidentate species. Pynta implements a new saddle point guess generation method called harmonically forced saddle point searching (HFSP). HFSP defines harmonic potentials based on the optimized adsorbate geometries and which bonds are breaking and forming that allow initial placements to be optimized using the GFN1-xTB semiempirical method to create reliable saddle point guesses. This method is reaction class agnostic and fast, allowing Pynta to consider all possible adsorbate site placements efficiently. We demonstrate Pynta on 11 diverse reactions involving monodenate, bidentate, and gas-phase species, many distinct reaction classes, and both a low and a high index facet of Cu. Our results suggest that it is very important to consider reactions between adsorbates adsorbed in all unique configurations for interadsorbate group transfers and reactions on high index surfaces. "
featured: false
publication: "*Journal of Chemical Information and Modeling*"
doi: "10.1021/acs.jcim.3c00948"
---

