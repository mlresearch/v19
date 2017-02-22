---
title: 'Beyond the regret minimization barrier: an optimal algorithm for stochastic
  strongly-convex optimization'
abstract: We give a novel algorithm for stochastic strongly-convex optimization in
  thegradient oracle model which returns an $O(\frac{1}{T})$-approximate solutionafter
  $T$ gradient updates. This rate of convergence is optimal in the gradientoracle
  model. This improves upon the previously known best rate of$O(\frac{\log(T)}{T})$,
  which was obtained by applying an onlinestrongly-convex optimization algorithm with
  regret $O(\log(T))$ to the batchsetting.We complement this result by proving that
  any algorithm has expected regret of$\Omega(\log(T))$ in the online stochastic strongly-convex
  optimizationsetting. This lower bound holds even in the full-information setting
  whichreveals more information to the algorithm than just gradients. This shows thatany
  online-to-batch conversion is inherently suboptimal for stochasticstrongly-convex
  optimization. This is the first formal evidence that onlineconvex optimization is
  strictly more difficult than batch stochastic convexoptimization.
pdf: "./hazan11a/hazan11a.pdf"
layout: inproceedings
key: hazan11a
month: 0
firstpage: 421
lastpage: 436
origpdf: http://jmlr.org/proceedings/papers/v19/hazan11a/hazan11a.pdf
sections: 
authors:
- given: Elad
  family: Hazan
- given: Satyen
  family: Kale
---
