# Fraud Risk Classification using Machine Learning

## Overview

This project focuses on building a supervised machine learning model to classify fraud risk based on transaction data. The classification process uses labeled data derived from the previous clustering stage, allowing the model to learn patterns and predict fraud risk categories.

## Dataset

The dataset used in this project was obtained from Google Drive.

Dataset link: [Google Drive Dataset Link](https://docs.google.com/spreadsheets/d/e/2PACX-1vTbg5WVW6W3c8SPNUGc3A3AL-AG32TPEQGpdzARfNICMsLFI0LQj0jporhsLCeVhkN5AoRsTkn08AYl/pub?output=csv)

## Objectives

* Prepare the dataset for classification modeling.
* Perform data preprocessing and feature engineering.
* Split the dataset into training and testing data.
* Build machine learning classification models.
* Evaluate model performance using classification metrics.
* Improve model performance through tuning and comparison.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Methodology

The project begins with loading the dataset and checking the data quality. Preprocessing steps are then applied to prepare the data for machine learning, including handling missing values, encoding categorical variables, and scaling features if required.

After preprocessing, the dataset is divided into training and testing sets. Several classification models are trained and evaluated to determine which model provides the best performance. The evaluation is performed using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

## Evaluation Metrics

The model performance is evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Result

The classification model successfully learned patterns from the dataset and was able to classify fraud risk categories based on transaction-related features. The evaluation results show that the model can be used as a basic approach for fraud risk prediction.

## Conclusion

This project demonstrates the implementation of supervised machine learning for fraud risk classification. By using data generated from the clustering process, the classification model can help predict fraud risk categories and support further fraud detection analysis.
