---
layout: post
title: "BridgeSDEInference.jl"
categories:
  - software
  - publication
tags:
  - software
  - inference
  - SDE
  - FPT
comments: false
---
<a href="https://doi.org/10.5281/zenodo.3446184"><img align="bottom" src="https://zenodo.org/badge/DOI/10.5281/zenodo.3446185.svg" title="DOI" alt="DOI BridgeSDEInference.jl"/></a>

[<img alt="mmider" src="https://avatars1.githubusercontent.com/u/15090340?v=4&s=117 width=117">](https://github.com/mmider) |[<img alt="mschauer" src="https://avatars1.githubusercontent.com/u/1923437?v=4&s=117 width=117">](https://github.com/mschauer) |[<img alt="SebaGraz" src="https://avatars0.githubusercontent.com/u/43820633?v=4&s=117 width=117">](https://github.com/SebaGraz) |
:---:|:---:|:---:|
[mmider](https://github.com/mmider)|[mschauer](https://github.com/mschauer)|[SebaGraz](https://github.com/SebaGraz)|

**BridgeSDEInference.jl** is a software package for <tt>Julia</tt> programming language in which we implement various inference algorithms for diffusion processes based on *Guided proposals*. It is hosted on [github](https://github.com/mmider/BridgeSDEInference.jl) and can be installed using <tt>Julia</tt>'s built-in package manager:

```julia
using Pkg
Pkg.add("BridgeSDEInference")
```
We provide routines for running an MCMC sampler that infers posterior distribution over the unknown parameters $\theta$ governing the stochastic differential equation

$$
dX_t = b_{\theta}(t,X_t)dt + \sigma_{\theta}(t,X_t)dW_t,\quad t\in[0,T],\quad X_0=x_0,
$$

from discrete-time, *partial and noisy observations* of the process $X$:

$$
V_{t_i}=L_i X_{t_i} + \xi_i,\quad i=1,\dots,N
$$

where $\xi_i$ are iid Gaussian random variables and $L_i\in R^{m_i\times d}$.

We also provide routines for inference from *first passage time observations*, as well as for *mixed effect models* (the last one is still in development).

Check out the [documentation](https://mmider.github.io/BridgeSDEInference.jl/dev) for more details.