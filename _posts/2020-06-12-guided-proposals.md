---
layout: post
title: "GuidedProposals.jl"
categories:
  - software
tags:
  - software
  - SDE
comments: false
---
> A Julia package for efficient sampling of conditioned diffusions.

[GuidedProposals.jl](https://github.com/JuliaDiffusionBayes/GuidedProposals.jl) uses the guided proposals algorithm introduced by [M. Schauer, F. van der Meulen, H. van Zanten](https://projecteuclid.org/euclid.bj/1494316837) [[arXiv](https://arxiv.org/abs/1311.3606)], using a computational framework described [here]({% post_url 2020-03-02-continuous-discrete-smoothing %}). It provides efficient and easy to use routines for sampling conditioned diffusions.

It is a part of a larger suite of packages [JuliaDiffusionBayes](https://github.com/JuliaDiffusionBayes)---a collection of efficient and intuitive tools for performing Bayesian inference for diffusion processes.