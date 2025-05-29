---
title:  "Shear Thinning of Lubricants"
mathjax: true
layout: post
categories: media
---
Shear thinning is a phenomenon where a fluid’s viscosity decreases with increasing shear rate, playing a critical role in many industrial applications. For example, lubricants—typical shear-thinning fluids—reduce friction and wear between moving parts, and their viscosity response under shear is essential for maintaining optimal performance.

<!--more-->

Laboratory experiments are typically limited to shear rates below 10⁵ s⁻¹, whereas real-world applications—such as engine oil lubrication—can involve shear rates reaching up to 10¹⁰ s⁻¹. While many rheological models can fit experimental data well within the measured range, their predictions often diverge significantly when extrapolated to higher shear rates. This makes it challenging to develop accurate rheological models that reliably capture shear thinning behavior across a broad spectrum of shear rates.

In this project, we employed non-equilibrium molecular dynamics (NEMD) simulations to investigate the rheological properties of lubricant molecules under high shear rates. NEMD has proven to be a powerful and reliable tool for accurately reproducing the Newtonian viscosities of lubricants. By combining NEMD simulation results with existing experimental data, we evaluated two key categories of rheological models central to the ongoing debate.

The first category includes power-law models, which posit that lubricant molecules align increasingly with the shear direction, thereby reducing intermolecular friction and, consequently, viscosity. The second category involves thermal activation models, which describe shear flow as a stress-biased, thermally activated process. In these models, applied shear stress lowers the energy barrier for molecular movement in the shear direction while raising it in the opposite direction.

We applied machine learning techniques—specifically, dimensionality reduction methods such as Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE)—to investigate the relationship between molecular orientation and shear rate in greater depth. Our analysis revealed that molecular orientation changes progressively with increasing shear rate at low to medium levels but becomes saturated at medium to high shear rates. Interestingly, fluid viscosity continues to decrease in this higher shear rate regime, which contradicts the assumptions of the power-law model.

To evaluate the validity of thermal activation models, we analyzed molecular rearrangement patterns, which these models identify as the primary mechanism behind shear thinning. Our results show that the observed molecular rearrangements are consistent with the theoretical predictions of the thermal activation model, supporting its relevance in describing rheological behavior at high shear rates.

See our publications:

[Comparing Phenomenological Models of Shear Thinning of Alkanes at Low and High Newtonian Viscosities](https://link.springer.com/article/10.1007/s11249-024-01908-7)

[Rheological Properties of Small-Molecular Liquids at High Shear Strain Rates](https://www.mdpi.com/2073-4360/15/9/2166)


![Squalane viscosity and shear stress under various shear rates](/assets/research_pics/viscosity_stress.png)
### Fig.1 Squalane viscosity and shear stress under various shear rates


![Squalane's atom pairs orientation under different pressures by PCA dimension reduction](/assets/research_pics/dist_backbone.png)
### Fig.2 Squalane's atom pairs orientation under different pressures by PCA dimension reduction

