---
title: "Explainability of deep learning models: the concept learning approach"
author: ["Mateja Jamnik"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["matejajamnik"]
summary: "Explainability of the predictions made by deep learning models is paramount in sensitive domains as well as for better decision making in general. We look at how to make deep learning models inherently explainable using a a concept learning approach."
---

As Deep Neural Networks (DNNs) continue to outperform competing methods in a number of fields, there has been a growing concern regarding the ethical and legal use of DNNs in sensitive tasks (e.g., healthcare). These concerns have inspired the development of interpretable-by-construction neural architectures that explain their predictions using “high-level concepts” (e.g., “has paws”, “has whiskers”). Concept learning models (e.g., CBMs [1] and CEMs [2]) are a recent example of such neural architectures where a DNN is trained first to learn a set of concepts that represent the activation or inactivation of known concepts and then use those to predict a task of interest. The utility of these models arises from the fact that at inference time they first predict a set of concepts whose semantical alignment can be used to explain the concept model’s output prediction (e.g., if the model predicted that an image has a “cat” in it, a possible concept explanation is that the concepts “whiskers”, “long ears”, and “paws” are active in the input image).

There are many aspect of concept learning that still need addressing. In this project, the student will focus on any (or all) of the following directions:

1. One of the limitations of concept learning is that a set of concept annotations is required at training time. This is costly and sometimes not even available and needs to be discovered. CEMs may be capturing concepts not provided at train time as part of their learnt embedding spaces [2]. If true, this allows the construction of more complete explanations using concepts not included during training but extracted from the learnt concept embeddings and assigned semantics via some post-hoc expert analysis. These discovered concepts can be iteratively reintroduced into a CEM’s training process as training-time concepts after they have been discovered through some post-hoc analysis. If successful, this will enable the creation of more interpretable models and the ability to discover valuable concepts beyond those provided as training annotations.

2. The newly discovered concepts may or may not denote obvious high-level interpretable pieces of knowledge. For example, in images, a new concept can be visualised and be interpreted. In other data modalities (e.g., genomics) it may not be obvious what the new concept denotes. One can use domain experts (e.g., medics) to manually inspect new concepts and determine if they are meaningful, but this is expensive. Alternatively, the direction here is to build methods for automatically naming newly discovered concepts. One way that may be promising is to leverage the power of large language models to exploit the existing knowledge bases (e.g., ontologies, knowledge graphs, digital repositories of articles, etc) to find out if the newly discovered concept is a known concept in the domain and thus name it.

3. Concept learning models allow for interventions of mispredicted concepts which in turn improves the model’s performance as well as allows a human-in-the-loop interaction with domain experts. Exploring how interventions can be done in an efficient, effective and automatic way is the direction of research here. 

***References***

[1] Koh, Pang Wei, et al. "Concept bottleneck models."  International Conference on Machine Learning. PMLR, 2020.

[2] Espinosa Zarlenga, Mateo, et al. "Concept embedding models: Beyond the accuracy-explainability trade-off."  Advances in Neural Information Processing Systems 35 (2022): 21400-21413.

[3] Espinosa Zarlenga, Mateo, et al. "TabCBM: Concept-based Interpretable Neural Networks for Tabular Data."  Transactions on Machine Learning Research  (2023).

[4] Oikarinen, Tuomas, et al. "Label-Free Concept Bottleneck Models."  ICLR  (2023).

[5] Kim, Eunji, et al. "Probabilistic Concept Bottleneck Models."  ICML  (2023).


## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/explainability-of-deep-learning-models-the-concept-learning-approach/?p168706)
