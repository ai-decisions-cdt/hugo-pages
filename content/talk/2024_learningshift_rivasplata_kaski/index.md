---
title: "Learning theory and methods for novel types of distributional shifts"
author: ["Omar Rivasplata"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["omarrivasplata","samuelkaski"]
summary: "In this project, the goal is to develop methods for tackling novel types of distributional shifts by combining development of the necessary new theory with development of methods and applying them to real cases with collaborators. The project can be tailored to focus more on theory or method development, depending on the interests of the student."
---

Distribution shift poses major challenges for developing reliable machine learning systems that might be robust to changing conditions, especially when unexpected changes happen. In this project, the goal is to develop methods for tackling novel types of distributional shifts by combining development of the necessary new theory with development of methods and applying them to real cases with collaborators. The project can be tailored to focus more on theory or method development, depending on the interests of the student. 

A starting question is the feasibility of using PAC-Bayes bounds for novel types of distributional shifts. These kinds of bounds have been used for learning robust majority vote rules in some binary classification problems with distribution shift, where the PAC-Bayes bounds guided a learning algorithm to find the weights for the weighted majority vote. The natural next steps then are to obtain PAC-Bayes bounds for multi-class problems and to derive corresponding learning strategies, with particular focus on exploring the capacity of the resulting models to distinguish structural differences between source and target samples.

Another interesting question asks to characterise properties of the likelihood that might induce robustness to distributional shifts or other perturbations. To answer this question, the project will study relaxations of the likelihood via implicit modelling where the likelihood isn't specified as such. In the absence of an explicit likelihood, some form of knowledge about it might be gained via upper bounds on functions of the likelihood. Specifically, a conjecture to study in this project is whether such bounds can be derived from the PAC-Bayesian analysis.

The situation is more complicated when distributional changes are unexpected and so it is no longer possible to specify a target distribution. A viable solution might be to design learning strategies such that the resulting prediction models are robust against the worst possible distribution from a given class of distributions. This is the idea behind distributionally robust optimisation (DRO) methods. The project will study the feasibility of applying DRO for tackling problems of unexpected distribution shift, and options to relax the potentially overly strict worst case bounds.

Applications: The project will have outstanding opportunities for demonstrating the developed new methods in applications with collaborators, from cancer research, engineering design, biological and drug and materials design, experimental design.

Deliverables of the project:
Publications in top-tier statistics and machine learning venues.
New learning methods which will be made publicly available via open-access.
Demonstrators and case study with collaborators in a real application.


***References***

Relevant literature:

A new PAC-Bayesian perspective on domain adaptation.
https://proceedings.mlr.press/v48/germain16.pdf

A closer look at distribution shifts and out-of-distribution generalization on graphs.
https://openreview.net/pdf?id=XvgPGWazqRH

On distributionally robust optimization and data rebalancing.
https://proceedings.mlr.press/v151/slowik22a/slowik22a.pdf

Mathematical foundations of robust and distributionally robust optimization.
https://www.researchgate.net/profile/Jianzhe-Zhen-2/publication/351298216_Mathematical_Foundations_of_Robust_and_Distributionally_Robust_Optimization/links/617fc4100be8ec17a95778a6/Mathematical-Foundations-of-Robust-and-Distributionally-Robust-Optimization.pdf

## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/learning-theory-and-methods-for-novel-types-of-distributional-shifts/?p168698)
