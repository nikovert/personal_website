---
title: SPoRt -- Safe Policy Ratio
subtitle: Certified Training and Deployment of Task Policies in Model-Free RL
publication_types:
  - "3"
authors:
  - Jacques Cloete
  - admin
  - Alessandro Abate
abstract: "To apply reinforcement learning to safety-critical applications, we
  ought to provide safety guarantees during both policy training and deployment.
  In this work we present novel theoretical results that provide a bound on the
  probability of violating a safety property for a new task-specific policy in a
  model-free, episodic setup: the bound, based on a `maximum policy ratio' that
  is computed with respect to a `safe' base policy, can also be more generally
  applied to temporally-extended properties (beyond safety) and to robust
  control problems. We thus present SPoRt, which also provides a data-driven
  approach for obtaining such a bound for the base policy, based on scenario
  theory, and which includes Projected PPO, a new projection-based approach for
  training the task-specific policy while maintaining a user-specified bound on
  property violation. Hence, SPoRt enables the user to trade off safety
  guarantees in exchange for task-specific performance. Accordingly, we present
  experimental results demonstrating this trade-off, as well as a comparison of
  the theoretical bound to posterior bounds based on empirical violation rates."
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-04-14T11:11:23.412Z
---
