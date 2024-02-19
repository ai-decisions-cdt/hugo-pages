---
title: "Understanding the Training of Neural Nets to Solve PDEs"
author: ["Anirbit Mukherjee"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["anirbit","alexfrangi","matthewcolbrook"]
summary: "This project plans to pioneer new frontiers in A.I. focusing on solving dynamical systems in use across physics, chemistry, engineering, and cardiology. This research proposal will establish new foundations to address possibilities and paradoxes in the broad theme of AI-for-Science and thus help define the limits of feasible deep learning. The Ph.D. student trained via this program will emerge with expertise in niche areas of A.I. that are poised to become critical in the near future."
---

In the last few years, there has been a surge in the literature on provable training of various kinds of neural nets in certain regimes of their widths or depths, or for very specifically structured data. This quest for provable deep learning is turning out to be an exciting pathway into hitherto unexplored regimes of mathematics. Motivated by the abundance of experimental studies it has often been surmised that Stochastic Gradient Descent (SGD) on neural net losses – with proper initialization and learning rate – converges to a low-complexity solution, one that generalizes – when it exists (ZLR+17). But only very recently there have appeared ways to try proofs of convergence of SGD on neural losses without either an assumption on the width or the data. And rarer still are studies of the limitations on the quality of neural nets obtainable by any algorithm at all. In this Ph.D. project, the student will explore both the above questions – specifically for setups being developed for scientific ML, like Physics Informed Neural Nets (PINNs) and Neural Operators (NOs.) (CLL, RPO23) 

In (GM22), in a first-of-its-kind result, certain recent developments in the theory of SDEs and Villani functions were leveraged to show that continuous-time SGD converges to the global minima of an appropriately Frobenius norm regularized squared loss on any depth 2 neural net with smooth activations – for arbitrary width and data. This immediately leads to the following intriguing question, 

Question : 

Are there PDEs corresponding to which loss functions can be written down in either the PINN or the NO setups such that they are Villani functions? 

Identification of the kinds of PDEs where the above question has an affirmative answer immediately and significantly pushes further our understanding of what PDEs are possibly efficiently solvable via neural nets. One can also see works like (BHT23) for another perspective on this question which can also be explored. 

In works like (MR23) the authors have initiated a study of provably necessary architectural properties of the nets involved in a DeepONet setup (an instantiation of the Neural Operator formalism) so that low error predictors can at all exist. On the other hand, motivated by failure modes of using neural nets in medical imaging (MRR+21), a novel approach to investigating the limitations of training neural nets has been shown in (CAH22). It was demonstrated that there are well-conditioned imaging problems where accurate and stable neural networks provably exist, yet for any integer K > 2, such a class of imaging problems can be constructed such that one cannot compute a neural network that provides a 10^(−K)-accurate solution for this problem but a training algorithm exists that computes a 10−(K−1)-accurate neural network using an arbitrarily large amount of data. Moreover, a 10−(K−2)-accurate neural network can be trained with just a few training samples. Notably, these results hold for any distribution of the training data. 

The proof techniques of (CAH22) stem from the mathematics behind the Solvability Complexity Index (SCI) hierarchy (BACH+15). The second part of this Ph.D. plan would aim to extend these methods to scientific M.L. and discover provable limitations of solving PDEs via deep-learning methods. It is envisioned that this framework will reveal stability vs accuracy trade-offs in solving PDEs via neural nets. 

Lastly, we note that similar questions as above can also be asked in the context of Koopman operators for nonlinear dynamical systems (BBKK22, CT24). 

***References***

[BACH+15]  Jonathan Ben-Artzi, Matthew J Colbrook, Anders C Hansen, Olavi Nevanlinna, and Markus Seidel. Computing spectra–on the solvability complexity index hierarchy and towers of algorithms. https: // doi. org/ 10. 48550/ arXiv. 1508. 03280 , 2015.  

[BBKK22]  Steven L Brunton, Marko Budisic, Eurika Kaiser, and J Nathan Kutz. Modern Koopman theory for dynamical systems. SIAM Review, 2022.  

[BHT23]  Nicolas Boullé, Diana Halikias, and Alex Townsend. Elliptic PDE learning is provably data-efficient. Proceedings of the National Academy of Sciences, 120(39), September 2023.  

[CAH22]  Matthew J Colbrook, Vegard Antun, and Anders C Hansen. The difficulty of computing stable and accurate neural networks: On the barriers of deep learning and Smale’s 18th problem. Proceedings of the National Academy of Sciences, 119(12):e2107151119, 2022.  

[CLL]  ETH CAM Lab Lectures. Deep learning in scientific computing 2023. [https://youtube.com/playlist?list=PLJkYEExhe7rYY5HjpIJbgo-tDZ3bIAqAm&feature=shared](https://youtube.com/playlist?list=PLJkYEExhe7rYY5HjpIJbgo-tDZ3bIAqAm&feature=shared)   

[CT24]  Matthew J. Colbrook and Alex Townsend. Rigorous data-driven computation of spectral properties of Koopman operators for dynamical systems. Communications on Pure and Applied Mathematics, 77(1):221–283, 2024.  

[GM22]  Pulkit Gopalani and Anirbit Mukherjee. [Global Convergence of SGD On Two Layer Neural Nets.](https://doi.org/10.48550/arXiv.2210. 11452), 2022. 

[MR23]  Anirbit Mukherjee and Amartya Roy. [Size Lowerbounds for Deep Operator Networks].(https://doi.org/10.48550/arXiv.2308.06338), 2023.

[MRR+21]  Matthew J Muckley, Bruno Riemenschneider, Alireza Radmanesh, Sunwoo Kim, Geunu Jeong, Jingyu Ko, Yohan Jun, Hyungseob Shin, Dosik Hwang, Mahmoud Mostapha, et al. Results of the 2020 fastMRI challenge for machine learning MR image reconstruction. IEEE transactions on medical imaging, 40(9):2306–2317, 2021.

[RPO23]  Deep Ray, Orazio Pinti, and Assad A Oberai. [Deep learning and computational physics (lecture notes).](https://doi.org/10.48550/arXiv.2301.00942), 2023.

[ZLR+17]  Chiyuan Zhang, Qianli Liao, Alexander Rakhlin, Karthik Sridharan, Brando Miranda, Noah Golowich, and Tomaso Poggio. Musings on deep learning: Properties of sgd. Technical report, Center for Brains, Minds and Machines (CBMM), 2017. 


## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/understanding-the-training-of-neural-nets-to-solve-pdes/?p168684)
