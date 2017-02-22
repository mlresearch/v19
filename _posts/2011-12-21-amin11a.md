---
title: Bandits, Query Learning, and the Haystack Dimension
abstract: Motivated by multi-armed bandits (MAB) problems with a very large or even
  infinite number of arms, we consider the problem of finding a maximum of an unknown
  target function by querying the function at chosen inputs (or arms).We give an analysis
  of the query complexity of this problem, under the assumption that the payoff of
  each arm is given by a function belonging to a known, finite, but otherwise arbitrary
  function class. Our analysis centers on a new notion of function class complexity
  that we callthe \emph{haystack dimension}, which is used to prove the approximate
  optimality of a simple greedy algorithm. This algorithm is then usedas a subroutine
  in a \parametric MAB algorithm, yielding provably near-optimal regret. We provide
  a generalization to the infinite cardinality setting, andcomment on how our analysis
  is connected to, and improves upon, existing results for query learning and generalized
  binary search.
pdf: "./amin11a/amin11a.pdf"
layout: inproceedings
key: amin11a
month: 0
firstpage: 87
lastpage: 106
origpdf: http://jmlr.org/proceedings/papers/v19/amin11a/amin11a.pdf
sections: 
authors:
- given: Kareem
  family: Amin
- given: Michael
  family: Kearns
- given: Umar
  family: Syed
---
