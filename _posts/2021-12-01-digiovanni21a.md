---
title: Thompson sampling for Markov games with piecewise stationary opponent policies
abstract: Reinforcement learning problems with multiple agents pose the challenge
  of efficiently adapting to nonstationary dynamics arising from other agents’ strategic
  behavior. Although several algorithms exist for these problems with promising empirical
  results, regret analysis and efficient use of other-agent models in general-sum
  games is very limited. We propose an algorithm (TSMG) for general-sum Markov games
  against agents that switch between several stationary policies, combining change
  detection with Thompson sampling to learn parametric models of these policies. Under
  standard assumptions for parametric Markov decision process (MDP) learning, the
  expected regret of TSMG in the worst case over policy parameters and switch schedules
  is near-optimal in time and number of switches, up to logarithmic factors. Our experiments
  on simulated games show that TSMG can outperform standard Thompson sampling and
  a version of Thompson sampling with a static reset schedule, despite the violation
  of an assumption that the MDPs induced by the other player are ergodic.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: digiovanni21a
month: 0
tex_title: Thompson sampling for Markov games with piecewise stationary opponent policies
firstpage: 738
lastpage: 748
page: 738-748
order: 738
cycles: false
bibtex_author: DiGiovanni, Anthony and Tewari, Ambuj
author:
- given: Anthony
  family: DiGiovanni
- given: Ambuj
  family: Tewari
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
pdf: https://proceedings.mlr.press/v161/digiovanni21a/digiovanni21a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v161/digiovanni21a/digiovanni21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
