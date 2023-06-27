---
title: Finite sample learning of moving targets
subtitle: ""
date: 2023-06-27T09:23:32.417Z
draft: true
featured: false
authors:
  - admin
tags:
  - Machine Learning
links:
  - url: https://github.com/nikovert/Code---Finite-sample-learning-of-moving-targets
    name: Source Code
    icon_pack: fab
    icon: github
image:
  filename: concept_drift.png
  focal_point: Smart
  preview_only: false
---
We consider a binary classification problem with a moving target and provide novel probability approximately correct (PAC) bounds on the samples needed for generating a sufficiently accurate prediction of the target function. Furthermore, we introduce a constructive method of generating the hypothesis using a Mixed Integer Linear Program (MILP). By considering the binary classifiers to lie in the class of hyperrectangles, we enable the elimination of a significant majority of samples (96% in the provided example) before constructing the MILP. We illustrate the computational viability of our approach by applying it to the problem of learning safety filters subject to concept drift, as found in autonomous emergency braking procedures.