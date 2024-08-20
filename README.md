# Credit Status Classification Model

## Overview
This project hosts a machine learning model that predicts the credit status of individuals, categorizing them as either '0' (low credit risk) or '1' (high credit risk). The model uses several pieces of information (features) about each individual to make its predictions.

## Features Used
The model considers the following data points to predict credit status:
- Age
- Income Level
- Debt
- Loan Amount
- Employment Status

## Model Insights
### Feature Importances
![Feature Importances](plots/model_evaluation_plots.png)
This image shows the relative importance of each feature in determining credit status. Features that have a bigger impact on the prediction are shown with larger bars.

### Model Performance
![Model Performance](plots/xgboost_random_forst_feature_importance.png)
This image displays the model's accuracy, precision, and recall. Here's what each of these metrics means:

#### Accuracy
- **Accuracy** measures the overall correctness of the model. It reflects the percentage of total predictions (credit status as '0' or '1') that were correct.

#### Precision
- **Precision** tells us the accuracy of the predictions for each category ('0' or '1'). For example, when the model predicts that an individual is at high risk (1), precision is a measure of whether that prediction was correct.

#### Recall
- **Recall** is about completeness. For each actual category ('0' or '1'), it measures the percentage that was correctly identified by the model. For instance, for all individuals who are actually at high risk (1), recall tells us how many of these were correctly predicted as high risk by the model.

