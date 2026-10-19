---
reading_time: false
title: "To Ask or Not to Ask: Learning to Require Human Feedback"
authors:
  - Andrea Pugnana
  - Giovanni De Toni
  - me
  - Roberto Pellungrini
  - Bruno Lepri
  - Andrea Passerini
date: "2025-09-01T00:00:00Z"
publication_types: ["paper-conference"]
publication:
  name: "The Third Workshop on Hybrid Human-Machine Learning and Decision Making (ECML PKDD 2025)"
  short_name: "HLDM @ ECML PKDD 2025"
peer_reviewed: true
featured: false
---

## Abstract

Developing decision-support systems that complement human performance in classification tasks remains an open challenge. A popular approach, Learning to Defer (LtD), allows a Machine Learning (ML) model to pass difficult cases to a human expert. However, LtD treats humans and ML models as mutually exclusive decision-makers, restricting the expert contribution to mere predictions. To address this limitation, we propose Learning to Ask (LtA), a new framework that handles both when and how to incorporate expert input in an ML model. LtA is based on a two-part architecture: a standard ML model and an enriched model trained with additional expert human feedback, with a formally optimal strategy for selecting when to query the enriched model. We provide two practical implementations of LtA: a sequential approach, which trains the models in stages, and a joint approach, which optimises them simultaneously. For the latter, we design surrogate losses with realisable-consistency guarantees. Our experiments with synthetic and real expert data demonstrate that LtA provides a more flexible and powerful foundation for effective human–AI collaboration.
