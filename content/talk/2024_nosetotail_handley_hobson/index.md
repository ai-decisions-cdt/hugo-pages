---
title: "Nose-to-tail emulation with nested sampling for online decision-making"
author: ["Will Handley"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["willhandley","mikehobson"]
summary: "This project combines the expertise is Bayesian numerical methods and machine learning in the Cambridge astrophysics group, with the group's ongoing research programme in simulation based inference. The project will develop new methods for Bayesian inference and decisionmaking via state-of-the-art neural emulators, with applications to cosmology and beyond."
---

Neural emulation has risen to prominence in the last decade as a tool for AI-accelerating computationally expensive scientific models. Tools such as PICO [astro-ph/0606709], SkyNet [1309.0790], CosmoPower [2106.03846], and globalemu [2104.04336] have a successful history of enabling cosmological investigation by turning costly analyses requiring supercomputers to ones that can be done on a laptop. Beyond cosmology, emulators become all the more relevant for making real-time sub-second decisions in a principled Bayesian manner.

This PhD project will build on recent work that has shown nested sampling [2205.15570] offers unique advantages in the training of emulators [2312.00294]. The strategy by which nested sampling scans high-dimensional parameter spaces (starting from the deep tails of an objective function and focusing inward in a self-similar compression) is ideally suited for providing targeted training data for emulators, rendering them capable of emulating across far wider dynamic ranges than traditional approaches (e.g. as applied to HERA simulations [2108.07282]). Initial projects will begin developing on work begun with the BAMBI algorithm [1110.2997], for modern cosmological datasets, supported by the group's DiRAC allocations. The direct results of such projects will then be applied to Bayesian model comparison to both cosmological theories and Bayesian experimental design (e.g. REACH [2210.07409]), in which Bayes theorem acts as the ultimate arbiter in decision-making.

Projects building from this will then apply these emulation techniques to real-time problems beyond cosmology, in particular to the group's ongoing research in adversarial machine learning and nested active learning. There will also be opportunities to apply these emulators in the group's ongoing ERC research programme in simulation based inference [ERC]. Other topics available involve using nested sampling itself to train compromise-free Bayesian neural networks [2004.12211] [2205.11151], with the potential to provide emulation.

The Cambridge astrophysics group is a centre of expertise in nested sampling, machine learning and cosmology. In addition, there is opportunity to work with the group's spin-out company PolyChord Ltd in applying these tools to industry problems, for example in Electric vehicle battery design, with existing collaborations in the group between AI-driven materials science and with the GAMBIT particle physics collaboration [GAMBIT].

***References***

https://willhandley.co.uk/ERC.pdf 
https://github.com/handley-lab

https://arxiv.org/abs/astro-ph/0606709
https://arxiv.org/abs/1309.0790
https://arxiv.org/abs/2106.03846
https://arxiv.org/abs/2104.04336
https://arxiv.org/abs/2205.15570
https://arxiv.org/abs/2312.00294
https://arxiv.org/abs/2108.07282
https://arxiv.org/abs/1110.2997
https://arxiv.org/abs/2210.07409
[ERC]: https://willhandley.co.uk/ERC.pdf
https://arxiv.org/abs/2004.12211
https://arxiv.org/abs/2205.11151
[GAMBIT]: https://gambitbsm.org/

## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/nose-to-tail-emulation-with-nested-sampling-for-online-decision-making/?p168707)
