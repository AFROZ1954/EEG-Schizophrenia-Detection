# EEG-Based Schizophrenia Detection

This repository contains my research work on EEG-based schizophrenia detection using signal processing and machine learning techniques.

## Project Overview

Schizophrenia is a complex neurological and psychiatric disorder that can affect brain activity patterns. EEG signals provide a non-invasive way to study brain dynamics and can be useful for computer-aided diagnosis.

In this project, EEG signals are analyzed using feature extraction and machine learning models to classify schizophrenia and healthy control subjects.

## Objectives

* To preprocess EEG signals
* To extract meaningful time-domain and statistical features
* To apply machine learning models for classification
* To evaluate model performance using standard metrics
* To build a clean and reproducible EEG analysis workflow

## Dataset

The dataset contains EEG recordings from schizophrenia patients and healthy control subjects.

Each EEG recording is processed channel-wise and segmented into epochs for feature extraction and classification.

## Methodology

1. EEG data loading
2. Signal reshaping
3. Epoching
4. Feature extraction
5. Train-test splitting
6. Subject-wise cross-validation
7. Machine learning classification
8. Model performance evaluation

## Machine Learning Models

* Logistic Regression
* Support Vector Machine
* Random Forest
* K-Nearest Neighbors

## Evaluation Metrics

* Accuracy
* Precision
* Sensitivity
* Specificity
* F1-score
* ROC-AUC

## Tools and Libraries

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Current Status
This repository is under development. I am currently organizing the code, results, and documentation for EEG-based schizophrenia detection.
## Results

Initial machine learning results using subject-wise cross-validation:

| Model | Accuracy | F1-score | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 0.810 | 0.811 | 0.837 |
| SVM | 0.798 | 0.795 | 0.893 |
| Random Forest | 0.785 | 0.794 | 0.887 |
| KNN | 0.762 | 0.723 | 0.874 |

The SVM model achieved the highest ROC-AUC among the tested models.

Detailed results are available in the [`results`](results/model_results.md) file.


