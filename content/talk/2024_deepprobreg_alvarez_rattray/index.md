---
title: "Using deep probabilistic machine learning to understand cellular decision-making"
author: ["Mauricio Alvarez"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["mauricioalvarez","magnusrattray"]
summary: "A critical question in developmental biology is how cells know when to differentiate into a new cell type. Recent advances in spatial transcriptomics provide an unprecedented increase in the spatial resolution of high-throughput gene expression measurements. In the proposed project, the student will develop machine learning methods for learning spatio-temporal dynamical models from such data to uncover the rules guiding cells to differentiate into new cell types over time."
---

Developmental biology is concerned with understanding how a complex organism is formed starting from a single fertilized egg. Fundamental concepts from developmental biology are important for understanding many areas of biology and medicine; for example, developmental biology can provide us with a better understanding of genetic disorders, stem cell therapies, synthetic organoids or cancer biology. The key question in all of these systems is how do cells know when to differentiate into a new cell-type? Recent advances in spatial transcriptomics provide an unprecedented increase in the spatial resolution of high-throughput gene expression measurements [1]. In the proposed project the student will develop machine learning methods for learning spatio-temporal dynamical models from such data, in order to uncover the rules guiding cells to differentiate into new cell-types over time. The student will have access to high-resolution spatial transcriptomics data collected from a time course of embryonic development in Drosophila, a model organism that has been incredibly useful in characterising the function of many important developmental genes. The data will have single-cell resolution across the entire embryo, quantifying the expression of hundreds of key regulatory genes within each cell. This unique data resource will be used to infer gene regulatory network models capturing how genes regulate one another to orchestrate early development of a complex organism. 

Rattray, the co-supervisor in the project, recently used differential equation models coupled with Gaussian process inference in this biological system [2]. By fitting these models to time course gene expression data from RNA-Seq experiments (without spatial resolution) they were able to learn about mRNA degradation rates and provide insights into the regulation of the degradation process. The new experimental data will have single cell spatial resolution, potentially enabling the fitting of spatial partial differential equation (PDE) models describing the spatio-temporal changes in gene expression. One promising approach to learning PDE models from data are Latent Force Models [3,4] which have already been applied to lower dimensional embryonic development data and models. Another promising approach to modelling cellular dynamics is based on concepts such as pseudotime and RNA velocity, typically applied to non-spatial single-cell data. Our collaborator, Guido Sanguinetti, recently supervised the development of NeuroVelo, an interpretable model of cellular dynamics that uses a neural ODE approach [5]. During the project the student will have the opportunity to visit the Sanguinetti lab to explore similar methods that can be applied to spatially resolved time course data. 

In the proposed project the student will investigate and adapt machine learning approaches to fitting spatio-temporal models of gene regulation to data obtained from high-dimensional spatial time course data. These models will help us to better understand the mechanisms underlying cellular decision making in complex organisms. The learned models will then be used to design environmental and genetic perturbation experiments, carried out by our collaborators, to test hypotheses about developmental decision making and robustness. 

***References***

[1] Marx, V. (2021). Method of the Year: spatially resolved transcriptomics. Nature methods, 18(1), 9-14.

[2] Forbes Beadle, L., Love, J. C., Shapovalova, Y., Artemev, A., Rattray, M., & Ashe, H. L. (2023). Combined modelling of mRNA decay dynamics and single-molecule imaging in the Drosophila embryo uncovers a role for P-bodies in 5′ to 3′ degradation. PLoS Biology, 21(1), e3001956.

[3] Alvarez, M. A., Luengo, D., & Lawrence, N. D. (2013). Linear latent force models using Gaussian processes. IEEE transactions on pattern analysis and machine intelligence, 35(11), 2693-2705.

[4] Croix, J. C., Durrande, N., & Alvarez, M. A. (2021). Bayesian inversion of a diffusion model with application to biology. Journal of Mathematical Biology, 83, 1-23.

[5] Kouadri Boudjelthia, I., Milite, S., El Kazwini, N., Fernandez-Mateos, J., Valeri, N., Huang, Y., ... & Sanguinetti, G. (2023). NeuroVelo: interpretable learning of cellular dynamics from single-cell transcriptomic data. bioRxiv, 2023-11.

## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/using-deep-probabilistic-machine-learning-to-understand-cellular-decision-making/?p168685)
