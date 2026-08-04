---
title: "Bayesian causal forests for estimating heterogeneous effects with joint treatments and interference"
subtitle: ""
excerpt: "A joint treatment Bayesian Causal Forest (BCF) that estimates direct and indirect effects of community-level exposures under interference and heterogeneity."
date: 2026-08-01
author: "Abhi Jain"
featured: true
draft: false
layout: single
---

Estimating the causal effect of community exposures, such as county or ZIP Code access to healthy food on health outcomes, is methodologically challenging because of 1) interference – the exposure in one community can affect health outcomes in nearby communities and 2) heterogeneous effects – the magnitude and direction of the effect of the exposure can vary by community characteristics such as socioeconomic status. We propose a new method, joint treatment Bayesian Causal Forest (BCF), to estimate the direct and indirect effects of community-level exposures. The method extends BCF models to settings with interference and addresses heterogeneous effects by incorporating multiple moderating functions for unit-level and neighborhood-level exposure, and their interaction. In an extensive simulation study, our new method accurately recovers both the average and individual direct and indirect effects under different data generating mechanisms and sample sizes. Finally, we apply our approach to estimate the effect of the presence of at least one healthy food retailer on obesity rates using cross-sectional ZIP Code-level data from Texas. Our findings suggest a small negative effect of living near a healthy food retailer on obesity rate, with evidence of stronger heterogeneous effects along socioeconomic lines.

{{< figure src="featured.png" align="center" alt="Scatterplots of estimated direct effects for Texas ZCTAs by income and SNAP percentile" caption="Scatterplots of $\widehat{DE}(\tilde{A}=1)$ for ZCTAs in Texas by different levels of median household income and percent SNAP beneficiaries. The x-axis of each plot is the percentile value of each covariate and the red line is the loess curve." >}}

This work was presented at the "Bayesian Tree-Based Models and BART Methods" session at JSM 2026 and a copy of the presentation slides are [here](/slides/jsm2026.pdf).
