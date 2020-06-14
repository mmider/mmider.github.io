---
layout: post
title: "JuliaDiffusionBayes"
categories:
  - software
tags:
  - SDE
  - inference
comments: false
---

A suite of Julia packages providing efficient and intuitive tools for performing Bayesian inference for diffusion processes.

[JuliaDiffusionBayes](https://github.com/JuliaDiffusionBayes) currently comprises of five main packages:
- [DiffusionDefinition.jl](https://github.com/JuliaDiffusionBayes/DiffusionDefinition.jl): makes it possible to define diffusion processes and sample from their laws
- [ObservationSchemes.jl](https://github.com/JuliaDiffusionBayes/ObservationSchemes.jl): provides a systematic way of encoding discrete-time observations for stochastic processes
- [GuidedProposals.jl](https://github.com/JuliaDiffusionBayes/GuidedProposals.jl): is responsible for defining and sampling conditioned diffusion processes
- [ExtensibleMCMC.jl](https://github.com/JuliaDiffusionBayes/ExtensibleMCMC.jl): a modular implementation of the Markov chain Monte Carlo (MCMC) algorithms
- [DiffusionMCMC.jl](https://github.com/JuliaDiffusionBayes/DiffusionMCMC.jl): Markov chain Monte Carlo (MCMC) algorithms for doing inference for diffusion processes

It is a work in progress and I will update this page as the progress is made.