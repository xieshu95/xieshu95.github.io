---
layout: archive
permalink: /Research/
author_profile: true
---

My overarching research interests revolve around community ecology. My early research focused on studying how species interactions shape the community dynamics in grassland and agriculture ecosystems,and their responses to climate and land use change (global meta-analysis). In recent years, my research journey has transitioned from experimental studies to theoretical modelling, driven by my desire to understand the mechanisms of community assembly and biodiversity dynamics at broader temporal and spatial scales.

# How species traits affect diversification rates and bodiversity patterns

Spectacular species radiations are perhaps the best known features of oceanic islands, however, these radiations with high diversification rates typically restricted to a limited number of lineages within an island. A key question is why do some groups radiate rapidly while others do not? As the number of independent phylogenetic studies increases, comparative analyses highlight that species traits are important drivers shaping diversification rates and biodiversity patterns. However, the effect of traits has been neglected in the current island biogeography models. Here, we develop a trait-dependent island biogeography framework to investigate how species traits affect macroevolutionary rates and biodiversity on islands (Figure 1).

![Illustration of combining vision and language modalities](/images/model.png){: .align-center width="500px"}

*Figure 1. Graphical visualization of a trait state-dependent simulation (SIS) model.*


To examine whether ignoring traits in island studies can be problematic in estimating parameters and reconstructing the phylogenies, we developed a computational robustness pipeline. We generated island phylogenies under different scenarios of trait-dependent evolutionary rates (colonization, speciation and extinction) and assessed whether the trait-independent DAISIE model [(Etienne et al. 2023)](https://doi.org/10.5281/zenodo.4054058) can still accurately reconstruct the evolutionary history or not. It is an important tool to measure model performance when the model deviates from a given assumption, and  to determine whether it is meaningful to develop a likelihood-based or other estimation methods for the complex model.


![Illustration of combining vision and language modalities](/images/pipeline.png){: .align-center width="400px"}

*Figure 2. Schematic representation of the robustness pipeline. (1) Simulate phylogenetic data with the SDS(trait state-dependent simulation) model. The binary states are represented by two different colors (red and black). (2) Use the data obtained from step 1 to estimate parameters with the SII (state-independent inference) model. (3) Simulate data using the SIS (state-independent simulation) model with parameters estimated in step 2. (4) Use the SII model again to estimate parameters. (5) Simulate data using the SIS model with the estimated parameters from step 4. E0 baseline error when simulation and inference model are identical; E error when simulation and inference model differ.*

The development and implementation of the trait-based island biogeography framework would contribute to research on a variety of open questions, such as how functional traits are associated with diversification rates, as well as providing insights into island conservation. Our next step is the application of the entire framework in empirical studies.

![Illustration of combining vision and language modalities](/images/birds.png){: .align-center width="400px"}

*Figure 3. Distribution of flightlessness across native bird clades of New Zealand. The plot shows the estimated times of colonization of the different lineages of native land birds of New Zealand, based on time calibrated phylogenies. Circles to the right of each lineage indicate the flight states for the species in that lineage.*


# Bayesian inference in diversification models

A popular statistical inference framework is likelihood-based estimation. However, likelihood-based methods are not always available for complex models because of the computational intractability of the likelihood. A promising alternative is Approximate Bayesian Computation (ABC), which is a simulation-based and likelihood-free approach. Here, we advance the use of Bayesian inference methods (MCMC and ABC) in both island biogeography and trait-dependent diversification models. For these models, likelihood-based inference is possible, which gives us the opportunity to assess the performance of ABC and MCMC inference method, and select powerful summary statistics.


![Illustration of combining vision and language modalities](/images/ABC.png){: .align-center width="400px"}

*Figure 4. Illustration of the ABC-SMC algorithm.*


# response of SOC and microbial community to climate and land use change (meta-analysis)

I am also fascinated by soil science, especially the dynamics of soil organic matter and microbial biomass. We applied global meta-analysis to understand the impact of grassland conversion to cropland on soil carbon losses, as well as the response of SOC and soil microbial biomass to elevated CO2 (eCO2). Through these studies, we emphasized the importance of incorporating environmental factors into ecosystem models, to accurately predict future global climate change effects and their impact on ecosystem functions.

![Illustration of combining vision and language modalities](/images/meta.png){: .align-center width="400px"}




