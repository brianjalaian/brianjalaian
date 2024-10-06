---
title: A Real-Time Solution for Underlay Coexistence with Channel Uncertainty
authors:
- S Li
- Y Huang
- C Li
- B Jalaian
- S Russell
- Y T Hou
- W Lou
- B MacCall
date: '2019-12-01'
publishDate: '2024-10-06T03:28:00.603736Z'
publication_types:
- paper-conference
publication: '*2019 IEEE Global Communications Conference (GLOBECOM)*'
doi: 10.1109/GLOBECOM38437.2019.9014147
abstract: Underlay coexistence is an effective mechanism to improve spectrum effïciency
  by having picocells coexist with macrocell on the same spectrum. Due to a lack of
  cooperation between the primary users (PUs) in the macrocell and secondary users
  (SUs) in the picocell, it is impossible to have complete knowledge of channel gains
  between them. Under such circumstance, chance-constrained programming (CCP) is shown
  to be the ideal optimization tool to address such uncertainty. However, solutions
  to CCP are computationally intensive and cannot meet 5G's timing requirement. To
  address this problem, we propose a novel scheduler called GUC (stands for GPU-based
  Underlay Coexistence) to find an approximate solution to CCP in real-time. The essence
  of GUC is to decompose the original optimization problem into a large number of
  small problems that are suitable for parallel computation on GPU platforms. Through
  extensive experiments, we show that GUC reduces the scheduling computation time
  by at least 10,000 times comparing to commercial solvers (on CPU) while achieving
  an average of 90% optimality.
tags:
- 5G mobile communication
- Graphics processing units
---
