---
title: "“To Ask or Not to Ask: Learning to Require Human Feedback” is on arXiv"
date: 2025-10-09
summary: "Our work on learning when and how to incorporate human feedback into ML models is now available on arXiv."
clickable: true
---
“[**To Ask or Not to Ask: Learning to Require Human Feedback**](https://arxiv.org/abs/2510.08314)” is now available on **arXiv**.

## Abstract

Developing decision-support systems that complement human performance in classification tasks remains an open challenge. A popular approach, Learning to Defer (LtD), allows a Machine Learning (ML) model to pass difficult cases to a human expert. However, LtD treats humans and ML models as mutually exclusive decision-makers, restricting the expert contribution to mere predictions. To address this limitation, we propose Learning to Ask (LtA), a new framework that handles both when and how to incorporate expert input in an ML model. LtA is based on a two-part architecture: a standard ML model and an enriched model trained with additional expert human feedback, with a formally optimal strategy for selecting when to query the enriched model. We provide two practical implementations of LtA: a sequential approach, which trains the models in stages, and a joint approach, which optimises them simultaneously. For the latter, we design surrogate losses with realisable-consistency guarantees. Our experiments with synthetic and real expert data demonstrate that LtA provides a more flexible and powerful foundation for effective human–AI collaboration.
