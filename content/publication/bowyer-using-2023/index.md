---
title: Using autodiff to estimate posterior moments, marginals and samples
authors:
- Sam Bowyer
- Thomas Heap
- Laurence Aitchison
date: '2023-10-01'
publishDate: '2024-04-05T15:52:24.282199Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'Importance sampling is a popular technique in Bayesian inference: by reweighting
  samples drawn from a proposal distribution we are able to obtain samples and moment
  estimates from a Bayesian posterior over some n latent variables. Recent work, however,
  indicates that importance sampling scales poorly — in order to accurately approximate
  the true posterior, the required number of importance samples grows is exponential
  in the number of latent variables (Chatterjee and Diaconis 2018). Massively parallel
  importance sampling works around this issue by drawing K samples for each of the
  n latent variables and reasoning about all Kn combinations of latent samples. In
  principle, we can reason efficiently over Kn combinations of samples by exploiting
  conditional independencies in the generative model. However, in practice this requires
  complex algorithms that traverse backwards through the graphical model, and we need
  separate backward traversals for each computation (posterior expectations, marginals
  and samples). Our contribution is to exploit the source term trick from physics
  to entirely avoid the need to hand-write backward traversals. Instead, we demonstrate
  how to simply and easily compute all the required quantities — posterior expectations,
  marginals and samples — by differentiating through a slightly modified marginal
  likelihood estimator.'
tags:
- Mathematics - Statistics Theory
- Statistics - Computation
links:
- name: URL
  url: http://arxiv.org/abs/2310.17374
---
