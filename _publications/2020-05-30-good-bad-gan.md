---
title: "Semi-supervised Learning using Adversarial Training with Good and Bad Samples"
collection: publications
permalink: /publication/2020-05-30-good-bad-gan
excerpt: 'In this work, we investigate semi-supervised learning (SSL) for image classification using adversarial training. 
Previous results have illustrated that generative adversarial networks (GANs)...'
date: 2020-05-30
venue: 'Machine Vision and Application (Springer)'
citation: 'Wenyuan Li, Zichen Wang, Yuguang Yue, Jiayun Li, William Speier, Mingyuan Zhou and Corey Arnold (2020). 
&quot; Semi-supervised Learning using Adversarial Training with Good and Bad Samples .&quot; 
<i>Machine Vision and Application 31.6, 1-11.</i>.'
---
### Abstract:
In this work, we investigate semi-supervised learning (SSL) for image classification using adversarial training. 
Previous results have illustrated that generative
adversarial networks (GANs) can be used for multiple purposes. Triple-GAN,
which aims to jointly optimize model components by incorporating three players,
generates suitable image-label pairs to compensate for the lack of labeled data in
SSL with improved benchmark performance. Conversely, Bad (or complementary)
GAN, optimizes generation to produce complementary data-label pairs and force a
classifier’s decision boundary to lie between data manifolds. Although it generally
outperforms Triple-GAN, Bad GAN is highly sensitive to the amount of labeled
data used for training. Unifying these two approaches, we present unified-GAN
(UGAN), a novel framework that enables a classifier to simultaneously learn from
both good and bad samples through adversarial training. We perform extensive
experiments on various datasets and demonstrate that UGAN: 1) achieves stateof-the-art performance among other deep 
generative models, and 2) is robust to
variations in the amount of labeled data used for training.

[Download paper here](https://arxiv.org/pdf/1910.08540.pdf)