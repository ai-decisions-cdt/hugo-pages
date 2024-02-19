---
title: "Compressed descriptors of damage microstructures in fusion materials"
author: ["Joseph  Robson"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["josephrobson","juliahandl","pratheekshanthraj","christopherrace"]
summary: "Structural materials in a tokamak fusion reactor are designed to withstand extreme temperatures, stresses, and radiation damage during their operation. Radiation damage, from bombardment with high-energy neutrons, result in complex defect structures that evolve across a wide range of time and length scales. Quantifying this damage structure and how it relates to degradation of material strength is critical to assessing risk of failure in reactor components. 

While experimental characterisation under neutron irradiation is time consuming, expensive and, in many cases, impossible, atomistic simulation methods can model individual damage events, involving millions of atoms, with a high level of fidelity to the true physics. However, raw data from these simulations, described by the positions of millions of atoms, is too large to parameterize predictive models of long-term damage accumulation across reactor components. Thus, the key to unlocking reduced order models for radiation damage lies in the development of a compressed representation of the underlying defect structures. Such a microstructure fingerprint reduces model parameterization from millions of atoms to a more manageable number of descriptor features.

Machine learning methods are increasingly accelerating the development of these fingerprints by treating microstructure evolution as a pattern recognition problem. In this project, we propose to generalize recent advances in microstructure image fingerprinting to graph data, which is the more natural setting to represent changes in local atomic neighbourhoods. Graph-based autoencoders will be developed to extract global and local descriptors of radiation damage microstructures in Tungsten – a critical plasma facing component which is exposed to the highest neutron doses in a reactor – using a large dataset of high-fidelity atomistic damage simulations. Furthermore, time-series data will also be used to learn the latent space dynamics of these damage descriptors.
The outcome of this project will enable the parameterisation of fast and actionable reduced order models for radiation damage evolution in fusion reactor components, which will significantly accelerate their in-silico design and qualification.
"
---

Structural materials in a tokamak fusion reactor are designed to withstand extreme temperatures, stresses, and radiation damage during their operation. Radiation damage, from bombardment with high-energy neutrons, result in complex defect structures that evolve across a wide range of time and length scales. Quantifying this damage structure and how it relates to degradation of material strength is critical to assessing risk of failure in reactor components. 

While experimental characterization under neutron irradiation is time consuming, expensive and, in many cases, impossible, atomistic simulation methods can model individual damage events, involving millions of atoms, with a high level of fidelity to the true physics. However, raw data from these simulations, described by the positions of millions of atoms, is too large to parameterize predictive models of long-term damage accumulation across reactor components. Thus, the key to unlocking reduced order models for radiation damage lies in the development of a compressed representation of the underlying defect structures. Such a microstructure fingerprint reduces model parameterization from millions of atoms to a more manageable number of descriptor features.

Machine learning methods are increasingly accelerating the development of these fingerprints by treating microstructure evolution as a pattern recognition problem. In this project, we propose to generalize recent advances in microstructure image fingerprinting [1] to graph data, which is the more natural setting to represent changes in local atomic neighborhoods. Graph-based autoencoders will be developed to extract global and local descriptors of radiation damage microstructures in Tungsten – a critical plasma facing component which is exposed to the highest neutron doses in a reactor – using a large dataset of high-fidelity atomistic damage simulations. Furthermore, time-series data will also be used to learn the latent space dynamics of these damage descriptors.
The outcome of this project will enable the parameterization of fast and actionable reduced order models for radiation damage evolution in fusion reactor components, which will significantly accelerate their in-silico design and qualification.


***References***

[1] M.D. White, A. Tarakanov, P.J. Withers, C.P. Race, K.J.H. Law, Digital fingerprinting of microstructures, Computational Materials Science, Volume 218, 2023.

## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/compressed-descriptors-of-damage-microstructures-in-fusion-materials/?p168699)
