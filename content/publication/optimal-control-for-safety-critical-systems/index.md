---
title: Optimal control for safety-critical systems
publication_types:
  - "7"
authors:
  - admin
doi: http://dx.doi.org/10.5287/ora-zr6o9q97k
abstract: >-
  Enforcing safety plays a crucial role within the optimisation and control
  literature. Despite notable advances in recent years, optimal control for
  safety-critical and high-dimensional systems remains a challenging problem.
  Developing a general theoretical framework for integrating safety within
  optimal control is not tractable as the numerical inaccuracy and computational
  cost often grow exponentially with the number of states. Furthermore,
  different notions of safety require different methodologies and present unique
  theoretical and computational challenges. This thesis focuses on the
  challenges that arise when addressing scalability and safety considerations
  simultaneously.



  Safety is a multi-facet problem that involves hard constraint satisfaction, avoiding sharing information considered as private, as well as robustifying towards uncertainty that could otherwise compromise safety. The initial chapters of the thesis focus on Hamilton-Jacobi reachability, which has become a well-established method of computing reachable sets for complex nonlinear systems. In addition to enforcing that the system remains within a safe part of the state-space, we consider application-specific abstractions to deal with scalability, the interplay between competing performance objectives and safety objectives, and the challenges arising from multi-objective optimal control problems. We then investigate safety considerations due to the amount of information that needs to be shared between agents in a multi-agent networked control setting. Extending classical state-aggregation in approximate dynamic programming, we introduce a method of solving a large-scale Markov Decision Process in a fully distributed manner. The final chapter considers stochastic safety constraints under a statistical learning theoretic lens. Utilising randomised algorithms, we establish probably approximately correct (PAC) bounds on predicting a future label in a binary classification problem whereby the classifier changes in an unknown structured manner.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-08-08T12:20:56.759Z
---
