---
title: Decentralized Bayesian learning with Metropolis-adjusted Hamiltonian Monte
  Carlo
authors:
- Vyacheslav Kungurtsev
- Adam Cobb
- Tara Javidi
- Brian Jalaian
date: '2023-08-01'
publishDate: '2024-10-06T03:28:00.732229Z'
publication_types:
- article-journal
publication: '*Machine Learning*'
doi: 10.1007/s10994-023-06345-6
abstract: Federated learning performed by a decentralized networks of agents is becoming
  increasingly important with the prevalence of embedded software on autonomous devices.
  Bayesian approaches to learning benefit from offering more information as to the
  uncertainty of a random quantity, and Langevin and Hamiltonian methods are effective
  at realizing sampling from an uncertain distribution with large parameter dimensions.
  Such methods have only recently appeared in the decentralized setting, and either
  exclusively use stochastic gradient Langevin and Hamiltonian Monte Carlo approaches
  that require a diminishing stepsize to asymptotically sample from the posterior
  and are known in practice to characterize uncertainty less faithfully than constant
  step-size methods with a Metropolis adjustment, or assume strong convexity properties
  of the potential function. We present the first approach to incorporating constant
  stepsize Metropolis-adjusted HMC in the decentralized sampling framework, show theoretical
  guarantees for consensus and probability distance to the posterior stationary distribution,
  and demonstrate their effectiveness numerically on standard real world problems,
  including decentralized learning of neural networks which is known to be highly
  non-convex.
tags:
- Decentralized learning
- Federated learning
- HMC
- Monte Carlo
links:
- name: URL
  url: https://doi.org/10.1007/s10994-023-06345-6
---
