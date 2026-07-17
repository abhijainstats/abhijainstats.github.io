---
title: "Modeling health and well-being measures using ZIP code spatial neighborhood patterns"
subtitle: ""
excerpt: "Spatially informed regression models that generate ZCTA-level well-being rankings by borrowing information across neighboring ZIP codes."
date: 2024-04-03
author: "Abhi Jain"
featured: true
draft: false
layout: single
---

Individual-level assessment of health and well-being permits analysis of community well-being and health risk evaluations across several dimensions of health. It also enables comparison and rankings of reported health and well-being for large geographical areas such as states, metropolitan areas, and counties. However, there is large variation in reported well-being within such large spatial units underscoring the importance of analyzing well-being at more granular levels, such as ZIP codes. In this paper, we address this problem by modeling well-being data to generate ZIP code tabulation area (ZCTA)-level rankings through spatially informed statistical modeling. We build regression models for individual-level overall well-being index and scores from five subscales (Physical, Financial, Social, Community, Purpose) using individual-level demographic characteristics as predictors while including a ZCTA-level spatial effect. The ZCTA neighborhood information is incorporated by using a graph Laplacian matrix; this enables estimation of the effect of a ZCTA on well-being using individual-level data from that ZCTA as well as by borrowing information from neighboring ZCTAs. We deploy our model on well-being data for the U.S. states of Massachusetts and Georgia. We find that our model can capture the effects of demographic features while also offering spatial effect estimates for all ZCTAs, including ones with no observations, under certain conditions. These spatial effect estimates provide community health and well-being rankings of ZCTAs, and our method can be deployed more generally to model other outcomes that are spatially dependent as well as data from other states or groups of states.

{{< figure src="featured.webp" alt="Estimated ZCTA-level spatial effects for the overall well-being index and five subscales in Massachusetts" caption="Estimated ZCTA-level effects for the overall well-being index and each of the five subscales, Massachusetts." >}}

{{< figure src="fig2.webp" alt="ZCTA quintile rankings for the overall well-being index and five subscales in Massachusetts" caption="ZCTA quintile rankings derived from the estimated spatial effects, Massachusetts." >}}

You can access the full paper [here](https://www.nature.com/articles/s41598-024-58157-w).
