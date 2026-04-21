---
title: "Credit Score Classification — Deep Learning"
date: 2023-12-01
layout: single
author_profile: true
permalink: /projects/credit-score-classification/
excerpt: "ANN-based multi-class credit risk classifier. 83.4% test accuracy on 100K records using TensorFlow/Keras with Dropout, BatchNorm, and L1 regularization."
header:
  teaser: /assets/images/Picture1.jpg
  overlay_color: "#1a1a2e"
  overlay_filter: 0.7
tags: [Python, TensorFlow, Deep Learning, Scikit-learn, Pandas, ANN]
toc: true
toc_label: "Sections"
---

<div class="badges-row">
  <span class="badge badge-ai">Deep Learning</span>
  <span class="badge badge-ml">TensorFlow</span>
</div>

## Overview

This project builds a **deep learning credit scoring system** predicting whether a customer belongs to **Poor, Standard, or Good** credit categories using financial behavior data — demonstrating how ANNs can capture complex non-linear relationships for more accurate credit risk prediction.

| Metric | Score |
|---|---|
| Training Accuracy | **86.4%** |
| Test Accuracy | **83.4%** |

## Dataset

- **Source:** Kaggle Credit Score Dataset · 100,000 rows · 28 features → 37 after engineering
- **Target Classes:** `0 → Poor` · `1 → Standard` · `2 → Good`
- Key features: Annual Income, Outstanding Debt, Credit Utilization Ratio, Payment Behavior, Monthly Balance

## Model Architecture

```
Input Layer
Dense(256) + ReLU → BatchNorm → Dropout(0.35)
Dense(512) + ReLU → BatchNorm → L1 Regularization
Dense(256) + ReLU → BatchNorm → Dropout(0.10)
Dense(256) + ReLU → BatchNorm → Dropout(0.10)
Output: Dense(3) + Softmax
```

**Config:** Adam · LR: 0.0003 · Epochs: 250 · Batch: 1024

## Tech Stack

Python · TensorFlow / Keras · Scikit-learn · Pandas · NumPy · Matplotlib · Google Colab
