---
title: "The Role of Stiffness in Training and Generalization of ResNets"
date: 2023-01-01
publishDate: 2024-01-14T19:27:19.576035Z
authors: ["Joshua Hudson", "Marta D'Elia", "Habib N. Najm", "Khachik Sargsyan"]
publication_types: ["2"]
abstract: "Neural ordinary differential equations (NODEs) have recently regained popularity as large-depth limits of a large class of neural networks. In particular, residual neural networks (ResNets) are equivalent to an explicit Euler discretization of an underlying NODE, where the transition from one layer to the next is one time step of the discretization. The relationship between continuous and discrete neural networks has been of particular interest. Notably, analysis from the ordinary differential equation viewpoint can potentially lead to new insights for understanding the behavior of neural networks in general. In this work, we take inspiration from differential equations to define the concept of stiffness for a ResNet via the interpretation of a ResNet as the discretization of a NODE. We then examine the effects of stiffness on the ability of a ResNet to generalize, via computational studies on example problems coming from climate and chemistry models. We find that penalizing stiffness does have a unique regularizing effect, but we see no benefit to penalizing stiffness over L2 regularization (penalization of network parameter norms) in terms of predictive performance."
featured: false
publication: "*Journal of Machine Learning for Modeling and Computing*"
doi: "10.1615/JMachLearnModelComput.2023047131"
---

