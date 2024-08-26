---
layout: archive
permalink: /Research/
author_profile: true
---

My overarching research interests revolve around community ecology. My early research focused on studying how species interactions shape the community dynamics in grassland and agriculture ecosystems,and their responses to climate and land use change (global meta-analysis). In recent years, my research journey has transitioned from experimental studies to theoretical modelling, driven by my desire to understand the mechanisms of community assembly and biodiversity dynamics at broader temporal and spatial scales.

# How species traits affect diversification rates and bodiversity patterns

Spectacular species radiations are perhaps the best known features of oceanic islands, however, these radiations with high diversification rates typically restricted to a limited number of lineages within an island. A key question is why do some groups radiate rapidly while others do not? As the number of independent phylogenetic studies increases, comparative analyses highlight that species traits are important drivers shaping diversification rates and biodiversity patterns. However, the effect of traits has been neglected in the current island biogeography models. Here, we develop a trait-dependent island biogeography framework to investigate how species traits affect macroevolutionary rates and biodiversity on islands (Figure 1).

![Illustration of combining vision and language modalities](/images/model.png){: .align-center width="500px"}

*Figure 1. Graphical visualization of a trait state-dependent simulation model.*


To examine whether ignoring traits in island studies can be problematic in estimating parameters and reconstructing the phylogenies, we developed a computational robustness pipeline. We generated island phylogenies under different scenarios of trait-dependent evolutionary rates (colonization, speciation and extinction) and assessed whether the trait-independent DAISIE model [Etienne et al. 2023](https://doi.org/10.5281/zenodo.4054058) can still accurately reconstruct the evolutionary history or not. It is an important tool to measure model performance when the model deviates from a given assumption, and  to determine whether it is meaningful to develop a likelihood-based or other estimation methods for the complex model.


![Illustration of combining vision and language modalities](/images/pipeline.png){: .align-center width="500px"}

*Figure 2. Schematic representation of the robustness pipeline. (1) Simulate phylogenetic data with the SDS model. The binary states are represented by two different colors (red and black). (2) Use the data obtained from step 1 to estimate parameters with the SII mo del. (3) Simulate data using the SIS model with parameters estimated in step 2. (4) Use the SII model again to estimate parameters. (5) Simulate data using the SIS model with the estimated parameters from step 4. E 0 baseline error when simulation and inf erence model are identical; E error when simulation and inference model differ.*


# How species traits affect diversification rates and bodiversity patterns









