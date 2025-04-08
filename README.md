# Binary-Prediction-with-a-Rainfall-Dataset
Building a binary predictor for rainfall using for the 2025 Kaggle playground series

# Overview
This repository contains my solution for the Kaggle Playground Series - Season 5, Episode 3 competition. The challenge involved developing a model to predict the likelihood of rainfall based on provided meteorological data.
Also took a this opportunity to experiment with Pycaret

Competition Details
Objective: Develop a binary classification model to predict the probability of rainfall occurrence.​
Kaggle



Evaluation Metric: Area Under the Receiver Operating Characteristic Curve (AUC).​

Dataset: The dataset comprises various meteorological features collected over time, with the target variable indicating the presence or absence of rainfall.​
 
# My Approach 
Data Preprocessing:

Handled missing values appropriately.​

Encoded categorical variables using suitable techniques.​

Normalized/standardized numerical features to ensure uniformity.​


# Feature Engineering:

Created new features based on domain knowledge to enhance model performance.​

Selected the most relevant features through exploratory data analysis and feature importance metrics.​


# Model Selection and Tuning:

Experimented with various classification algorithms, including Logistic Regression, Random Forest, and Gradient Boosting Machines.​

Performed hyperparameter tuning using cross-validation to prevent overfitting and improve generalization.​

# Evaluation:

Assessed models based on AUC scores.​

Validated the models using both training and validation datasets to ensure consistent performance.​

# Results
I achieved a final leaderboard position of 1152nd out of 4382 participants, placing me in the top 26% of the competition.​

Repository Structure
data/: Contains datasets used for training and evaluation.​

notebooks/: Jupyter notebooks detailing the exploratory data analysis, model development, and evaluation processes.​

models/: Saved model artifacts for reproducibility.​
