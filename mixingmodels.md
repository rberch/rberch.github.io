---
layout: page
title: Bayesian mixing models
subtitle: Estimating diet
---

Mixing models are statistical tools that use biotracers to estimate contributions of sources to a mixture, for example:
  - Diet in ecology (sources = prey, mixture = consumers, biotracers = stable isotopes, fatty acids)
  - Movement in ecology (sources = regions, mixture = animals that can move between regions)
  - Sediments in river systems (sources = upstream land uses, mixture = downstream sediment)

In addition to developing open-source software to construct and run mixing models ([MixSIAR](https://brianstock.github.io/mixsiar)), I have worked on the following projects:

### An improved mixing model error structure

In the course of developing MixSIAR, Brice Semmens and I realized that the ecological assumptions of existing mixing models--as encoded in their error structures--were unrealistic. We came up with a new error parameterization based on more realistic assumptions about the predation process--how biotracer values in prey should relate to biotracer values in consumers. We showed that this new error structure outperformed existing models, as well as implicitly providing an estimate of consumption. This "multiplicative error" term is included as an option in [MixSIAR](https://brianstock.github.io/mixsiar).

**Stock BC** and Semmens BX. Unifying error structures in commonly used biotracer mixing models. *Ecology* 97(10): 2562-2569. [pdf](/pdf/Stock_Semmens_2016_unifying_error_structures.pdf)

### "Smasher" mantis shrimp: generalist diet despite specialized morphology

Smashing mantis shrimp have a hammer-like club (modified mouthparts) that delivers one of the fastest and most powerful strikes in the animal kingdom. This specialized morphology allows them to break open hard-shelled prey like clams and snails. Through feeding trials and stable isotope mixing models, we found that smashing mantis shrimp eat a generalist diet including fish--despite being physically specialized for consuming hard-shelled prey. One neat aspect of this study is that we showed that this result was robust across several alternative priors in the Bayesian mixing model (i.e. alternative a priori expectations).

deVries MS, **Stock BC**, Christy JH, Goldsmith GR, and Dawson TE. Specialized morphology corresponds to a generalist diet: linking form and function in smashing mantis shrimp crustaceans. *Oecologia* 128(2): 429–442. [pdf](/pdf/deVries_2016_mantis_shrimp.pdf)