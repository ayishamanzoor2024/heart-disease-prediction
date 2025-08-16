# Heart Disease Prediction

## Project Overview
This project uses machine learning models to predict the presence of heart disease in patients based on various health indicators.

## Dataset
The dataset used in this project is a CSV file containing information about patient health metrics. The dataset is not included in this repository.

## Key Findings & Visualizations
* **Gender Distribution**: The dataset contains more male patients than female patients. (68.3% male vs 31.7% female) [cite_start][cite: 830, 831, 832]
* **Chest Pain Types**: The most common type of chest pain is asymptomatic (type 0). [cite: 849, 853]
* **Class Distribution**: The number of patients with heart disease is slightly higher than those without. (165 vs 138) [cite_start][cite: 865, 867]
**Feature Correlation**: The strongest positive correlation with heart disease is `cp` (chest pain), while the strongest negative correlations are `exang` (exercise-induced angina) and `oldpeak`. [cite: 733, 745, 747]

## Models Used
This project uses three different machine learning models:
1.  [cite_start]**Logistic Regression**: This model had an Area under ROC score of `0.88`[cite: 915].
2.  **Random Forest**
3.  **Linear SVM**

## Model Evaluation
* [cite_start]**Logistic Regression**: Achieved an average AUC score of 0.835 across 5-fold cross-validation. [cite: 988, 991, 996, 997, 999]
* [cite_start]**Deep Learning**: A TensorFlow model was trained and achieved a final test accuracy of `0.909`[cite: 981].
