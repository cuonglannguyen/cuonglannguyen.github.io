---
title: "Provably Improving Generalization of Few-Shot Models with Synthetic Data"
collection: publications
category: conferences
permalink: /publication/2025-05-01-ICML-Provably
excerpt: 'The paper provides a theoretical-guided method for few-shot learning.'
date: 2025-05-01
venue: 'International Conference on Machine Learning (ICML)'
slidesurl: 'https://cuonglannguyen.github.io/files/ICML2025_presentation.pdf'
paperurl: 'https://openreview.net/pdf?id=L6U7nYc4ah'
---

Abstract
------

Few-shot image classification remains challenging due to the scarcity of labeled training examples. Augmenting them with synthetic data has emerged as a promising way to alleviate this issue, but models trained on synthetic samples often face performance degradation due to the inherent gap between real and synthetic distributions. To address this limitation, we develop a theoretical framework that quantifies the impact of such distribution discrepancies on supervised learning, specifically in the context of image classification. More importantly, our framework suggests practical ways to generate good synthetic samples and to train a predictor with high generalization ability. Building upon this framework, we propose a novel theoretical-based algorithm that integrates prototype learning to optimize both data partitioning and model training, effectively bridging the gap between real few-shot data and synthetic data. Extensive experiments results show that our approach demonstrates superior performance compared to state-of-the-art methods, outperforming them across multiple datasets. 

Our code can be found [here](https://github.com/Fsoft-AIC/ProtoAug) and our slides can be found [here](https://cuonglannguyen.github.io/files/ICML2025_presentation.pdf)