---
title: "Regularized Contrastive Pre-training for Few-shot Bioacoustic Sound Detection"
collection: publications
category: manuscripts
permalink: https://arxiv.org/pdf/2309.08971
date: 2024-04
venue: 'ICASSP'
# paperurl: 'https://www.mdpi.com/2072-6694/14/1/36'
---

Bioacoustic sound event detection allows for better understanding of animal behavior and for better monitoring biodiversity using audio. Deep learning systems can help achieve this goal. However, it is difficult to acquire sufficient annotated data to train these systems from scratch. To address this limitation, the Detection and Classification of Acoustic Scenes and Events (DCASE) community has recasted the problem within the framework of few-shot learning and organize an annual challenge for learning to detect animal sounds from only five annotated examples. In our study, we introduce a regularization to supervised contrastive loss, to learn non redundant features that exhibit effective transferability to few-shot tasks involving the detection of animal sounds not encountered during the training phase. Our method achieves a high F-score of 61.52%±0.48 when no feature adaptation is applied, and an F-score of 68.19%±0.75 when we further adapt the learned features for each new target task. This work aims to lower the entry bar to few-shot bioacoustic sound event detection by proposing a simple and yet effective framework for this task, and by providing open-source code.