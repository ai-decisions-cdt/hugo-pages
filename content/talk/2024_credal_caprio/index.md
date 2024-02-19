---
title: "Relationship Between Conformal Prediction and Credal Probabilistic Machine Learning"
author: ["Michele Caprio"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["michelecaprio"]
summary: "You will conduct research at the frontier of probabilistic machine learning leveraging uncertainty in the form of credal sets. You will inspect the relationship existing between these latter and a model-free approach like conformal prediction, to ultimately discover (i) in which context one approach is to prefer to the other, and (ii) whether properties of one of the two methodologies can be used to improve on the other."
---

The probabilistic tools typically used in machine learning can suffer from shortcomings. For example, the uniform distribution is not able to distinguish between indifference and ignorance [1]: are we using equal weights because we know that outcomes are all equally probable, or because we are ignorant about which are the more likely to obtain? We can overcome this drawback, known as the Laplace’s paradox, by using credal sets, that is, closed and convex sets of probabilities [2]. Credal sets are also instrumental for representing aleatoric and epistemic uncertainties (AU and EU, resp.), two quantities that are of great importance in ML and AI [3]. The former refers to irreducible uncertainty, so in the presence of an excess of AU, the model should abstain from producing a result and query for human help. EU instead is reducible, and can be lessened on the basis of additional data. The field of probabilistic machine learning encompassing both theoretical and methodological research around credal sets is called Credal Probabilistic Machine Learning (CPML).

Conformal Prediction [4] is a very popular distribution-free uncertainty quantification technique which provides prediction regions equipped with (user-defined) statistical guarantees. CPML techniques, instead, are model-based. The goal of this project is to explore the relationship existing between CMPL and Conformal Prediction, an effort framed in the general endeavor of comparing model-free and model-based approaches, an undertaking as old as statistics itself, and yet still an ongoing one. Is the modeling effort required for CPML rewarded with a prediction region that is narrower than the conformal one, while enjoying the same guarantees? Studying this connection is also important because, while measures for AU and EU for credal sets are well-studied in the literature, there is still no way of disentangling between AU and EU in the conformal framework. Connecting credal sets to conformal regions will bridge this knowledge gap.

First steps on the path of relating CPML and Conformal Prediction were made in [5,8]. In [5], the authors showed that – in the case of “vanilla” full conformal prediction, based on the exchangeability assumption – credal regions are wider than conformal regions when the designer faces high uncertainty, while they are narrower when the uncertainty faced is low. Hence, depending on the degree of ambiguity, the designer chooses either of the two techniques. They also proved that, in a classification problem, for a particular choice of the non-conformity score, it is possible to derive a credal set that induces a prediction region that is narrower than the conformal one, while retaining the same probabilistic guarantee, regardless of the amount of uncertainty faced by the agent. In [8], the authors showed that, in the case of ambiguous ground truth in split conformal prediction, the plausibility regions derived in [9] are credal sets, and that more efficient prediction regions (narrower than the conformal ones) can be derived from such credal sets.

In this project, you will further the initial exploration in [5,8] to more general notions of conformal prediction [6,7]. In addition, you will study whether the results concerning classification can be generalized to a regression setting, and to a wider selection of non-conformity scores. Finally, you will study in detail the empirical implications of your results.

Introductory slides to the field of Credal/Imprecise Machine Learning, and its relationship with Conformal Prediction, can be found [here](https://www.dropbox.com/scl/fi/vys2dne8k2o4mjj5orjzv/IPML_Lecture.pdf?rlkey=dced6oeju6691qfuirvecnxou&dl=0).


***References***

[1] Introduction to Imprecise Probabilities; Augustin, Coolen, de Cooman, Troffaes; https://onlinelibrary.wiley.com/doi/book/10.1002/9781118763117 

[2] Statistical Reasoning with Imprecise Probabilities; Walley; https://philpapers.org/rec/WALSRW 

[3] Aleatoric and Epistemic Uncertainty in Machine Learning: an Introduction to Concepts and Methods; Hüllermeier, Waegeman; https://link.springer.com/article/10.1007/s10994-021-05946-3 

[4] A Tutorial on Conformal Prediction; Shafer and Vovk; https://jmlr.csail.mit.edu/papers/volume9/shafer08a/shafer08a.pdf 

[5] Relationship between Conformal Prediction and Imprecise Probabilities; Caprio, Sale, Lee, Hüllermeier; Available upon request 

[6] Conformal Prediction Beyond Exchangeability; Barber, Candès, Ramdas, Tibshirani; https://arxiv.org/pdf/2202.13415.pdf

[7] Conformal Prediction with Conditional Guarantees; Gibbs, Cherian, Candès; https://arxiv.org/pdf/2305.12616.pdf

[8] Plausibility Regions are Credal Sets; Caprio and Stutz; Available upon request

[9] Conformal Prediction under Ambiguous Ground Truth; Stutz, Roy, Matejovicova, Strachan, Cemgil, Doucet; https://arxiv.org/pdf/2307.09302v1.pdf


**More details in** [**Find A PhD**](https://www.findaphd.com/phds/project/relationship-between-conformal-prediction-and-credal-probabilistic-machine-learning/?p168861)
