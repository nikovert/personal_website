---
title: State Aggregation for Distributed Value Iteration in Dynamic Programming
publication_types:
  - "2"
authors:
  - admin
  - Kostas Margellos
publication: "*under review*"
abstract: We propose a distributed algorithm to solve a dynamic programming problem with multiple agents, where each agent has only partial knowledge of the state transition probabilities and costs. We provide consensus proofs for the presented algorithm and derive error bounds of the obtained value function with respect to what is considered as the "true solution" obtained from conventional value iteration. To minimize communication overhead between agents, state costs are aggregated and shared between agents only when the updated costs are expected to influence the solution of other agents significantly. We demonstrate the efficacy of the proposed distributed aggregation method to a large-scale urban traffic routing problem. Individual agents compute the fastest route to a common access point and share local congestion information with other agents allowing for fully distributed routing with minimal communication between agents.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-20-05T13:52:41.273Z
---
