---
layout: post
title: "Continuous–discrete smoothing of diffusions"
categories:
  - publication
tags:
  - inference
  - SDE
comments: false
---

**This is joint work with [Moritz Schauer](http://www.math.chalmers.se/~smoritz/index.html) and [Frank van der Meulen](https://diamweb.ewi.tudelft.nl/~meulen/)**

Abstract
----
> Suppose $X$ is a multivariate diffusion process that is observed discretely in time. At each observation time, a linear transformation of the state of the process is observed with noise. The smoothing problem consists of recovering the path of the process, consistent with the observations. We derive a novel Markov Chain Monte Carlo algorithm to sample from the exact smoothing distribution. The resulting algorithm is called the Backward Filtering Forward Guiding (BFFG) algorithm. We extend the algorithm to include parameter estimation. The proposed method relies on guided proposals introduced in Schauer et al. (2017). We illustrate its efficiency in a number of challenging problems.

Additional info
----
The paper is available on [arXiv](https://arxiv.org/abs/1712.03807)