---
layout: post
title: "ObservationSchemes.jl"
pictureaddress: "https://raw.githubusercontent.com/JuliaDiffusionBayes/ObservationSchemes.jl/master/docs/src/assets/logo.png"
picturehref: "https://github.com/JuliaDiffusionBayes/ObservationSchemes.jl"
categories:
  - software
tags:
  - software
  - SDE
comments: false
---
> A Julia package that provides tools for defining observation schemes for stochastic processes in a systematic manner.

The principal idea behind [ObservationSchemes.jl](https://github.com/JuliaDiffusionBayes/ObservationSchemes.jl) is to
1. provide structs (currently `LinearGsnObs` and `GeneralObs`) that can decorate each observation separately with the information about how each particular datapoint was collected
2. provide a collection struct (`AllObservations`) that collects
   - the decorated data
   - together with the information about the laws of the underlying stochastic processes
   - and the dependence structure between various laws (so as to facilitate working with mixed effect models)

It is a part of a larger suite of packages [JuliaDiffusionBayes](https://github.com/JuliaDiffusionBayes)---a collection of efficient and intuitive tools for performing Bayesian inference for diffusion processes.