---
title: 'EDITS: Modeling and Mitigating Data Bias for Graph Neural Networks'
authors:
- Yushun Dong
- Ninghao Liu
- Brian Jalaian
- Jundong Li
date: '2022-04-01'
publishDate: '2024-10-06T03:28:00.760458Z'
publication_types:
- paper-conference
publication: '*Proceedings of the ACM Web Conference 2022*'
doi: 10.1145/3485447.3512173
abstract: 'Graph Neural Networks (GNNs) have shown superior performance in analyzing
  attributed networks in various web-based applications such as social recommendation
  and web search. Nevertheless, in high-stake decision-making scenarios such as online
  fraud detection, there is an increasing societal concern that GNNs could make discriminatory
  decisions towards certain demographic groups. Despite recent explorations on fair
  GNNs, these works are tailored for a specific GNN model. However, myriads of GNN
  variants have been proposed for different applications, and it is costly to fine-tune
  existing debiasing algorithms for each specific GNN architecture. Different from
  existing works that debias GNN models, we aim to debias the input attributed network
  to achieve fairer GNNs through feeding GNNs with less biased data. Specifically,
  we propose novel definitions and metrics to measure the bias in an attributed network,
  which leads to the optimization objective to mitigate bias. We then develop a framework
  EDITS to mitigate the bias in attributed networks while maintaining the performance
  of GNNs in downstream tasks. EDITS works in a model-agnostic manner, i.e., it is
  independent of any specific GNN. Experiments demonstrate the validity of the proposed
  bias metrics and the superiority of EDITS on both bias mitigation and utility maintenance.
  Open-source implementation: https://github.com/yushundong/EDITS.'
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3485447.3512173
---
