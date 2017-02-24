---
title: 'Convergent Learning: Do different neural networks learn the same representations?'
abstract: 'Recent successes in training large, deep neural networks (DNNs) have prompted
  active investigation into the underlying representations learned on their intermediate
  layers. Such research is difficult because it requires making sense of non-linear
  computations performed by millions of learned parameters. However, despite the difficulty,
  such research is valuable because it increases our ability to understand current
  models and training algorithms and thus create improved versions of them. We argue
  for the value of investigating whether neural networks exhibit what we call convergent
  learning, which is when separately trained DNNs learn features that converge to
  span similar spaces. We further begin research into this question by introducing
  two techniques to approximately align neurons from two networks: a bipartite matching
  approach that makes one-to-one assignments between neurons and a spectral clustering
  approach that finds many-to-many mappings. Our initial approach to answering this
  question reveals many interesting, previously unknown properties of neural networks,
  and we argue that future research into the question of convergent learning will
  yield many more. The insights described here include (1) that some features are
  learned reliably in multiple networks, yet other features are not consistently learned;
  and (2) that units learn to span low-dimensional subspaces and, while these subspaces
  are common to multiple networks, the specific basis vectors learned are not; (3)
  that the  average activation values of neurons vary considerably within a network,
  yet the mean activation values across different networks converge to an almost identical
  distribution.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: li15convergent
month: 0
firstpage: 196
lastpage: 212
page: 196-212
sections: 
author:
- given: Yixuan
  family: Li
- given: Jason
  family: Yosinski
- given: Jeff
  family: Clune
- given: Hod
  family: Lipson
- given: John
  family: Hopcroft
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
pdf: http://proceedings.mlr.press/v44/li15convergent.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
