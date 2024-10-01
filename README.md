# Heart Disease Prediction - DSN Bootcamp 2024 Qualification Hackathon

<p align="center">
<img src="images/heart_disease.jpg" alt="Heart Disease" height=312 width=820/>
</p>

## PROBLEM STATEMENT

> Heart disease is one of the leading causes of global mortality. Early detection is crucial for improving patient outcomes and halting its progression. This challenge aims to develop a cost-effective and efficient method for assessing heart disease risk using readily available patient information.

> The objective of this challenge is to design and build a sophisticated predictive model capable of accurately determining the probability of an individual having heart disease.

## Table of Contents

- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Selection and Training](#model-selection-and-training)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Ensemble Learning](#ensemble-learning)
- [Cross-Validation](#cross-validation)

## Data Preprocessing

<p align="center">
<img src="images/data_preprocessing.png" alt="Data Preprocessing" height=150 width=820/>
</p>

- Cleaning column names for consistency
- Handling missing values
- Encoding categorical variables using one-hot encoding
- Normalizing numerical features using StandardScaler

## Feature Engineering

<p align="center">
<img src="images/feature_engineering.png" alt="Feature Engineering" height=150 width=820/>
</p>

- Identifying and using relevant features for model training
- Creating new features if applicable (not explicitly mentioned in the notebook)

## Model Selection and Training

<p align="center">
<img src="images/model_selection.png" alt="Model Selection" height=150 width=820/>
</p>

- Implementing multiple models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - CatBoost
- Evaluating models using various metrics: Accuracy, Recall, F1-score, and AUC

## Hyperparameter Tuning

<p align="center">
<img src="images/hyperparameter_tuning.png" alt="Hyperparameter Tuning" height=150 width=820/>
</p>

- Utilizing Optuna for hyperparameter optimization of CatBoost and XGBoost models
- Defining search spaces for key hyperparameters
- Optimizing for accuracy using cross-validation

## Ensemble Learning

<p align="center">
<img src="images/ensemble_learning.png" alt="Ensemble Learning" height=150 width=820/>
</p>

- Implementing a Voting Classifier to combine the strengths of the best-performing models
- Using soft voting with weighted predictions
- Combining CatBoost, XGBoost, and Logistic Regression models

## Cross-Validation

<p align="center">
<img src="images/cross_validation.png" alt="Cross-Validation" height=150 width=820/>
</p>

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
