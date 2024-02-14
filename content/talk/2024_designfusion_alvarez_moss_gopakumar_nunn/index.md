---
title: "ML-driven Design for Fusion Reactors"
author: ["Mauricio Alvarez"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["mauricioalvarez","henrymoss","vigneshgopakumar","timothynunn", "stanislaspamela"]
summary: "This project aims to pioneer interactive ML optimisation techniques to help scientists at the UK Atomic Energy Authority tackle the intricate design challenges inherent in developing sustainable fusion energy solutions and make informed decisions that can accelerate progress in nuclear fusion research.
"
---

The goal of a fusion reactor is to confine plasma at a sufficiently high temperature to generate fusion reactions, allowing the generation of electricity. A leading candidate for building a practically useful fusion reactor — one that produces more energy that is required to begin the reaction — is a confinement system laid out in a toroidal structure known as a tokamak. However, in order to ensure efficiency of the tokamak, a wide variety of physics and engineering challenges must be resolved within the limited amount of space available in the reactor, thus posing a complicated design problem. Moreover, evaluating the suitability of any candidate reactor is a laboriously slow process, involving multiple levels of computationally expensive simulations and requirements from multiple stakeholders. Consequently, traditional design processes are unsuitable, as they require many design iterations and explore only a small fraction of possible design possibilities.

To demonstrate the complexity of designing a fusion reactor system, we can look at just one of its many key components — the toroidal field (TF) coils. The TF are responsible for the generation of the magnetic pressure confining the plasma and thus must be carefully optimised to minimise the toroidal field variations (ripple) occurring at the plasma boundaries that drive the overall performance of the tokamak. However, as choices in the TF influences various other practical aspects of the tokamak design, from the distribution of the electromechanical forces (structural integrity) to the size of the reactor (financial cost), the TF cannot be designed in isolation, without a system-level understanding of the vast overall reactor design space.

In this project, we will work with scientists from the UK Atomic Energy Authority (UKAEA) to develop novel ML-driven optimisation routines that help tackle the intricate design challenges inherent in developing sustainable fusion energy solutions. In particular, we will depart from traditional reactor design processes, and instead follow the paradigm of Bayesian sequential design, which has risen as an effective ML-driven strategy for high-cost design problems over complex search spaces through methods such as Bayesian Optimisation (BO) and active learning. Indeed, the potential benefits of such AI-based exploration for optimum fusion reactor components has already been demonstrated in initial work by scientists at UKAEA, where existing BO methodology was able to successfully design a simplified 8-dimensional parametrisation of the TF coils. However, extending this  proof-of-concept work to a level where it can accelerate progress in nuclear fusion research requires novel methodology in key areas such as 1) high-dimensional and multi-fidelity optimization, leveraging different levels of computational simulations; 2) optimisation of manifolds to allow direct optimisation of 3D structures like TF coils; and 3) ML-guided human interaction, devising methods for effective collaboration between ML algorithms and expert scientists even when objectives are poorly defined or not fully know before beginning optimisation.


***References***

Existing proof of concept Bayesian optimisation work on TF coil design: 
https://gp-seminar-series.github.io/neurips-2022/assets/camera_ready/45.pdf

Information about design frameworks for Tokamaks: 
https://ccfe.ukaea.uk/resources/bluemira/
https://iopscience.iop.org/article/10.1088/1741-4326/ac6433
https://github.com/Fusion-Power-Plant-Framework/bluemira#publications


