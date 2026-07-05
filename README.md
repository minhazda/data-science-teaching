# Applied Time-Series Forecasting Tutorials

Three hands-on notebooks that build from a first forecasting model to
tree ensembles evaluated with Rolling-Origin Cross-Validation — originally
developed as teaching material, kept here as the readable companion to my
research and production forecasting repos.

**Author:** Md Minhazur Rahman
MSc Data Science (Merit) — University of Greenwich

---

## Contents

| Notebook | Topic | Level |
|---|---|---|
| [01 — Introduction to Time-Series Forecasting](./01_intro_time_series_forecasting.ipynb) | Synthetic data, Linear Regression, train-test split | Beginner |
| [02 — Feature Engineering for Time-Series](./02_feature_engineering_for_time_series.ipynb) | Lag features, rolling windows, feature leakage | Intermediate |
| [03 — Tree-Based Models and ROCV](./03_tree_models_and_rocv.ipynb) | Random Forest, XGBoost, Rolling-Origin Cross-Validation | Intermediate–Advanced |

---

## Learning Path

These three notebooks form a complete mini-module in
applied time-series forecasting: 

Notebook 01 → What is time-series data?
Build your first forecasting model.

Notebook 02 → Why raw data is not enough.
Engineer lag and rolling features.
Understand and prevent feature leakage.

Notebook 03 → Why tree-based models dominate.
Evaluate honestly with ROCV.
See how research becomes a live system.

---

## Related Research

These teaching materials connect directly to
published MSc dissertation research:

- **Full research pipeline:**
  [github.com/minhazda/synthetic-retail-forecasting](https://github.com/minhazda/synthetic-retail-forecasting)

- **Live interactive demo:**
  [retail-forecasting.streamlit.app](https://retail-forecasting-hvdzvesi4u9l6fs5tvdoyi.streamlit.app/)

- **Published preprint (DOI):**
  [10.5281/zenodo.19479285](https://doi.org/10.5281/zenodo.19479285)

---

## Why this repo exists

Explaining a method clearly is part of doing it well. These notebooks take the
research-grade methods from my forecasting work (lag features, leakage
prevention, Rolling-Origin CV) and present them so a beginner can follow the
progression from first model to deployed system — the same communication I'd
bring to design docs and analysis write-ups on a team.

My CV: [Rahman_CV.pdf](./Rahman_CV.pdf) · Portfolio: [github.com/minhazda](https://github.com/minhazda)
