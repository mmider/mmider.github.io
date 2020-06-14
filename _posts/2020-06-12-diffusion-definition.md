---
layout: post
title: "DiffusionDefinition.jl"
pictureaddress: "https://raw.githubusercontent.com/JuliaDiffusionBayes/DiffusionDefinition.jl/master/docs/src/assets/logo.png"
picturehref: "https://github.com/JuliaDiffusionBayes/DiffusionDefinition.jl"
categories:
  - software
tags:
  - software
  - SDE
comments: false
---
> A Julia package that makes it easy to define diffusion processes and sample from their laws.

[DiffusionDefinition.jl](https://github.com/JuliaDiffusionBayes/DiffusionDefinition.jl) comprises of:
- convenient methods facilitating
  - defining diffusion laws
  - forward-sampling their trajectories
  - computing functionals of sampled paths
  - computing gradients of functionals of sampled paths with respect to diffusion parameters or with respect to the starting point of the trajectory
- A number of predefined diffusion processes that can be immediately loaded in and experimented on

It is designed to work efficiently in a setting of Bayesian inference for diffusion processes.

It is a part of a larger suite of packages [JuliaDiffusionBayes](https://github.com/JuliaDiffusionBayes)---a collection of efficient and intuitive tools for performing Bayesian inference for diffusion processes.