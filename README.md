# Credit-risk-analysis


Credit Risk Analysis with Machine Learning: Predicting Default Risk Using XGBoost, LightGBM, and CatBoost

Credit risk, the risk of clients failing to meet financial obligations, is a critical concern for financial institutions. To enhance risk assessment and minimize defaults, institutions like banks, investment firms, and fintech companies are increasingly turning to machine learning.

Dataset Link: http://dl.dropboxusercontent.com/s/xn2a4kzf0zer0xu/acquisition_train.csv?dl=0

In this project, we leveraged a dataset from Nubank, a data-driven Brazilian digital bank. It contains 43 features for 45,000 clients, with 'target_default' as the binary target variable. Data exploration revealed outliers and missing values, which were addressed in preprocessing.

We experimented with three gradient boosting algorithms: XGBoost, LightGBM, and CatBoost. Our primary goal was to balance precision and recall, minimizing both false negatives and false positives. XGBoost achieved a recall rate of 81% but had a high false positive rate of 56%. LightGBM and CatBoost performed better in terms of false positives (38% and 33%, respectively) but had weaker recall rates.

This project showcases the trade-off between precision and recall in credit risk analysis. While XGBoost excelled in identifying defaulters, LightGBM and CatBoost offered a lower false positive rate. The choice of model depends on the institution's risk tolerance and the emphasis placed on reducing false positives versus false negatives
