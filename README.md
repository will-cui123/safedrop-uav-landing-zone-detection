# SafeDrop: AI-Powered UAV Landing Zone Detection and Guidance

This repository contains the code used for our ENGG2112 project. The project aims to identify landing zones for disaster-relief UAVs using image-based machine learning and semantic segmentation.

# Project Overview

The goal of this project is to support UAV landing decisions by classifying terrain into three safety classes:

- Safe
- Caution
- Unsafe

The final system uses a CNN segmentation model based on a U-Net-style architecture to produce pixel-level predictions. Baseline machine learning models were also tested for comparison.

# Repository Structure

```text
.
├── safedrop-cnn-model.ipynb/           # U-Net CNN final model code
├── random_forest_baseline.ipynb/       # Random Forest baseline code
├── knn_baseline.ipynb/                 # KNN baseline code
├── logistic_regression_baseline.ipynb  # Logistic Regression baseline code
├── svm_baseline.ipynb                  # SVM baseline code
├── ml_model_plots.ipynb                # Code for performance plots, including model comparisons, confusion matrix, etc.
└── README.md
