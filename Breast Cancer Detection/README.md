# Breast Cancer Prediction

## Introduction

This project aims to determine the accuracy of predicting whether a patient's breast cancer is malignant or benign. We will be using the Breast Cancer Wisconsin (Diagnostic) Data Set from Kaggle, which consists of 569 samples of malignant and benign breast cancer tumor observations. We will apply machine learning algorithms to this dataset and select the one that gives the best accuracy and precision in predicting the diagnosis of breast cancer.

## Data Source

The dataset used in this project is available on Kaggle and can be found at: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data. The data is in CSV format and contains the following columns:

* ID number
* Diagnosis (M = malignant, B = benign)
* 30 features with numerical values

## Methodology

We will follow these steps to build our machine learning model:

1. Importing necessary libraries and dataset
2. Exploratory data analysis (EDA)
3. Data preprocessing
4. Splitting the dataset into train and test sets
5. Training and evaluating the model
6. Tuning hyperparameters for improved performance
7. Finalizing the model and making predictions on new data

## Libraries Used

The following libraries were used in this project:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Results

After performing exploratory data analysis and preprocessing the data, we applied two machine learning algorithms: logistic regression and random forest. Based on the evaluation metrics and cross-validation results, it appears that our logistic regression model performed slightly better than the random forest model. While the random forest model had a high accuracy score of 0.96, its precision score was perfect (1.00) while its recall score was relatively low (0.88), indicating that the model had a higher false negative rate. On the other hand, the logistic regression model had high scores for all evaluation metrics, with an accuracy of 0.97, a precision of 0.98, and a recall of 0.95.

In addition, the logistic regression model is a simpler model compared to the random forest model, which could potentially result in better generalization and interpretation. Therefore, we decided to finalize our model as logistic regression.

## Conclusion

In conclusion, we were able to build a machine learning model using logistic regression to predict the diagnosis of breast cancer with an accuracy of 98.25%. The model could potentially be used by healthcare professionals to make more accurate predictions and improve patient outcomes.
