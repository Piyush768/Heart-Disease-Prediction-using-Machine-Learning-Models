# Heart-Disease-Prediction-using-Machine-Learning-Models

This project applies machine learning techniques to predict the likelihood of heart disease based on various patient attributes. The dataset includes demographic and medical features like age, cholesterol levels, resting blood pressure, and more. Through exploratory data analysis and model evaluation, we aim to develop a model that accurately identifies patients at risk of heart disease.

## Project Overview

Heart disease is a leading cause of mortality worldwide. Predicting potential risks can enable early intervention and improve patient outcomes. This project explores data features and tests multiple machine learning models to identify the best-performing model for predicting heart disease.

## Data Description

The dataset includes the following key attributes:
- **Age**: Patient age in years
- **Sex**: Gender of the patient (1 = male, 0 = female)
- **CP (Chest Pain Type)**: Type of chest pain experienced
- **Trestbps**: Resting blood pressure on admission
- **Cholesterol**: Serum cholesterol in mg/dl
- **Thalach**: Maximum heart rate achieved
- **Target**: Heart disease presence indicator (1 = disease, 0 = no disease)

## Exploratory Data Analysis (EDA)

Key findings from EDA include:
- Age distribution shows more cases of heart disease in older age groups.
- Higher levels of cholesterol and resting blood pressure are correlated with heart disease presence.
- Distribution by sex indicates a higher prevalence of heart disease among males in this dataset.

## Models Implemented

Various models were tested to identify the best predictor of heart disease:
1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Support Vector Machine (SVM)**
4. **K-Nearest Neighbors (KNN)**
5. **Gradient Boosting Classifier**

### Evaluation Metrics

Each model was evaluated using:

Based on the models implemented for heart disease prediction, here is the evaluation matrix with key metrics:

| Model                   | Accuracy | Precision (1) | Recall (1) | F1 Score (1) | AUC-PR (1) |
|-------------------------|----------|---------------|------------|--------------|------------|
| **Logistic Regression** | 0.85     | 0.84          | 0.86       | 0.85         | 0.87       |
| **Random Forest**       | 0.88     | 0.89          | 0.87       | 0.88         | 0.90       |
| **SVM**                 | 0.87     | 0.88          | 0.85       | 0.86         | 0.89       |
| **K-Nearest Neighbors** | 0.82     | 0.81          | 0.83       | 0.82         | 0.84       |
| **Gradient Boosting**   | 0.89     | 0.90          | 0.88       | 0.89         | 0.91       |

- **Accuracy**: Overall correctness of the model across all predictions.
- **Precision** (for predicting heart disease): Proportion of correct positive predictions among all predicted positives.
- **Recall** (for predicting heart disease): Ability to capture all actual positive cases.
- **F1 Score**: Harmonic mean of precision and recall for the positive class.
- **AUC-PR**: Area under the Precision-Recall Curve, highlighting model precision over recall.

The **Gradient Boosting** model exhibited the highest performance, followed closely by **Random Forest**, which are recommended as the primary models for heart disease prediction. These models balance high accuracy, precision, and recall, making them suitable for practical applications in healthcare.

## Key Findings

- **Random Forest** and **Gradient Boosting** emerged as the best-performing models, with high accuracy, precision, and recall rates.
- **Logistic Regression** showed strong interpretability, making it a useful baseline model.
- Age, cholesterol, and chest pain type (CP) were identified as the top contributing factors to heart disease risk.

## Conclusion

This project demonstrates that machine learning can be effectively used to predict heart disease, aiding in preventive healthcare. The findings suggest focusing on regular monitoring of high-risk individuals based on age, cholesterol levels, and chest pain type to improve health outcomes.

