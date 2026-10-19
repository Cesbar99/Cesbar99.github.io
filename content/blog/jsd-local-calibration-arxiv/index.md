---
title: "“Multiclass Local Calibration with the Jensen–Shannon Distance” is on arXiv"
date: 2025-10-30
summary: "Our work on consistent multiclass local calibration with LocalNets is now available on arXiv."
clickable: true
---
“[**Multiclass Local Calibration with the Jensen–Shannon Distance**](https://arxiv.org/abs/2510.26566)” is now available on **arXiv**.

## Abstract

Developing trustworthy Machine Learning (ML) models requires their predicted probabilities to be well-calibrated, meaning they should reflect true-class frequencies. Among calibration notions in multiclass classification, strong calibration is the most stringent, as it requires all predicted probabilities to be simultaneously calibrated across all classes. However, existing approaches to multiclass calibration lack a notion of distance among inputs, which makes them vulnerable to proximity bias: predictions in sparse regions of the feature space are systematically miscalibrated. In this work, we address this main shortcoming by introducing a local perspective on multiclass calibration. First, we formally define multiclass local calibration and establish its relationship with strong calibration. Second, we theoretically analyze the pitfalls of existing evaluation metrics when applied to multiclass local calibration. Third, we propose a practical method to enhance local calibration in Neural Networks, which enforces alignment between predicted probabilities and local estimates of class frequencies using the Jensen-Shannon distance. Finally, we empirically validate our approach against existing multiclass calibration techniques.
