# Breast Cancer Classification using Logistic Regression

## Overview
In this project, we build a machine learning model to classify breast cancer tumors as either benign or malignant based on several features. We use logistic regression as our model and fine-tune its hyperparameters using randomized search cross-validation. We then evaluate our final model's performance using metrics like accuracy, precision, recall, and F1 score.

## Data
The dataset we use is the Breast Cancer Wisconsin Diagnostic dataset, which contains 569 samples of tumor biopsies with 30 features each. The target variable is a binary classification of the tumor as either malignant or benign.

## Model Training and Evaluation
We begin by exploring and visualizing the data to gain insights. We then split the data into training and testing sets and use logistic regression as our model, achieving an accuracy of 96.49%. We evaluate our model's performance using a confusion matrix and calculate metrics like precision, recall, and F1 score.

We then fine-tune our model's hyperparameters using randomized search cross-validation and evaluate its performance again. Our final model achieves an accuracy of 97.37%, with improved F1 score and the same recall.

## Predicting New Observations
We can use our final model to predict whether new observations are benign or malignant. To do this, we transform the new observations using the same transformation we used on our training data, then input them into our final model to get a prediction.

## Conclusion
This project demonstrates the use of logistic regression and hyperparameter tuning for binary classification tasks. The model we developed can be applied in the real world to help diagnose breast cancer and assist medical professionals in making informed decisions.
