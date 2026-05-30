# Fraud Risk Classification using Machine Learning

## Overview

This project focuses on building a supervised machine learning model to classify fraud risk based on transaction data. This classification project is a continuation of the previous clustering project, where the clustering results were used to generate labels for fraud risk categories.

In the previous stage, unsupervised learning was applied to group transaction data into several clusters based on similar patterns. In this project, those cluster-based labels are used as the target variable for classification modeling, allowing the model to learn patterns and predict fraud risk categories on new data.

Previous project: [Fraud Detection Customer Segmentation using Clustering](https://github.com/iyashaa/fraud-detection-customer-segmentation)

## Dataset

The dataset used in this project was obtained from Google Drive.

Dataset link: [Google Drive Dataset Link](https://docs.google.com/spreadsheets/d/e/2PACX-1vTbg5WVW6W3c8SPNUGc3A3AL-AG32TPEQGpdzARfNICMsLFI0LQj0jporhsLCeVhkN5AoRsTkn08AYl/pub?output=csv)

## Objectives

* Use cluster-based labels from the previous project as the target variable.
* Prepare the dataset for classification modeling.
* Perform data preprocessing and feature engineering.
* Split the dataset into training and testing data.
* Build machine learning classification models.
* Evaluate model performance using classification metrics.
* Improve model performance through tuning and comparison.

## Tools and Libraries

* Python
* Pandas
* Scikit-Learn
* Joblib
* Jupyter Notebook

## Methodology

This project begins by loading the dataset generated from the previous clustering process. The dataset already contains cluster-based labels that represent different fraud risk categories. These labels are then used as the target variable for supervised learning.

After loading the data, preprocessing steps are performed to prepare the dataset for machine learning. The dataset is then divided into training and testing sets. Several classification models are trained and evaluated to determine which model provides the best performance.

The models used in this project include Decision Tree and Random Forest. Model evaluation is performed using accuracy, precision, recall, F1-score, and classification report. Hyperparameter tuning is also applied using GridSearchCV and RandomizedSearchCV to improve model performance.

## Evaluation Metrics

The model performance is evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

## Result

The classification model successfully learned patterns from the cluster-based dataset and was able to classify fraud risk categories based on transaction-related features. The evaluation results show that the model can be used as a basic approach for fraud risk prediction.

## Conclusion

This project demonstrates how clustering results can be extended into a supervised machine learning task. By using labels generated from the previous clustering process, the classification model can help predict fraud risk categories and support further fraud detection analysis.
