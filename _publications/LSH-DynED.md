---
title: "LSH-DynED: A Dynamic Ensemble Framework with LSH-Based Undersampling for Evolving Multi-Class Imbalanced Classification"
collection: publications
category: preprints
permalink: /publication/LSH-DynED
excerpt: 'Extends DynED with LSH-based undersampling of majority classes to classify multi-class imbalanced, non-stationary data streams.'
date: 2025-06-24
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2506.20041'
bibtexurl: 'https://soheilabadifard.github.io/files/LSH-DynED.bib'
citation: 'Abadifard, S., & Can, F. (2025). LSH-DynED: A Dynamic Ensemble Framework with LSH-Based Undersampling for Evolving Multi-Class Imbalanced Classification. arXiv preprint arXiv:2506.20041.'
---

**Abstract.** The classification of imbalanced data streams, which have unequal class distributions, is a key difficulty in machine learning, especially when dealing with multiple classes. While binary imbalanced data stream classification tasks have received considerable attention, only a few studies have focused on multi-class imbalanced data streams. Effectively managing the dynamic imbalance ratio is a key challenge in this domain. This study introduces a novel, robust, and resilient approach to address these challenges by integrating Locality Sensitive Hashing with Random Hyperplane Projections (LSH-RHP) into the Dynamic Ensemble Diversification (DynED) framework. To the best of our knowledge, we present the first application of LSH-RHP for undersampling in the context of imbalanced non-stationary data streams. The proposed method undersamples the majority classes by utilizing LSH-RHP, provides a balanced training set, and improves the ensemble's prediction performance. We conduct comprehensive experiments on 23 real-world and ten semi-synthetic datasets and compare LSH-DynED with 15 state-of-the-art methods. The results reveal that LSH-DynED outperforms other approaches in terms of both Kappa and mG-Mean effectiveness measures, demonstrating its capability in dealing with multi-class imbalanced non-stationary data streams. Notably, LSH-DynED performs well in large-scale, high-dimensional datasets with considerable class imbalances and demonstrates adaptation and robustness in real-world circumstances. To motivate our design, we review existing methods for imbalanced data streams, outline key challenges, and offer guidance for future work. For the reproducibility of our results, we have made our implementation available on GitHub.

**Code:** [github.com/soheilabadifard/LSH-DynED](https://github.com/soheilabadifard/LSH-DynED)
