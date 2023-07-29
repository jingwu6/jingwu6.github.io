---
title: "Hallucination Improves the Performance of Unsupervised Visual Representation Learning"
permalink: /publication/2009-10-01-paper-title-number-1
date: 2023-8-1
excerpt: '**Jing Wu**, Naira Hovakimyan,Jennifer Hobbs'
venue: 'International Conference on Computer Vision(ICCV)'
paperurl: 'https://arxiv.org/pdf/2307.12168.pdf'
---

**Abstract** \
Contrastive learning models based on Siamese structure have demonstrated remarkable performance in selfsupervised learning. Such a success of contrastive learning relies on two conditions, a sufficient number of positive pairs and adequate variations between them. If the
conditions are not met, these frameworks will lack semantic contrast and be fragile on overfitting. To address these
two issues, we propose Hallucinator that could efficiently
generate additional positive samples for further contrast.
The Hallucinator is differentiable and creates new data in
the feature space. Thus, it is optimized directly with the
pre-training task and introduces nearly negligible computation. Moreover, we reduce the mutual information of hallucinated pairs and smooth them through non-linear operations. This process helps avoid over-confident contrastive
learning models during the training and achieves more
transformation-invariant feature embeddings. Remarkably,
we empirically prove that the proposed Hallucinator generalizes well to various contrastive learning models, including MoCoV1&V2, SimCLR and SimSiam. Under the linear
classification protocol, a stable accuracy gain is achieved,
ranging from 0.3% to 3.0% on CIFAR10&100, Tiny ImageNet, STL-10 and ImageNet. The improvement is also observed in transferring pre-train encoders to the downstream
tasks, including object detection and segmentation.
