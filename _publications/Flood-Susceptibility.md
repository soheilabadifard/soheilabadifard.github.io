---
title: "Infrastructure-Aware Urban Flood Susceptibility from Multi-Event High-Water Marks: A Multi-Model Comparison"
collection: publications
category: preprints
permalink: /publication/Flood-Susceptibility
excerpt: 'Maps urban flood susceptibility in Manhattan, Kansas, from surveyed high-water marks and stormwater infrastructure, comparing MaxEnt with five supervised classifiers.'
date: 2026-10-08
venue: 'SSRN'
paperurl: 'https://doi.org/10.2139/ssrn.7583892'
bibtexurl: 'https://soheilabadifard.github.io/files/Flood-Susceptibility.bib'
citation: 'Monavarian, A., Abadifard, S., Heatherman, W. J., McGinty, H., & Sharda, V. (2026). Infrastructure-Aware Urban Flood Susceptibility from Multi-Event High-Water Marks: A Multi-Model Comparison. SSRN preprint. https://doi.org/10.2139/ssrn.7583892'
---

**Abstract.** Urban flooding is driven by pluvial and infrastructure-mediated processes, yet flood susceptibility models typically rely on terrain-centric predictors and on flood inventories or remotely sensed extents. This study evaluates two underused inputs, high-water marks surveyed by municipal crews as presence observations and a city stormwater geodatabase as a source of infrastructure predictors, such as outfall proximity. Using 277 presence points from 11 flood events (2007–2024) in Manhattan, Kansas, and 17 predictors at 10 m resolution, we fitted a maximum-entropy model, compared it with five supervised classifiers, and assessed generalization by spatial-block and leave-one-event-out cross-validation. Distance to the nearest outfall was the strongest single predictor (area under the receiver-operating-characteristic curve, AUC = 0.915). Spatial-block and event cross-validation gave AUCs of 0.935 and 0.952, respectively, against 0.983 for a random split, and no model differed significantly from another after Holm correction. After controlling for road access and four terrain and land-cover confounders, outfall proximity still added 0.025 AUC. The regulatory 1% floodplain captured 40% of held-out marks while covering 17% of the study area, whereas the model captured 95% within 7%. Refitted on marks outside the floodplain, distance to outfall alone still reached AUC = 0.920, so the association is not limited to riverine flooding. An exploratory socioeconomic overlay found no significant association after Holm correction. Proximity to stormwater outfalls was the strongest available correlate of observed flooding. Because these two inputs are municipal records and the code is openly available, the workflow can be adapted to other cities that hold them.

**Code:** [github.com/Alireza-Monavarian/Urban-Flood-Susceptibility-Mapping](https://github.com/Alireza-Monavarian/Urban-Flood-Susceptibility-Mapping)
