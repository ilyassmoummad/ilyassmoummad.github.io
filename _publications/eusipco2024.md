---
title: "Mixture of Mixups for Multi-label Classification of Rare Anuran Sounds"
collection: publications
category: manuscripts
permalink: https://arxiv.org/pdf/2403.09598
date: 2024-08-01
venue: 'EUSIPCO'
# paperurl: 'https://www.mdpi.com/2072-6694/14/1/36'
---

Multi-label imbalanced classification poses a significant challenge in machine learning, particularly evident in bioacoustics where animal sounds often co-occur, and certain sounds are much less frequent than others. This paper focuses on the specific case of classifying anuran species sounds using the dataset AnuraSet, that contains both class imbalance and multi-label examples. To address these challenges, we introduce Mixture of Mixups (Mix2), a framework that leverages mixing regularization methods Mixup, Manifold Mixup, and MultiMix. Experimental results show that these methods, individually, may lead to suboptimal results; however, when applied randomly, with one selected at each training iteration, they prove effective in addressing the mentioned challenges, particularly for rare classes with few occurrences. Further analysis reveals that Mix2 is also proficient in classifying sounds across various levels of class co-occurrences.