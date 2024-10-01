# Heart Disease Prediction - DSN Bootcamp 2024 Qualification Hackathon
<p align="center">
<img src="images/DSN-Data-Science-Nigeria-Logo.png" alt="Heart Disease" height=312 width=820/>
</p>


## PROBLEM STATEMENT
<p align="center">
<img src="images/heart disease.jpg" alt="Heart Disease" height=312 width=820/>
</p>

Heart disease is one of the leading causes of global mortality. Early detection is crucial for improving patient outcomes and halting its progression. This challenge aims to develop a cost-effective and efficient method for assessing heart disease risk using readily available patient information.

The objective of this challenge is to design and build a sophisticated predictive model capable of accurately determining the probability of an individual having heart disease.

## Table of Contents

- [Data Preprocessing](#data-preprocessing)
- [Model Selection and Training](#model-selection-and-training)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Ensemble Learning](#ensemble-learning)
- [Cross-Validation](#cross-validation)

## Data Preprocessing


- Cleaning column names for consistency
- Handling missing values
- Encoding categorical variables using one-hot encoding
- Normalizing numerical features using StandardScaler

## Model Selection and Training


- Implementing multiple models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - CatBoost
- Evaluating models using various metrics: Accuracy, Recall, F1-score, and AUC

## Hyperparameter Tuning


- Utilizing Optuna for hyperparameter optimization of CatBoost and XGBoost models
- Defining search spaces for key hyperparameters
- Optimizing for accuracy using cross-validation

## Ensemble Learning



- Implementing a Voting Classifier to combine the strengths of the best-performing models
- Using soft voting with weighted predictions
- Combining CatBoost, XGBoost, and Logistic Regression models

## Cross-Validation

s

- Employing Stratified K-Fold cross-validation to ensure robust performance estimation
- Handling potential data imbalance
- Assessing the model's generalizability

## Technologies Used

- Google Colab
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost, CatBoost
- Optuna

## Support

For any issues, suggestions, or queries, contact the maintainer at [your-email@example.com].
