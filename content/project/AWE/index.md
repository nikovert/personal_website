---
slides: ""
url_pdf: ""
title: Safety-Aware Hybrid Control of an Airborne Wind Energy Systems
date: 2022-06-11T15:52:50.717Z
summary: A robust control approach for Airborne Wind Energy Systems
authors:
  - Nikolaus Vertovec
url_video: ""
featured: true
tags:
  - AWE
external_link: ""
url_slides: ""
links:
  - icon: github
    icon_pack: fab
    name: Source Code
    url: https://github.com/nikovert/AWE_Simulation
  - url: https://www.vertovec.info/publication/safety-aware-hybrid-control-of-airborne-wind-energy-systems/
    icon_pack: ai
image:
  caption: ""
  focal_point: Smart
  filename: featured.jpeg
url_code: ""
---
In order to move Airborne Wind Energy (AWE) into the future, a fundamental concern is being able to guarantee that safety requirements placed on the systems are met. Due to the high dimensional complexity of AWE systems, however, strict mathematical robustness guarantees become difficult to compute.

We draw on research from high dimensional Hamilton-Jacobi (HJ) reachability analysis to compute the optimal trajectory for tracking a figure-eight flight path during the pumping cycle of AWE systems while enforcing safety constraints on the system, such as those placed on the aircraft speeds and the tether force. In addition to providing the optimal control policy, the subzero level-set of the computed value function inherent in HJ reachability analysis indicates the backward reachable set (BRS), the set of states from which it is possible to safely drive the system into a target set within a given time without entering undesirable states, defined by an avoid set.

The BRS can then be used as a maneuverability envelope to derive a switching law, such that the safety controller can be used in conjunction with arbitrary least restrictive controllers to provide a safe hybrid control law. In such a setup, the safety controller is only needed when the system approaches the boundary of the maneuverability envelope. Such a hybrid control law is a notable improvement over existing robust control approaches that assume the worst-case environmental and system behavior at all times, leading to potentially sub-optimal control laws.