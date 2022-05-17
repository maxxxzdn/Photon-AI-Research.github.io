---
permalink: /neural_solvers/
title: "Neural Solvers"
author_profile: true
redirect_from:
  - /pinn/
  - /neural_solvers.html
---

![Drag Racing](https://raw.githubusercontent.com/Photon-AI-Research/NeuralSolvers/master/images/cropped_logo.png)

Neural Solvers are neural network based solver for partial differential equations and inverse problems. 
Our library [Neural Solvers](https://github.com/Photon-AI-Research/NeuralSolvers) implements the physics-informed neural network approach on scale. Physics informed neural networks allow strong scaling by design. Therefore, we have developed a framework that uses data parallelism to accelerate the training of 
physics informed neural networks significantly. To implement data parallelism, we use the <a href="https://github.com/horovod/horovod">Horovod</a> framework, which provides near-ideal speedup on multi-GPU regimes.

The framework currently implements a variety of recent models in natural sciences such as
* 1d, Maxwell's equation
* 1d, 2d Schrödinger's equation
* 1d, 2d Heat equation
* 3d Wave equation

## Implemented Approaches:

- P. Stiller, F. Bethke, M. Böhme, R. Pausch, S. Torge, A. Debus, J. Vorberger, M.Bussmann, N. Hoffmann: 
Large-scale Neural Solvers for Partial Differential Equations (2020).

- Raissi, Maziar, Paris Perdikaris, and George Em Karniadakis.
Physics Informed Deep Learning (Part I): Data-driven Solutions of Nonlinear Partial Differential Equations.(2017).

- Raissi, Maziar, Paris Perdikaris, and George Em Karniadakis. 
Physics Informed Deep Learning (Part II): Data-driven Discovery of Nonlinear Partial Differential Equations.(2017).

- Suryanarayana Maddu, Dominik Sturm, Christian L. Müller and Ivo F. Sbalzarini (2021):
Inverse Dirichlet Weighting Enables Reliable Training of Physics Informed Neural Networks

- Sifan Wang, Yujun Teng, Paris Perdikaris (2020) Understanding and mitigating gradient pathologies in physics-informed neural networks
