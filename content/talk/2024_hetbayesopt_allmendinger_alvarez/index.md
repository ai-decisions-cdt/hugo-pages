---
title: "Heterogenous Bayesian Optimization"
author: ["Richard Allmendinger"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["richardallmendinger","mauricioalvarez"]
summary: "This is a collaborative project with Honda Research Institute (HRI), who are interested in efficient and sustainable vehicle design. A typical challenge here is performing costly simulations (eg through CFD), potentially combined with resource-intense physical experiments in the laboratory, resulting in optimization problems with heterogeneous objectives and/or constraints. We will develop novel Bayesian methods for heterogeneous objectives, and validate them on real problems provided by HRI."
---

This is a collaborative project with Honda Research Institute (HRI) Europe https://www.honda-ri.de/, the research arm of Honda, one of the world's largest and well-known automotive companies. Efficient and sustainable vehicle design is one of HRI’s focus areas. A typical challenge here is performing costly simulations (eg through CFD), potentially combined with resource-intense physical experiments in the laboratory, resulting in optimization problems with heterogeneous objectives and/or constraints [1]. Heterogeneous objectives/constraints may differ eg in practical evaluation effort (time, costs, resources, etc), formal computational complexity, determinism (stochastic vs deterministic), or some combination of all these. A particularly challenging variety of heterogeneity may occur by the combination of a time-consuming laboratory-based objective/constraint with other objectives/constraints that are evaluated using faster computer-based calculations [2,3].

Current research on heterogeneous objectives is largely focused on problems with two objectives (typically one slow vs one fast to evaluate objective) [1]. Research on heterogeneous constraints is even more so in its infancy. Also, most existing research has only considered heterogeneity in terms of computational time of objectives/constraints.

In this PhD project, we propose to generalize recent advances in machine learning and operations search [1,4] to tackle optimization problems with heterogeneous objectives/constraint. Hybrid methods will be developed and validated on real problems provided by HRI. Furthermore, realistic synthetic benchmark problems will be proposed varying in type and level of heterogeneity. The outcome of this research will allow tackling heterogenous optimization problems more efficiently while using less resources.

***References***

[1] Allmendinger, R., Handl, J. and Knowles, J., 2015. Multiobjective optimization: When objectives exhibit non-uniform latencies. European Journal of Operational Research, 243(2), pp.497-513.

[2] Allmendinger, R. and Knowles, J., 2023. Heterogeneous objectives: state-of-the-art and future research. In Many-Criteria Optimization and Decision Analysis: State-of-the-Art, Present Challenges, and Future Perspectives (pp. 317-335). Cham: Springer International Publishing.

[3] Blank, J. and Deb, K., 2022. Handling constrained multi-objective optimization problems with heterogeneous evaluation times: proof-of-principle results. Memetic Computing, 14(2), pp.135-150.

[4] Moreno-Muñoz, P., Artés, A. and Alvarez, M., 2018. Heterogeneous multi-output Gaussian process prediction. Advances in neural information processing systems, 31.

## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/heterogenous-bayesian-optimization/?d1022p156384)
