---
title: Scalable Verification of Neural Control Barrier Functions Using Linear
  Bound Propagation
publication_types:
  - "3"
authors:
  - admin
  - Frederik Baymler Mathiesen
  - Thom Badings
  - Luca Laurenti
  - Alessandro Abate
abstract: Control barrier functions (CBFs) are a popular tool for safety
  certification of nonlinear dynamical control systems. Recently, CBFs
  represented as neural networks have shown great promise due to their
  expressiveness and applicability to a broad class of dynamics and safety
  constraints. However, verifying that a trained neural network is indeed a
  valid CBF is a computational bottleneck that limits the size of the networks
  that can be used. To overcome this limitation, we present a novel framework
  for verifying neural CBFs based on piecewise linear upper and lower bounds on
  the conditions required for a neural network to be a CBF. Our approach is
  rooted in linear bound propagation (LBP) for neural networks, which we extend
  to compute bounds on the gradients of the network. Combined with McCormick
  relaxation, we derive linear upper and lower bounds on the CBF conditions,
  thereby eliminating the need for computationally expensive verification
  procedures. Our approach applies to arbitrary control-affine systems and a
  broad range of nonlinear activation functions. To reduce conservatism, we
  develop a parallelizable refinement strategy that adaptively refines the
  regions over which these bounds are computed. Our approach scales to larger
  neural networks than state-of-the-art verification procedures for CBFs, as
  demonstrated by our numerical experiments.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-11-14T11:51:22.596Z
---
