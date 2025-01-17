---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Understanding the growth-biomass links in mature forests"
subtitle: ""
summary: ""
authors: [Laura Marqués]
tags: ["growth enhancements", "biomass stocks", "self-thinning"]
categories: []
date: 2023-09-20T17:17:30+01:00
lastmod: 2023-09-20T17:17:30+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "European beech forest, Trüllikon ZH. *Source: Swiss Forest National Inventory.*"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Forest demographic processes are being altered by global change. Elevated atmospheric carbon dioxide has been reported to enhance photosynthesis and tree growth rates. Different studies have reported increased tree growth globally over the last decades (Brienen et al., 2015; Hubau et al., 2020) but the implications for long-term carbon storage in forests remain unknown. Tree growth enhancement could be translated into an increase in biomass stocks or could be associated with a reduction in tree longevity, compensating for any potential change in biomass, as has been established by the ***grow-fast-die-young*** hypothesis (*GFDY*). In our study recently published in AGU Advances [(Marqués et al., 2023)](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022AV000859), we investigated whether accelerated tree growth leads to increased biomass stocks. These links between growth and biomass have been difficult to study because on the one hand, it is an observational challenge - what we can record today is very much affected by the history of the stand development and past disturbances. In the other hand, although we know which mechanisms are at play, scarce empirical evidence exists for how changing drivers affect these processes making it difficult to evaluate their net effect.

We can formulate this question in quantitative terms asking what is the relative change in biomass (*dB/B*) per unit relative change in growth (*dG/G*)? We can start with a NULL model and consider that the relative change in growth is equal to the relative change in biomass, that is the 1:1 line. We refer to this linear response as the ***constant turnover*** where biomass at the steady state depends on growth and on turnover rate. But based on what we know from observations and how we understand the mechanisms, we can expect an ***accelerated turnover***, which leads to a non-linear response where the relative increase in biomass is smaller than the relative increase in growth. During stand development, a large number of small seedlings grow to the point that canopy closes and mutual shading sets in. As a consequence, smaller individuals suffer light limitation and at some point die. So, an emergent relationship appears between the number of individuals in the stand and the average size. In the log-log scale, this leads to a negative relation called the self-thinning line (STL). As the stands mature, density-driven mortality kicks in and the surviving trees continue growing. If the ***GFDY*** hypothesis holds, this will imply that trees just progress faster along the STL with a ***constant self-thinning*** where no or only a very small change in stand-level biomass would result from enhanced growth. 

![Conceptual model](fig2.png "Conceptual model of biomass and STL responses to tree growth enhancement.")

We combined **forest observations** and **model simulations** to evaluate to what extent tree growth enhancements lead to persistent increases in forest biomass stocks. First, we used long-term forest data from unmanaged stands in Switzerland to evaluate responses of the STL to growth enhancement. We selected only data from plots where no management was recorded during and before the censuses. To minimize the effects of natural past disturbances, we further retained only plots for which the stand density was in the upper 75<sup>th</sup> percentile of average plot-level tree sizes. We found that the negative relationship between the number and the size of trees has not remained stable but shifted upward over time, i.e., for a given size, forest stands tend to have become denser over time. Further, the self-thinning relationship exhibited a change as a function of growth anomalies, derived from stand-level growth, indicating also a spatial change across forest plots. The positive effect of both *calendar year* and *growth anomalies* on the intercept of the STL indicates that the relationship between biomass and density has not been stationary but has shifted significantly over the past decades. 

![STL changes](fig3.png "STL changes as a function of time and growth in unmanaged Swiss forests.")

Second, using a cohort-based vegetation demography model (BiomeE, [Weng et al. 2015)](https://bg.copernicus.org/articles/12/2655/2015/) to explore under which conditions persistent biomass stock increases result from growth enhancements. BiomeE simulates leaf-level ecophysiology, individual-level competition for light and soil resources, forest structural dynamics, and biogeochemical processes. To test the *GFDY* hypothesis, a U-shape mortality was specified with higher mortality rates for the smaller and younger understory cohorts and a size-dependent mortality rate for the upper-canopy trees. We also evaluate the influence of the mortality curvature on the *growth-biomass* link by testing different mortality parameterizations. To simulate tree growth enhancement, we applied a step-increase in the light use efficiency (LUE) of photosynthesis by two levels (+15% and +30%). Higher LUE and a resulting tree-level growth enhancement represent effects of a growing season extension, enhanced nutrient inputs, relieving of cold-limitation, or increasing atmospheric CO<sub>2</sub>. A biomass increase under enhanced growth was simulated in all model setups, but the magnitude of the change varied substantially with the shape of the mortality function - the higher the curvature, the lower the increase in biomass. Importantly, the relative increase in biomass was smaller than the relative change in growth, indicating a reduction in the apparent carbon residence time and tree longevity which follows the non-linearity described before. 

![Model simulations](fig4.png "Model simulations for size-dependent mortality showing absolute and relative changes in biomass, growth, mortality, carbon turnover rate and tree longevity.")

The increase in steady-state biomass with enhanced growth was also reflected in the upward shift of the modeled STL, pointing to larger trees for a given stand density or denser stands for a given average tree size - consistent with observations. The influence of the mortality parameterizations was also evident in the degree to which the STL is shifted in response to growth enhancements, with a higher curvature leading to a weaker change in the STL. Biomass was largely constant along the STLs and thus, an upward shift of the STL indicated that biomass increased at conditions where self-thinning is acting. 

![Simulated STL changes](fig5.png "Simulated STL changes under increased LUE.")

Taken together, we found that the position of the STL has shifted upwards over time and as tree growth rates increased in unmanaged, closed-canopy forests in Switzerland. Simulated tree growth enhancements lead to a positive net increment in biomass despite reductions in carbon residence time and tree longevity - they are not mutually exclusive. These findings reconcile reports of tree longevity reductions ([Büntgen et al. 2019](https://www.nature.com/articles/s41467-019-10174-4); [Brienen et al. 2020](https://www.nature.com/articles/s41467-020-17966-z)) with model predictions of increased forest biomass ([Yu et al. 2019](https://www.pnas.org/doi/full/10.1073/pnas.1821387116); [Pugh et al. 2020](https://bg.copernicus.org/articles/17/3961/2020/)), both of which are consistent with the mechanistic understanding outlined here. Yet, the ratio of relative changes in growth and biomass was critically affected by the shape of the mortality function, with the stronger the curvature in the size-mortality parameterization, the smaller the increase in biomass and the upward shift in the STL. Our findings further emphasize the need for long-term monitoring plots to better understand the links between growth and biomass and to constrain influential, yet not directly observable model parameters.

### Full article
Marqués, L., Weng, E., Bugmann, H., Forrester, D. I., Rohner, B., Hobi, M. L., et al. (2023). Tree growth enhancement drives a persistent biomass gain in unmanaged temperate forests. AGU Advances, 4, e2022AV000859. https://doi.org/10.1029/2022AV000859

## Data availability
Data analyses and evaluations were based on data from the Swiss National Forest Inventory (NFI), the Experimental Forest Management (EFM), and the Natural Forest Reserves (NFR) and are available upon request to the specific networks.

## Open access code
Code for the data analyses and model simulations of this study is available at the GitHub repository geco-bern/GFDY, https://doi.org/10.5281/zenodo.7326085.
