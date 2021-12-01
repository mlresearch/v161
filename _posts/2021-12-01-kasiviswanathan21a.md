---
title: SGD with low-dimensional gradients with applications to private and distributed
  learning
abstract: In this paper, we consider constrained optimization problems subject to
  a convex set C Stochastic gradient descent (SGD) is a simple and popular stochastic
  optimization algorithm that has been the workhorse of machine learning for many
  years. We show a new and surprising fact about SGD, in that depending on the constraint
  set C, one can operate SGD with much lower-dimensional stochastic gradients without
  affecting its performance. In particular, we design an optimization algorithm that
  operates with the lower-dimensional (compressed) stochastic gradients, and establish
  that with the right set of parameters it has the exact same dimension-free convergence
  guarantees as that of regular SGD for popular convex and nonconvex optimization
  settings. We also present two applications of these bounds, one for improving the
  empirical risk minimization bounds in differentially private nonconvex optimization,
  and other for reducing communication costs with distributed SGD. Additionally, we
  also show that this connection between constraint set structure and gradient compression
  also extends beyond SGD to the conditional gradient (Frank-Wolfe) method. The geometry
  of the constraint set, captured by its Gaussian width, plays an important role in
  all our results.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kasiviswanathan21a
month: 0
tex_title: SGD with low-dimensional gradients with applications to private and distributed
  learning
firstpage: 1905
lastpage: 1915
page: 1905-1915
order: 1905
cycles: false
bibtex_author: Kasiviswanathan, Shiva Prasad
author:
- given: Shiva Prasad
  family: Kasiviswanathan
date: 2021-12-01
address:
container-title: Proceedings of the Thirty-Seventh Conference on Uncertainty in Artificial
  Intelligence
volume: '161'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 12
  - 1
pdf: https://proceedings.mlr.press/v161/kasiviswanathan21a/kasiviswanathan21a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v161/kasiviswanathan21a/kasiviswanathan21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
