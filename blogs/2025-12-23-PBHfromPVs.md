---
layout: default
title:   "Primoridal Black Holes from Primordial Voids"
date:   20205-12-23 02:19:19 +0200
categories: cosmo
image:
  feature: 
  teaser: 
---

---

### Summary

Primordial Black Holes (PBHs) are usually associated with rare overdensities in the primordial curvature perturbation, which collapse upon Hubble re-entry during radiation domination. In our new work, however, we explore a qualitatively different and previously overlooked formation channel: PBHs formed from primordial voids, i.e. large negative curvature perturbations.

In the paper [arXiv:2411.07647](https://arxiv.org/abs/2411.07647), we show using full numerical relativity simulations that sufficiently deep primordial voids (PVs) do not simply disperse. Instead, after Hubble re-entry, they undergo a nonlinear rebound at their center, dynamically generating an overdense core that can subsequently collapse into a PBH.

This mechanism establishes primordial voids as a novel channel for PBH formation, complementary to the standard overdensity picture, and highlights the importance of accounting for both signs of primordial curvature fluctuations when assessing PBH abundances and cosmological signatures.


### From Voids to Black Holes

A negative curvature perturbation corresponds initially to an underdense region that expands faster than the background. While this might appear hostile to gravitational collapse, the situation changes once nonlinear dynamics are taken into account.

Due to the oscillatory nature of the curvature profile (we focus on a sinc-shaped profile associated with a monochromatic power spectrum), a primordial void is always surrounded by an overdense shell. After Hubble crossing, pressure gradients and self-gravity cause this shell to contract, driving matter back toward the center. If the void is sufficiently deep, this rebound produces a central overdensity that collapses into a PBH. Otherwise, the system dissipates into sound waves.

This process is intrinsically relativistic and cannot be captured by linear theory. We therefore study it using fully general-relativistic hydrodynamical simulations in spherical symmetry.


The figure below illustrates the dynamical evolution of primordial voids re-entering the Hubble horizon during radiation domination.

&nbsp;

{:refdef: style="text-align: center;"}
<p align = "center">
<img src="/images/tri_-1.8.png" alt="fig ecm" width="800"/>
</p>

<p align = "center">
Fig. 1, Dynamics of formation and collapse of a primordial void into a black hole.   
</p>
{: refdef}


The panels show, from top to bottom, the energy density contrast, the relative recession velocity with respect to the background expansion, and the (rescaled) three-dimensional Ricci curvature. These diagnostics clearly reveal the qualitative difference between collapsing and non-collapsing voids.



#### Thresholds and Mass Scaling

We determine the critical amplitude required for PBH formation from primordial voids across a range of equations of state. As expected, collapse from voids requires larger amplitudes than the overdensity case, since gravity must overcome the initially open geometry of the core.

Remarkably, once collapse occurs, the resulting PBHs obey a critical mass scaling relation entirely analogous to the standard overdensity scenario,
$$
M_{\rm PBH} \propto |\mu - \mu_c|^{\gamma},
$$
with a critical exponent \(\gamma\) that depends primarily on the equation of state and is nearly identical for positive and negative curvature perturbations.


&nbsp;

{:refdef: style="text-align: center;"}
<p align = "center">
<img src="/images/bhmasses_neg.png" alt="fig ecm" width="800"/>
</p>

<p align = "center">
Fig. 2, Mass scaling of PBH formation from negative curvature fluctuations (voids).
</p>
{: refdef}


This universality strongly suggests that PBHs formed from primordial voids are not exotic outliers, but belong to the same broader class of critical gravitational collapse phenomena.

---

### Why Primordial Voids Matter

Negative curvature perturbations are unavoidable in any inflationary scenario that enhances small-scale power. Our results therefore imply that primordial voids may contribute nontrivially to PBH abundances and associated signatures, including:

- additional channels for PBH production,
- modified sound-wave and gravitational-wave backgrounds,
- potential implications for PBH formation during non-standard epochs (e.g. early matter domination or reheating).

Accounting for primordial voids may thus be essential for a complete and consistent PBH phenomenology.

---

### Outlook

This work opens several directions for future research, including the effects of non-Gaussianities, broader power spectra, departures from spherical symmetry, and PBH formation during scalar-field–dominated eras. Understanding how void-dominated configurations interact with these ingredients will be crucial for building a unified picture of PBH formation in the early Universe.

 
If interested, stay tuned — more on primordial voids is coming soon.



<br/><br/>

#### References:

1.  Cristian Joana and Zi-Yan Yuwen ``Primordial black holes from Primordial Voids”, PRD. 2025 022, [arXiv:2510.11611](https://arxiv.org/abs/2510.11611)


[![Hits](https://hits.sh/cjoana.github.io/blogs/2025-12-23-PBHfromPVs.svg?label=read&color=ffffff&labelColor=ffffff)](https://hits.sh/cjoana.github.io/blogs/2025-12-23-PBHfromPVs/)
