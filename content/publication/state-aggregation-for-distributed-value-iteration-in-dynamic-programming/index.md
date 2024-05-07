---
title: State Aggregation for Distributed Value Iteration in Dynamic Programming
publication_types:
  - "2"
authors:
  - admin
  - Kostas Margellos
doi: 10.1109/LCSYS.2023.3285655
publication: In *IEEE Control Systems Letters*, vol. 7, pp. 2269–2274
abstract: We propose a distributed algorithm to solve a dynamic programming
  problem with multiple agents, where each agent has only partial knowledge of
  the state transition probabilities and costs. We provide consensus proofs for
  the presented algorithm and derive error bounds of the obtained value function
  with respect to what is considered as the "true solution" obtained from
  conventional value iteration. To minimize communication overhead between
  agents, state costs are aggregated and shared between agents only when the
  updated costs are expected to influence the solution of other agents
  significantly. We demonstrate the efficacy of the proposed distributed
  aggregation method to a large-scale urban traffic routing problem. Individual
  agents compute the fastest route to a common access point and share local
  congestion information with other agents allowing for fully distributed
  routing with minimal communication between agents.
draft: false
featured: false
tags:
  - Distributed control
  - Optimal Control
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-06-15T12:38:49.184Z
---
