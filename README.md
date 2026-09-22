# Machine Learning-Guided Short-Form Video Development and Evaluation for T-Shirt Purchase Behaviour on TikTok

This repository contains the executed source code, aggregate analytical outputs, and manuscript sources associated with a two-phase study of self-reported T-shirt purchase behaviour on TikTok.

The associated manuscript is prepared for submission to the *Journal of Theoretical and Applied Electronic Commerce Research* (JTAER), published by MDPI.

## Study overview

The study was conducted in two independent phases.

### Phase 1: Machine-learning analysis

Phase 1 examined Theory of Planned Behavior indicators and video-content predictors associated with self-reported T-shirt purchase behaviour on TikTok. The workflow includes supervised-classifier comparison, class-imbalance handling, hyperparameter optimisation, cross-validated permutation importance, and predictor-subset evaluation. Model performance was evaluated with repeated stratified cross-validation using macro-F1 as the primary selection metric.

### Phase 2: Video development and evaluation

The retained video-content predictors informed the development of a short-form T-shirt promotional video. An independent sample evaluated the resulting video in terms of video quality and viewer satisfaction, and purchase-related perceptions and decision-making.

## Repository contents

- `analysis/`: executed notebooks for Phase 1 modelling.
- `results/`: generated aggregate tables, figures, configuration, and fitted models.
- `manuscript/`: latest main and supplementary LaTeX sources and figure assets.
- `data/private/`: local raw data only, excluded from Git and public release.

## Primary notebooks

- `analysis/PB_Phase1_ML.ipynb` produces the repeated cross-validation tables in `results/table1_outputs/`.
- `analysis/PB_Phase1_HyperTune.ipynb` produces hyperparameter-tuning and feature-selection results in `results/combined_phase2_phase3_outputs/`, including the source image for manuscript Figure 2.

## Data availability

Raw data are deliberately excluded from this public repository. The notebooks expect `DATA.xlsx` in the repository root when run locally. A data file must be anonymised and approved for public sharing before it is committed; otherwise, an approved controlled-access statement should be used.

## Manuscript sources

- `manuscript/template_revised_editT.tex` is the latest main manuscript source.
- `manuscript/Supplementary_Material_clean_grouped_v2.tex` is the latest supplementary-material source.
