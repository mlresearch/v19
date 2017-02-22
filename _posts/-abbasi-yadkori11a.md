---
title: Regret Bounds for the Adaptive Control of Linear Quadratic Systems
abstract: We study the average cost Linear Quadratic (LQ) control problem with unknown
  model parameters, also known as the adaptive control problem in the control community.
  We design an algorithm and prove that apart from logarithmic factors its regret
  up to time $T$ is $O(\sqrt{T})$.Unlike previous approaches that use a forced-exploration
  scheme, we construct a high-probability confidence set around the model parameters
  and design an algorithm that plays optimistically with respect to this confidence
  set. The construction of the confidence set is based on the recent results from
  online least-squares estimation and leads to improved worst-case regret bound for
  the proposed algorithm.To the best of our knowledge this is the the first time that
  a regret bound is derived for the LQ control problem. \%(That $O(\sqrt{T})$ is a
  minimax optimal rate follows from the existing lower bounds for linear bandit problems.)
pdf: "./abbasi-yadkori11a/abbasi-yadkori11a.pdf"
layout: inproceedings
key: abbasi-yadkori11a
month: 0
firstpage: 1
lastpage: 26
origpdf: http://jmlr.org/proceedings/papers/v19/abbasi-yadkori11a/abbasi-yadkori11a.pdf
sections: 
authors:
- given: Yasin
  family: Abbasi-Yadkori
- given: Csaba
  family: Szepesvári
---
