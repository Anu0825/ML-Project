# Arrhythmia Classification using ECG Data

A machine learning project for classifying ECG records into different arrhythmia categories using the **UCI Arrhythmia Dataset**.

The project focuses on handling **high-dimensional data and severe class imbalance** using **PCA** and **SMOTE**, followed by comparison of multiple machine learning classifiers.

## Dataset

- **Source:** UCI Machine Learning Repository — Arrhythmia Dataset
- **Samples:** 452
- **Features:** 279
- **Classes:** 16
- **Major challenge:** High dimensionality and severe class imbalance

The dataset contains ECG-related attributes along with basic patient information.

## Methodology

The project follows this pipeline:

UCI ECG Dataset
      ↓
Data Preprocessing
      ↓
EDA & Feature Analysis
      ↓
Missing Value Handling
      ↓
SMOTE Oversampling
      ↓
PCA (95% Variance)
      ↓
Model Training
      ↓
Model Comparison
      ↓
Performance Evaluation

## Key Findings

- PCA helped reduce the impact of high dimensionality and correlated features.
- SMOTE improved learning for minority classes.
- The complete pipeline demonstrates the effectiveness of combining **PCA and SMOTE** for high-dimensional, imbalanced ECG data.
