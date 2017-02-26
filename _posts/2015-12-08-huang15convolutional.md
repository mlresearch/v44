---
title: Convolutional Dictionary Learning through Tensor Factorization
abstract: Tensor methods have emerged as a powerful paradigm for consistent learning
  of many latent variable models such as topic models,  independent component analysis
  and dictionary learning. Model parameters are estimated via CP decomposition of
  the observed higher order input moments. In this paper, we extend tensor decomposition
  framework to models with invariances, such as convolutional dictionary models.    Our
  tensor decomposition algorithm is based on the popular alternating least squares
  (ALS) method, but with additional shift invariance constraints on the factors. We
  demonstrate that each ALS update can be computed efficiently using simple operations
  such as fast Fourier transforms and matrix multiplications. Our algorithm converges
  to models with better reconstruction error and is much faster, compared to the popular
  alternating minimization heuristic, where the filters  and activation maps are alternately
  updated.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: huang15convolutional
month: 0
tex_title: Convolutional Dictionary Learning through Tensor Factorization
firstpage: 116
lastpage: 129
page: 116-129
order: 116
cycles: false
author:
- given: Furong
  family: Huang
- given: Animashree
  family: Anandkumar
date: 2015-12-08
address: Montreal, Canada
publisher: PMLR
container-title: 'Proceedings of the 1st International Workshop on Feature Extraction:
  Modern Questions and Challenges at NIPS 2015'
volume: '44'
genre: inproceedings
issued:
  date-parts:
  - 2015
  - 12
  - 8
pdf: http://proceedings.mlr.press/v44/huang15convolutional.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
