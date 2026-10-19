---
reading_time: false
title: "Divide et Calibra: Multiclass Local Calibration via Vector Quantization"
authors:
  - me
  - Lorenzo Perini
  - Giovanni De Toni
  - Andrea Passerini
  - Andrea Pugnana
date: "2026-09-01T00:00:00Z"
publication_types: ["paper-conference"]
publication:
  name: "Advances in Neural Information Processing Systems (NeurIPS 2026)"
  short_name: "NeurIPS 2026"
peer_reviewed: true
featured: true
---

## Abstract

Accurate and well-calibrated Machine Learning (ML) models are mandatory in high-stakes settings, yet effective multiclass calibration remains challenging: global approaches assume calibration errors are homogeneous across the latent space, while local methods often rely on latent-space dimensionality reduction, which leads to information loss. To address these issues, we propose a compositional approach to multiclass calibration, where region-specific calibration maps are constructed from shared codeword-dependent factors. We instantiate this idea via Vector Quantization (VQ), which induces a structured partition of the representation space, and an indexed parameterization of Dirichlet concentrations that enables parameter sharing across regions. Our approach learns heterogeneous calibration maps that generalize well even to sparse regions of the latent space. Experiments on benchmark datasets show significant improvements in local calibration while maintaining competitive global calibration and predictive performance.
