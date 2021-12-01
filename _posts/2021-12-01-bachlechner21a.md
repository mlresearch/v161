---
title: 'ReZero is all you need: fast convergence at large depth'
abstract: Deep networks often suffer from vanishing or exploding gradients due to
  inefficient signal propagation, leading to long training times or convergence difficulties.
  Various architecture designs, sophisticated residual-style networks, and initialization
  schemes have been shown to improve deep signal propagation. Recently, Pennington
  et al. [2017] used free probability theory to show that dynamical isometry plays
  an integral role in efficient deep learning. We show that the simplest architecture
  change of gating each residual connection using a single zero-initialized parameter
  satisfies initial dynamical isometry and outperforms more complex approaches. Although
  much simpler than its predecessors, this gate enables training thousands of fully
  connected layers with fast convergence and better test performance for ResNets trained
  on an image recognition task. We apply this technique to language modeling and find
  that we can easily train 120-layer Transformers. When applied to 12 layer Transformers,
  it converges 56% faster.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bachlechner21a
month: 0
tex_title: 'ReZero is all you need: fast convergence at large depth'
firstpage: 1352
lastpage: 1361
page: 1352-1361
order: 1352
cycles: false
bibtex_author: Bachlechner, Thomas and Majumder, Bodhisattwa Prasad and Mao, Henry
  and Cottrell, Gary and McAuley, Julian
author:
- given: Thomas
  family: Bachlechner
- given: Bodhisattwa Prasad
  family: Majumder
- given: Henry
  family: Mao
- given: Gary
  family: Cottrell
- given: Julian
  family: McAuley
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
pdf: https://proceedings.mlr.press/v161/bachlechner21a/bachlechner21a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v161/bachlechner21a/bachlechner21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
