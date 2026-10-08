---
title: "Revisiting Hypernetwork in Model Heterogeneous Personalized Federated Learning"
collection: publications
category: conferences
permalink: /publication/2026-09-01-revisiting-hypernetwork-mh-pfl
excerpt: 'We revisit hypernetworks for model-heterogeneous personalized federated learning, proposing MH-pFedHN and MH-pFedHNGD — no external data required, and client model architectures stay undisclosed.'
date: 2026-09-01
venue: 'International Joint Conference on Artificial Intelligence (IJCAI)'
paperurl: 'https://doi.org/10.24963/ijcai.2026/589'
citation: 'Chen Zhang, Husheng Li, Xiang Liu, Linshan Jiang, Danxin Wang. (2026). &quot;Revisiting Hypernetwork in Model Heterogeneous Personalized Federated Learning.&quot; <i>Proceedings of the Thirty-Fifth International Joint Conference on Artificial Intelligence (IJCAI-26)</i>, 5288&ndash;5296. DOI: 10.24963/ijcai.2026/589'
---

**Abstract**

Recent personalized federated learning research focuses on heterogeneous models across clients. However, existing methods often rely on external data, model decoupling, and partial learning, which makes them sensitive to settings. In contrast, we revisit hypernetworks and leverage their strong generalization ability to propose the first practical method for personalized federated learning. We first propose a model heterogeneous personalized federated learning framework based on hypernetworks, MH-pFedHN, which quantifies clients with different architectures using customized embedding vectors and then generates client-specific model parameters through a server-side hypernetwork. Besides the shared feature extractor, our hypernetwork consists of multiple heads, where clients with similar numbers of parameters are assigned the same number of customized embedding vectors and consequently share the same head. This design enables knowledge sharing across different architectures and reduces the computation of parameter generation. To further enhance the hypernetwork's learning and generalization, we propose MH-pFedHNGD, which introduces a lightweight yet effective plug-in global model. Our framework requires no external data and does not disclose client model architectures, thereby effectively ensuring security and demonstrating great potential. Experiments across various models and tasks demonstrate that our approach outperforms standard baselines and exhibits strong generalization performance.

**Code**: [github.com/DangDang1895/MH-pFL](https://github.com/DangDang1895/MH-pFL)
