---
title: 'The Methodological Pitfall of Dataset-Driven Research on Deep Learning: An
  IoT Example'
authors:
- Tianshi Wang
- Denizhan Kara
- Jinyang Li
- Shengzhong Liu
- Tarek Abdelzaher
- Brian Jalaian
date: '2022-11-01'
publishDate: '2024-10-06T03:28:00.681421Z'
publication_types:
- paper-conference
publication: '*MILCOM 2022 - 2022 IEEE Military Communications Conference (MILCOM)*'
doi: 10.1109/MILCOM55135.2022.10017612
abstract: In this paper, we highlight a dangerous pitfall in the state-of-the-art
  evaluation methodology of deep learning algorithms. It results in deceptively good
  evaluation outcomes on test datasets, whereas the underlying algorithms remain prone
  to catastrophic failure in practice. We illustrate the pitfall in the context of
  an Internet-of-Things (IoT) application example and show that it occurs despite
  the use of cross-validation that breaks down the data into separate training, validation,
  and testing sets. The pitfall is illustrated by designing two target detection and
  classification algorithms. One is based on a recently proposed neural network architecture
  for embedded AI, and the other is based on a traditional machine learning approach
  with domain-inspired feature engineering. The neural network approach outperforms
  the traditional one on test data. Yet, it fails in deployment. The mechanics behind
  the failure are explained and linked to the way the algorithms are trained. Suggestions
  are presented to avoid the pitfall. The paper is a “call to arms” to improve the
  evaluation methodology of machine learning algorithms for mission-critical systems.
tags:
- Deep learning
- Training
- Machine learning algorithms
- Neural networks
- Feedback loop
- Military communication
- Mission critical systems
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10017612
---
