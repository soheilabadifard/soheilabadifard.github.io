---
title: "DynED: Dynamic Ensemble Diversification in Data Stream Classification"
collection: publications
category: conferences
permalink: /publication/DynED
excerpt: 'An ensemble method for data stream classification that uses Maximal Marginal Relevance to balance the accuracy and diversity of its components under concept drift.'
date: 2023-10-22
venue: 'CIKM'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3583780.3615266'
bibtexurl: 'https://soheilabadifard.github.io/files/DynED.bib'
citation: 'Soheil Abadifard, Sepehr Bakhshi, Sanaz Gheibuni, and Fazli Can. 2023. DynED: Dynamic Ensemble Diversification in Data Stream Classification. In Proceedings of the 32nd ACM International Conference on Information and Knowledge Management (CIKM 2023). Association for Computing Machinery, New York, NY, USA, 3707–3711. https://doi.org/10.1145/3583780.3615266'
---

**Abstract.** Ensemble methods are commonly used in classification due to their remarkable performance. Achieving high accuracy in a data stream environment is a challenging task considering disruptive changes in the data distribution, also known as concept drift. A greater diversity of ensemble components is known to enhance prediction accuracy in such settings. Despite the diversity of components within an ensemble, not all contribute as expected to its overall performance. This necessitates a method for selecting components that exhibit high performance and diversity. We present a novel ensemble construction and maintenance approach based on MMR (Maximal Marginal Relevance) that dynamically combines the diversity and prediction accuracy of components during the process of structuring an ensemble. The experimental results on both four real and 11 synthetic datasets demonstrate that the proposed approach (DynED) provides a higher average mean accuracy compared to the five state-of-the-art baselines.

**Poster:** presented at [CIKM 2023](/talks/2023-10-21-cikm-poster) in Birmingham, UK.

**Code:** [github.com/soheilabadifard/DynED](https://github.com/soheilabadifard/DynED)
