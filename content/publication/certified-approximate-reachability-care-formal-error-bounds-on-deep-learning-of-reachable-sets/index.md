---
title: Certified Approximate Reachability (CARe)
subtitle: Formal Error Bounds on Deep Learning of Reachable Sets
publication_types:
  - "3"
authors:
  - Prashant Solanki
  - admin
  - Yannik Schnitzer
  - Jasper Van Beers
  - Coen de Visser
  - Alessandro Abate
author_notes: []
abstract: Recent approaches to leveraging deep learning for computing reachable
  sets of continuous-time dynamical systems have gained popularity over
  traditional level-set methods, as they overcome the curse of dimensionality.
  However, as with level-set methods, considerable care needs to be taken in
  limiting approximation errors, particularly since no guarantees are provided
  during training on the accuracy of the learned reachable set. To address this
  limitation, we introduce an epsilon-approximate Hamilton-Jacobi Partial
  Differential Equation (HJ-PDE), which establishes a relationship between
  training loss and accuracy of the true reachable set. To formally certify this
  approximation, we leverage Satisfiability Modulo Theories (SMT) solvers to
  bound the residual error of the HJ-based loss function across the domain of
  interest. Leveraging Counter Example Guided Inductive Synthesis (CEGIS), we
  close the loop around learning and verification, by fine-tuning the neural
  network on counterexamples found by the SMT solver, thus improving the
  accuracy of the learned reachable set. To the best of our knowledge, Certified
  Approximate Reachability (CARe) is the first approach to provide soundness
  guarantees on learned reachable sets of continuous dynamical systems.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-04-01T08:26:41.910Z
---
