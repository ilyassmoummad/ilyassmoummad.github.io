---
title: "Pretraining Respiratory Sound Representations using Metadata and Contrastive Learning"
collection: publications
category: manuscripts
permalink: https://arxiv.org/pdf/2210.16192
date: 2023-10
venue: 'WASPAA'
# paperurl: 'https://www.mdpi.com/2072-6694/14/1/36'
---

Methods based on supervised learning using annotations in an endto-end fashion have been the state-of-the-art for classification problems. However, they may be limited in their generalization capability, especially in the low data regime. In this study, we address this issue using supervised contrastive learning combined with available metadata to solve multiple pretext tasks that learn a good representation of data. We apply our approach on respiratory sound classification. This task is suited for this setting as demographic information such as sex and age are correlated with presence of lung diseases, and learning a system that implicitly encode this information may better detect anomalies. Supervised contrastive learning is a paradigm that learns similar representations to samples sharing the same class labels and dissimilar representations to samples with different class labels. The feature extractor learned using this paradigm extract useful features from the data, and we show that it outperforms cross-entropy in classifying respiratory anomalies in two different datasets. We also show that learning representations using only metadata, without class labels, obtains similar performance as using cross entropy with those labels only. In addition, when combining class labels with metadata using multiple supervised contrastive learning, an extension of supervised contrastive learning solving an additional task of grouping patients within the same sex and age group, more informative features are learned. This work suggests the potential of using multiple metadata sources in supervised contrastive settings, in particular in settings with class imbalance and few data.