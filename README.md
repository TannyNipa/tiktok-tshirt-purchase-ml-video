# Machine Learning-Guided Short-Form Video Development and Evaluation for T-Shirt Purchase Behaviour on TikTok

This repository contains the source code, aggregate analytical outputs,
and final short-form promotional video associated with a two-phase study
of self-reported T-shirt purchase behaviour on TikTok.

The associated manuscript has been submitted to *Trends in Sciences
(TiS)* for publication consideration.

## Study Overview

The study was conducted in two independent phases.

### Phase 1: Machine-Learning Analysis

Phase 1 examined Theory of Planned Behavior indicators and
video-content predictors associated with self-reported T-shirt purchase
behaviour on TikTok.

The machine-learning workflow included:

- comparison of supervised classification algorithms;
- evaluation of alternative TPB predictor configurations;
- comparison of class-imbalance handling methods;
- hyperparameter optimisation;
- permutation-importance analysis; and
- predictor-subset evaluation.

Model performance was evaluated using repeated stratified
cross-validation, with macro-F1 used as the primary model-selection
criterion.

### Phase 2: Video Development and Evaluation

The retained video-content predictors were used to guide the development
of a short-form promotional video for T-shirt products on TikTok.

The final video was evaluated by an independent sample across two
dimensions:

1. Video quality and viewer satisfaction
2. Purchase-related perceptions and decision-making

Statistical analyses were conducted to examine differences in evaluation
scores across demographic groups.

## Repository Contents

```text
tiktok-tshirt-purchase-ml-video/
│
├── machine-learning/
│   ├── model-comparison/
│   ├── hyperparameter-optimisation + predictor-selection/
│
├── statistical-analysis/
│   ├── descriptive-analysis/
│   ├── gender-comparison/
│   ├── age-comparison/
│   └── occupation-comparison/
│
├── results/
│   ├── tables/
│   └── figures/
│
├── video/
│   └── final-promotional-video/
│
└── README.md
