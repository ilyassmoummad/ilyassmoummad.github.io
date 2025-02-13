---
title: "Domain-Invariant Representation Learning of Bird Sounds"
collection: publications
category: manuscripts
permalink: https://arxiv.org/pdf/2409.08589
date: 2024-10-01
venue: 'arXiv'
# paperurl: 'https://www.mdpi.com/2072-6694/14/1/36'
---

Passive acoustic monitoring (PAM) is crucial for bioacoustic research, enabling non-invasive species tracking and biodiversity monitoring. Citizen science platforms like Xeno-Canto provide large annotated datasets from focal recordings, where the target species is intentionally recorded. However, PAM requires monitoring in passive soundscapes, creating a domain shift between focal and passive recordings, which challenges deep learning models trained on focal recordings. To address this, we leverage supervised contrastive learning to improve domain generalization in bird sound classification, enforcing domain invariance across same-class examples from different domains. We also propose ProtoCLR (Prototypical Contrastive Learning of Representations), which reduces the computational complexity of the SupCon loss by comparing examples to class prototypes instead of pairwise comparisons. Additionally, we present a new few-shot classification evaluation based on BIRB, a large-scale bird sound benchmark to evaluate bioacoustic pre-trained models.