---
title: Can strong structural encoding reduce the importance of Message Passing?
abstract: The most prevalent class of neural networks operating on graphs are message
  passing neural networks (MPNNs), in which the representation of a node is updated
  iteratively by aggregating information in the 1-hop neighborhood. Since this paradigm
  for computing node embeddings may prevent the model from learning coarse topological
  structures, the initial features are often augmented with structural information
  of the graph, typically in the form of Laplacian eigenvectors or Random Walk transition
  probabilities. In this work, we explore the contribution of message passing when
  strong structural encodings are provided. We introduce a novel way of modeling the
  interaction between feature and structural information based on their tensor product
  rather than the standard concatenation. The choice of interaction is compared in
  common scenarios and in settings where the capacity of the message-passing layer
  is severely reduced and ultimately the message-passing phase is removed altogether.
  Our results indicate that using tensor-based encodings is always at least on par
  with the concatenation-based encoding and that it makes the model much more robust
  when the message passing layers are removed, on some tasks incurring almost no drop
  in performance. This suggests that the importance of message passing is limited
  when the model can construct strong structural encodings.
openreview: mbgod4sDia
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: eijkelboom23a
month: 0
tex_title: Can strong structural encoding reduce the importance of Message Passing?
firstpage: 278
lastpage: 288
page: 278-288
order: 278
cycles: false
bibtex_author: Eijkelboom, Floor and Bekkers, Erik J and Bronstein, Michael M. and
  Giovanni, Francesco Di
author:
- given: Floor
  family: Eijkelboom
- given: Erik J
  family: Bekkers
- given: Michael M.
  family: Bronstein
- given: Francesco Di
  family: Giovanni
date: 2023-09-27
address: 
container-title: Proceedings of 2nd Annual Workshop on Topology, Algebra, and Geometry
  in Machine Learning (TAG-ML)
volume: '221'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 9
  - 27
pdf: https://proceedings.mlr.press/v221/eijkelboom23a/eijkelboom23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
