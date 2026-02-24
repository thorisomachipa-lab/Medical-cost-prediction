# Medical-cost-prediction


# Project Overview

This project focuses on predicting individual medical insurance costs using demographic and health-related features. The objective was to build a regression model capable of estimating healthcare expenses accurately to support insurance planning and financial risk assessment.A Multiple Linear Regression model was selected due to its interpretability and effectiveness in modeling relationships between continuous variables.

# Objective

*Build a regression model to estimate medical insurance charges
*Identify key cost-driving factors
*Evaluate model performance using appropriate error metrics
*Interpret results to support data-driven insurance decisions

# Dataset

*The dataset includes demographic and health-related features such as:
*Age
*Gender
*BMI
*Number of Dependents
*Smoking Status
*Region
*Target variable:Medical Insurance Charges (continuous variable)

# Methodology
# Data Preparation

*Performed exploratory data analysis (EDA)
*Analyzed correlations between predictors and insurance charges
*Encoded categorical variables
*Split data into training and testing sets

# Model Selection

*A Multiple Linear Regression model was chosen because:It provides interpretable coefficients,It quantifies the impact of each feature on cost,It performs well for structured tabular data

 # Model Evaluation

The model was evaluated using:Mean Squared Error (MSE),Root Mean Squared Error (RMSE),Mean Absolute Error (MAE),R² Score

# Results

The model achieved the following performance:
*MSE: 39,435,416.86
*RMSE: 6,279.76
*MAE: 4,371.68
*R² Score: 76%

# Key Learnings

*Linear regression remains a strong baseline model for cost prediction.
*Outliers significantly influence squared-error metrics.
*Feature interpretation is critical in financial and insurance applications.
*Multiple models should be compared to improve fairness, reliability, and predictive accuracy.

# Technologies Used :Python,NumPy,Pandas,Matplotlib,scikit-learn

This project demonstrates the practical application of regression modeling in insurance analytics. By identifying cost-driving factors and evaluating predictive accuracy, the model provides meaningful insights that can support pricing strategies and financial planning in healthcare insurance systems.
