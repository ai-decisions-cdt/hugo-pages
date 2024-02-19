---
title: "Human-in-the-loop Generative Models for Experimental Design"
author: ["Samuel Kaski"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["samuelkaski","patrickcai","mingfeisun"]
summary: "Experimental Design, which is the driving force of all empirical science and much of product development, involves brute-force trial and error to reach a desired outcome. While we have seen successful applications of AI driven experimental design, they are still faced with the challenges of small data, heterogeneous inputs, and domain knowledge. This project aims to use human-in-the-loop generative models to tackle these challenges. We will test the principles in running the Design-Build-Test-Learn (DBTL) loops in Synthetic Biology through the collaboration of the supervisors."
---

[Background & Challenges] Experimental Design, which is the driving force of all empirical science and much of product development, often involves brute-force trial and error to reach a desired outcome which may not be optimal. While we have seen successful applications of AI driven experimental design, they are still limited and tailored to a particular dataset and research question. Challenges still remain: (1) The stages in a typical experimental design are still rather expensive and while AI-assistance is available for some individual operations, automation is not yet widely affordable. As a consequence, the available datasets consisting of many designs for one specific experiment can be quite limited -- Small data [1]; (2) Each design can have a seemingly vast amount of multi-modal, multi-task and multi-embodiment data generated from a typical high-throughput experiment, but the large number of variables makes the problem only harder when sample size remains severely small -- Heterogeneous inputs; and (3) Generalizing from the small-scale experiments in design cycles to forecast the behavior of next iteration of design, and further to laboratories at a larger scale is fundamentally difficult as machine learning is notoriously bad in generalizing outside the training distribution without first-principles – Domain knowledge [2].
 
[Objectives] This project aims to use human-in-the-loop generative models for experimental design. Specifically, the project will use generative models to capture the underlying distribution of well designed experiments and then transfer to unseen experiments. The transferring will leverage 
Bayesian optimal experimental design methods to bring expert domain knowledge to bear in the sequential decision task of navigating the design space even with small heterogeneous data [3, 4]. With Bayesian experimental design principles we can choose the next experiment to run, combining candidates from generative models of experiments, and data collected so far from measurements and the user. This experimental design approach will be integrated with transformers to handle heterogeneous data that merges experimentally generated patterns and model-generated databases. 

We will test the principles in running the Design-Build-Test-Learn (DBTL)  loops in Synthetic Biology, where we have outstandingly interesting case studies available through the collaboration of the supervisors, and ultimately can generalize also to other fields with additional collaborations.


***References***

1 Online simulator-based experimental design for cognitive model selection, https://arxiv.org/pdf/2303.02227.pdf 
2 Human-in-the-loop assisted de novo molecular design, https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00667-8 
3 Differentiable User Models, https://proceedings.mlr.press/v216/hamalainen23a/hamalainen23a.pdf 
4 Approximate Bayesian Computation with Domain Expert in the Loop, https://proceedings.mlr.press/v162/bharti22a.html 


## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/human-in-the-loop-generative-models-for-experimental-design/?p168697)
