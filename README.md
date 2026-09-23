# Machine Learning-Guided Short-Form Video Development and Evaluation for T-Shirt Purchase Behaviour on TikTok

This repository contains reviewer-facing analysis notebooks and the final short-form promotional video associated with a two-phase study of self-reported T-shirt purchase behaviour on TikTok.

Manuscript files, supplementary materials, raw data, and standalone result tables are intentionally excluded while the work remains unpublished.

## Study overview

The study was conducted in two independent phases.

### Phase 1: Machine-learning analysis

Phase 1 examined Theory of Planned Behavior indicators and video-content predictors associated with self-reported T-shirt purchase behaviour on TikTok. The workflow includes supervised-classifier comparison, class-imbalance handling, hyperparameter optimisation, cross-validated permutation importance, and predictor-subset evaluation. Model performance was evaluated with repeated stratified cross-validation using macro-F1 as the primary selection metric.

### Phase 2: Video development and evaluation

The retained video-content predictors informed the development of a short-form T-shirt promotional video. An independent sample evaluated the resulting video in terms of video quality and viewer satisfaction, and purchase-related perceptions and decision-making.

## Repository contents

- `analysis/`: executed notebooks for Phase 1 modelling.
- `video/`: final short-form promotional video, stored with Git LFS.

## Primary notebooks

- `analysis/PB_Phase1_ML.ipynb` contains the repeated cross-validation workflow.
- `analysis/PB_Phase1_HyperTune.ipynb` contains the hyperparameter-tuning and feature-selection workflow.

## Data availability

Raw data are deliberately excluded from this public repository. The notebooks expect `DATA.xlsx` in the repository root when run locally. A data file must be anonymised and approved for public sharing before it is committed; otherwise, an approved controlled-access statement should be used.
