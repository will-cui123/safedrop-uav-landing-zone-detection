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
├── preprocessing/          # Image and mask preprocessing code
├── baseline_models/        # Random Forest / SVM / Logistic Regression code
├── cnn_model/              # CNN / U-Net model training code
└── README.md
