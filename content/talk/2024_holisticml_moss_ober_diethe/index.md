---
title: "Holistic ML-guided Design for the High-throughput Optimisation of Biologics"
author: ["Henry Moss"]
lastmod: 2024-01-24T22:47:03+00:00
draft: false
weight: 4001
event: "Projects 2024"
authors: ["henrymoss","sebastianober","tomdiethe"]
summary: "This project aims to develop interactive machine learning methods that help AstraZeneca scientists guide high-throughput screening in drug discovery pipelines."
---

Although AI has revolutionised numerous design processes, its impact on end-to-end biologic optimization campaigns, where we design large, complex molecules such as proteins or  antibodies, has so far been limited. In existing ML-guided design algorithms, a crucial assumption is that the problem is fully understood and specified before beginning optimisation. However, this assumption doesn't hold in drug design: distilling the knowledge of scientists, which is often based on intuition and partial information, into computable quantities is challenging. Furthermore, the goals of drug design can change as we gain insight about what constitutes a "good" biologic in the current context. 

Consider the following typical drug design pipeline. We might start with a few promising candidates (leads) which are then extensively optimised to match the candidate drug target profile (CDTP) specifying desirable properties such as chemical affinity to the target, biological activity, and developability. Unfortunately,  it is not uncommon for leads with good affinity relative to the CDTP to fail due to other developability properties which are more difficult to assess. Moreover, developability constraints are typically only proxies for good in-vivo properties, so our optimised lead can still fail for unexpected reasons in early-stage clinical trials. Finally, our objectives may change during the campaign as we obtain new data. For instance, scientists’ improved understanding of the relationship between activity and in vivo characteristics could cause a change in the developability criteria. In a more extreme case, the discovery of a lead with very high affinity may cause us to investigate a different route of administration (e.g., inhalation rather than intravenous), completely changing the developability objectives and the downstream manufacturing processes.

In this project, our goal  is to develop a novel ML-based design approach that embraces the dynamic nature and varying costs of drug design. In current pipelines, encountering any of these challenges would force us to return to an earlier stage of the discovery process, thus wasting time and resources. Moreover, it is typically difficult to get much use out of the data obtained from these unsuccessful experiments as we pivot our search into different areas of the biologics space. By employing feedback loops, enforcing diversity within experiments, and integrating human expertise throughout the process, we will focus on forming a holistic understanding of what defines a good biologic in the current context based on insights and issues that arise in real time during a screening campaign, rather than blindly maximising potentially incomplete or misleading objectives.

The overarching theme of our project extends beyond the traditional role of ML in drug design, exploring its potential to support drug design at a systems level. We aim to elevate ML's role beyond mere sub-optimizations, delving into key areas such as multi-fidelity optimization, leveraging different assays and in-silico methods; batch optimizers to support high-throughput screening and library design; sequence optimization, considering noisiness in sequence generation for improved accuracy; and ML-guided human interaction, devising methods for effective collaboration between ML algorithms and expert scientists.

***References***

Existing work on a more holistic approach to biologics optimisation:
Assessing Developability Early in the Discovery Process for Novel Biologics. Fernández-Quintero et al. mAbs 2023.

Existing work on active learning for biologics optimisation with realistic constraints:
AntBO: Towards Real-World Automated Antibody Design with Combinatorial Bayesian Optimisation. Khan et al. 2022.

Initial promising work on using human interactions to help guide ML-driven optimisation:
Preference Exploration for Efficient Bayesian Optimization with Multiple Outcomes. Lin et al. International Conference on Artificial Intelligence and Statistics 2023.


## Additional information

Additional information in [**Find A PhD**](https://www.findaphd.com/phds/project/holistic-ml-guided-design-for-the-high-throughput-optimisation-of-biologics/?p168705)
