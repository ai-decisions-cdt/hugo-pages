---
title: "Generative Models for Large-Scale Combinatorial Decision-Making"
author: ["Mingfei Sun"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["mingfeisun","manuellopezibanez"]
summary: "Combinatorial Decision-Making has numerous practical applications across domains varying from logistics, physics, to fundamental sciences. As the search space typically grows exponentially with the problem size, combinatorial decision-making is often tackled with handcrafted heuristics using expert knowledge. This project leverages Generative Models (GMs), including Large Language Models and diffusion models to capture those handcrafted heuristics for solving large-scale combinatorial decision-making problems. "
---

Combinatorial Decision-Making– where the maxima or minima of an objective function acting on a finite set of discrete variables is sought – has attracted significant interest in many studies on decision-making for complex systems due to both their (often NP) hard nature and numerous practical applications across domains varying from logistics, physics, material science to fundamental sciences. As the search space of feasible solutions typically grows exponentially with the problem size, exact solvers can be challenging to scale; hence, combinatorial decision-making problems are often tackled with handcrafted heuristics using expert knowledge, which, however, are often hard to devise even for experienced domain experts. 

Generative Models (GMs), including Large Language Models (LLMs) such as ChatGPT/GPT4 and diffusion models such as Dalle2, allow AI to generate images/text, write code, generate synthetic data and naturally interact with a computer. Whilst the highest profile applications of GMs have been in text and images [1], this project seeks to improve their utility in combinatorial decision-making problems to enable the capture of the delicate characteristics of handcrafted heuristics from expert knowledge [2]. 

Specifically, this project tackles the following significant research challenges: (1) modelling of graph-structured distributions: combinatorial optimization problems are usually described in the form of graphs, with nodes and edges corresponding to the discrete variables. This graph-structured distribution will pose a great challenge for modelling the heuristics with the generative models since the latter focuses primarily on vector distributions; (2) training efficiency for large-scale problems: As the problem size increases, solving for even feasible (not optimal) solutions with the heuristic methods will be slow and computationally expensive. This will be exacerbated by the even more computationally intensive training of generative models; and (3) expert-in-the-loop learning: capturing the heuristics using expert knowledge inevitably requires the expert in the loop for the training. Ensuring that models align with expert values and learn the effective heuristics for solution construction will need a more delicate design of the generative sampling process. 


***References***

1. Imitating Human Behaviour with Diffusion Models, Tim Pearce, Tabish Rashid, Anssi Kanervisto, Dave Bignell, Mingfei Sun, Raluca Georgescu,
Sergio Valcarcel Macua, Shan Zheng Tan, Ida Momennejad, Katja Hofmann, Sam Devlin, https://openreview.net/pdf?id=Pv1GPQzRrC8

2. Effective Generation of Feasible Solutions for Integer Programming via Guided Diffusion, Hao Zeng, Jiaqi Wang, Avirup Das, Junying He, Kunpeng Han, Haoyuan Hu, Mingfei Sun, https://openreview.net/pdf?id=joMMM9eadc 


## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/generative-models-for-large-scale-combinatorial-decision-making/?p168692)
