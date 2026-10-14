---
title: "Dynamic Ensemble Diversification and Hash-Based Undersampling for the Classification of Multi-Class Imbalanced Data Streams"
collection: publications
category: theses
permalink: /publication/MSc-Thesis
excerpt: 'M.Sc. thesis, Bilkent University. Advisor: Prof. Fazlı Can.'
date: 2024-07-01
venue: 'Bilkent University'
paperurl: 'https://hdl.handle.net/11693/115735'
bibtexurl: 'https://soheilabadifard.github.io/files/MSc-Thesis.bib'
citation: 'Abadifard, S. (2024). Dynamic Ensemble Diversification and Hash-Based Undersampling for the Classification of Multi-Class Imbalanced Data Streams [Master''s thesis, Bilkent University]. https://hdl.handle.net/11693/115735'
---

**Abstract.** The classification of imbalanced data streams, which have unequal class distributions, is a key difficulty in machine learning, especially when dealing with multiple classes and concept drift. While binary imbalanced data stream classification tasks have received considerable attention, only a few studies have focused on multi-class imbalanced data streams. Additionally, dealing with the dynamic imbalance ratio is of great importance. This study introduces a novel, robust, and resilient approach to address these challenges by integrating Locality Sensitive Hashing with Random Hyperplane Projections (LSH-RHP) into the Dynamic Ensemble Diversification (DynED) framework. To the best of our knowledge, we present the first application of LSH-RHP for undersampling in the context of imbalanced non-stationary data streams. The proposed method, undersamples majority classes by utilizing LSH-RHP, provides a balanced training set, and improves the ensemble’s prediction accuracy. We conduct comprehensive experiments on 23 real-world and ten semi-synthetic datasets and compare LSH-DynED with 15 state-of-the-art methods. The results reveal that LSH-DynED outperforms other approaches in terms of both Kappa and mG-Mean effectiveness measures, demonstrating its capability in dealing with multi-class imbalanced non-stationary data streams. Notably, LSH-DynED performs well in large-scale, high-dimensional datasets with considerable class imbalances and demonstrates adaptation and robustness in real-world circumstances. For the reproducibility of our results, we have made our implementation available on GitHub.

The work in this thesis is also published as [DynED](/publication/DynED) (CIKM 2023) and [LSH-DynED](/publication/LSH-DynED) (arXiv preprint).
