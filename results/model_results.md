# Model Results

## PCA and Machine Learning Results

This file summarizes the initial machine learning results for EEG-based schizophrenia detection.

| Model | Accuracy | F1-score | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 0.810 | 0.811 | 0.837 |
| SVM | 0.798 | 0.795 | 0.893 |
| Random Forest | 0.785 | 0.794 | 0.887 |
| KNN | 0.762 | 0.723 | 0.874 |

## Notes

- Subject-wise cross-validation was used.
- PCA was used for dimensionality reduction and visualization.
- SVM achieved the highest ROC-AUC among the tested models.
