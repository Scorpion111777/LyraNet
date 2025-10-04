🌌 LyraNet – Exoplanet Candidate Detection with Responsible AI

LyraNet is an AI-driven framework for exoplanet detection using stellar flux time series. The project benchmarks multiple methods for anomaly detection and candidate classification, while adhering to Responsible and Explainable AI principles.

✨ Project Overview

Exoplanet discovery relies on analyzing stellar light curves (FLUX time series) for periodic dips caused by planetary transits. LyraNet automates this process with two main stages:

Anomaly Detection (Flux Analysis & Candidate Detection)

PCA Reconstruction

PCA Mahalanobis Distance

Autoencoders

Candidate Classification (Confirmed vs False Positives)

Random Forest

Histogram-based Gradient Boosting (HistGB)

CatBoost

XGBoost

📊 Features

Flux Preprocessing: Denoising, normalization, and candidate signal detection.

Benchmark Models: Multiple anomaly detection & classification algorithms compared.

Visualizations:

Flux reconstructions

Residuals & anomalies

Confusion matrices & ROC curves

Explainability:

Feature Importance (tree-based models)

SHAP analysis for local and global interpretability

Responsible AI: Transparent workflows, interpretable models, and reproducible experiments.

🛠️ Tech Stack

Python

Scikit-learn (PCA, Random Forest, HistGB)

CatBoost, XGBoost

TensorFlow / PyTorch (Autoencoders)

SHAP (Explainability)

Matplotlib / Seaborn (Visualizations)
