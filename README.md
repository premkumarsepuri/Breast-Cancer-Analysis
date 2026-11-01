# Breast-Cancer-Analysis
Exploratory data analysis and machine learning classification of breast  tumors as **malignant** or **benign**, Based on features computed from cell nucleus mesaurements

##Project Workflow
Data Cleaning and preprocessing
Exploratory data analysis(distributions, correlations)
feature scaling and selection
model training and evalution(PCA,Kcross vadliation, funetunning(grid CV)
comparing model performance

#model used
Logistic Regression

#Result
**Test set performance** (114 Samples):
Class - Precision - Recall - F1-Score Support
0(Bengin) |0.96| 0.99 | 0.97| 72|
1(Malignant) | 0.97| 0.93| 0.95| 42|

**Accuracy:** 96%
**Macro avg F1:** 0.96
**Best CV Accuracy:** 96.74%

## Predictive System
The notebook includes a predict_cancer() function that takes alist of feature values and returns a diagnosis(benign or malignant) using the trained pipeline

