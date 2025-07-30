# SHAP Value Mini Project – Breast Cancer Prediction (Random Forest)

This mini project explores **SHAP (SHapley Additive exPlanations)** to interpret the predictions of a Random Forest classifier trained on the Wisconsin Breast Cancer dataset.

## What is SHAP?

SHAP is a game-theoretic approach to explain the output of machine learning models. It shows how much each feature contributes to a particular prediction, helping us open the “black box” of complex models.

## Project Goals

- Train a Random Forest classifier on breast cancer data.
- Use SHAP to understand which features influence predictions.
- Visualize both **global** and **local** feature importance.
- Learn the basics of model interpretability.

## Dataset

- Dataset used: `wdbc.data` (Wisconsin Diagnostic Breast Cancer)
- Binary classification: Malignant vs Benign tumors
- 30 numeric features

## What I Learned

- How to apply SHAP with `TreeExplainer`
- How to interpret SHAP bar plots and waterfall plots
- Why features like `area_worst` and `concave_points_worst` are key in predictions
- The difference between global and local interpretability

## Requirements

```bash
pip install pandas matplotlib shap scikit-learn
