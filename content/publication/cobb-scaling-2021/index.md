---
title: Scaling Hamiltonian Monte Carlo Inference for Bayesian Neural Networks with
  Symmetric Splitting
authors:
- Adam D. Cobb
- Brian Jalaian
date: '2021-12-01'
publishDate: '2024-10-06T03:28:00.653021Z'
publication_types:
- paper-conference
publication: '*Proceedings of the Thirty-Seventh Conference on Uncertainty in Artificial
  Intelligence*'
abstract: Hamiltonian Monte Carlo (HMC) is a Markov chain Monte Carlo (MCMC) approach
  that exhibits favourable exploration properties in high-dimensional models such
  as neural networks. Unfortunately, HMC has limited use in large-data regimes and
  little work has explored suitable approaches that aim to preserve the entire Hamiltonian.
  In our work, we introduce a new symmetric integration scheme for split HMC that
  does not rely on stochastic gradients. We show that our new formulation is more
  efficient than previous approaches and is easy to implement with a single GPU. As
  a result, we are able to perform full HMC over common deep learning architectures
  using entire data sets. In addition, when we compare with stochastic gradient MCMC,
  we show that our method achieves better performance in both accuracy and uncertainty
  quantification. Our approach demonstrates HMC as a feasible option when considering
  inference schemes for large-scale machine learning problems.
links:
- name: URL
  url: https://proceedings.mlr.press/v161/cobb21a.html
---
