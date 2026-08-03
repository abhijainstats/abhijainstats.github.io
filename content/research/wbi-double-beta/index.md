---
title: "Modeling bounded well-being indices using Bayesian double generalized beta regression with spatial and temporal borrowing"
subtitle: ""
excerpt: "A Bayesian double generalized beta regression framework that borrows spatial and temporal information to model bounded well-being indices at the ZCTA level."
date: 2026-03-01
author: "Abhi Jain"
featured: true
draft: false
layout: single
---

Health and well-being indices are widely used to assess population health outcomes and inform policy decisions. Individual-level assessment of well-being can be used to develop community-level indices that measure wellness for different geographical units. While many existing indices operate at coarse geographic levels such as counties or states, finer spatial resolution can offer more actionable insights. We present a novel Bayesian double generalized beta regression framework to model a bounded individual-level well-being index (WBI) using annual survey data collected from 2021 to 2023 in Massachusetts. Although survey respondents may differ across years, responses are geotagged to ZIP Code Tabulation Areas (ZCTAs), enabling the integration of both spatial and temporal information. Our framework incorporates spatial dependencies via a graph Laplacian matrix that encodes driving time-based ZCTA neighborhood structure, and leverages temporal borrowing by using posterior spatial effect estimates from one year to inform priors in the next. This dual-borrowing strategy within a Bayesian double generalized beta regression framework enhances estimation precision, particularly in areas with sparse data, and improves inference for smaller geographic units. We demonstrate the utility of our method through a realistic simulation study that highlights improved estimation when borrowing spatial and temporal information. In the real data analysis, we model individual-level well-being for residents in Massachusetts and find that income, education status, and marital status are most associated with WBI. Additionally, we observe that ZCTAs in Western Massachusetts, Cape Cod, and those near Boston perform best with the highest spatial effects.

This work was awarded the 2026 ENAR Distinguished Paper Award and a copy of the presentation slides can be found [here](/slides/enar2026.pdf). Additionally, details on the software to implement this model can be found [here](/software/bayesbadger/).
