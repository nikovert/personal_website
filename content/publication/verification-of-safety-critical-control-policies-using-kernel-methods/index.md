---
title: Verification of safety critical control policies using kernel methods
publication_types:
  - "1"
authors:
  - admin
  - Sina Ober-Blöbaum
  - Kostas Margellos
publication: In *2022 European Control Conference (ECC)*
publication_short: In *ECC22*
abstract: Hamilton-Jacobi reachability methods for safety-critical control have
  been well studied, but the safety guarantees derived rely on the accuracy of
  the numerical computation. Thus, it is crucial to understand and account for
  any inaccuracies that occur due to uncertainty in the underlying dynamics and
  environment as well as the induced numerical errors. To this end, we propose a
  framework for modeling the error of the value function inherent in
  Hamilton-Jacobi reachability using a Gaussian process. The derived safety
  controller can be used in conjuncture with arbitrary controllers to provide a
  safe hybrid control law. The marginal likelihood of the Gaussian process then
  provides a confidence metric used to determine switches between a least
  restrictive controller and a safety controller. We test both the prediction as
  well as the correction capabilities of the presented method in a classical
  pursuit-evasion example.
draft: false
featured: false
tags:
  - Reachability
  - Optimal Control
  - Machine Learning
image:
  filename: corrected_v_high.png
  focal_point: Smart
  preview_only: false
date: 2022-03-26T15:13:31.968Z
---
