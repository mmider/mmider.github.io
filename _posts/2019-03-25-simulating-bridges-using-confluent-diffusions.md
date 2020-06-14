---
layout: post
title: "Simulating bridges using confluent diffusions"
categories:
  - publication
tags:
  - SDE
  - algorithm design
comments: false
---

**This is joint work with [Paul Jenkins](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/jenkins/), [Murray Pollock](https://www.turing.ac.uk/people/researchers/murray-pollock), [Gareth Roberts](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/roberts/) and [Michael Sørensen](http://web.math.ku.dk/~michael/)**


Abstract
----
> Diffusions are a fundamental class of models in many fields, including finance, engineering, and biology. However, their simulation is challenging as their sample paths are infinite-dimensional and their transition function is typically intractable. In many statistical settings (such as parameter inference for discretely observed diffusions), we require simulation techniques for diffusions conditioned on hitting an endpoint, which introduces further complication. In this paper we introduce a Markov chain Monte Carlo algorithm for simulating diffusion bridges which is both exact (in the sense that there is no discretisation error) and has computational cost that is linear in the duration of the bridge. Our approach works directly on diffusion path space, by constructing a proposal (which we term a confluence) with finite computational cost which is then accepted/rejected using a computable probability. The novelty of our method is that it only requires the simulation of unconditioned diffusion sample paths. Our methodology develops a number of simulation techniques we believe to be of independent interest, related to the crossing and first passage times of multiple Brownian motions, meanders and bridges, and Bessel bridges. We apply our methodology to the simulation of Langevin diffusion bridges, a practical problem arising naturally in statistical fusion settings.

Additional info
----
The paper is available on [arXiv](https://arxiv.org/abs/1903.10184). The algorithm developed in the paper is biased---this bias can be reduced to an arbitrary degree by increasing the intensity of the dominating Poisson process. However, we are currently working on removing this limitation.