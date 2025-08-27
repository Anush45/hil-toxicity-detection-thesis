# Human-in-the-Loop ML for Toxicity Detection (Master's Thesis)

This repository contains the final code and materials for my MSc thesis:
**"Human-in-the-Loop Machine Learning for Real-Time Feedback Systems"** (University of Limerick).

## Overview
- Task: Toxicity detection in online text.
- Baseline: TF–IDF + Logistic Regression / SVM.
- HIL loop: Collect human feedback on low-confidence/disagreement cases; incremental retraining.
- Key results: F1 ↑ from 0.74 to 0.76; Recall ↑ (0.62 → 0.64); fairness metrics improved.

## Datasets
- Jigsaw Toxic Comments (Kaggle)
- Civil Comments (Kaggle)
Datasets are **not included** due to size/licensing. Please download from Kaggle and place files under `data/`.

## Repo Structure (suggested)
- `notebooks/` – EDA, preprocessing, training, HIL loop
- `src/` – reusable scripts (if any)
- `results/` – plots/figures (small only)
- `sample_data/` – tiny sample CSV for demo (optional)

## Quickstart
1. Create environment and install deps:
   ```bash
   pip install -r requirements.txt

