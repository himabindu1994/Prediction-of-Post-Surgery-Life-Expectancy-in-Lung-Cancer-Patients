# Prediction-of-Post-Surgery-Life-Expectancy-in-Lung-Cancer-Patients

## Table of contents
* About Project
* Abstract
* Libraries and Modules

## About Project
In this project, we developed Machine Learning models to determine Post-Operative Life Expectancy of Lung Cancer Patients. This project includes Data cleaning on the dataset (removing noise from the dataset), Visualization of features, performed Min-Max normalization on specific features as they are not scaled, performed Oversampling and Undersampling and created Ensemble model using Random Forest, SVM and KNN using best parameters. After applying different techniques, "KNN with Random Oversampling" turned out to be balanced model for the dataset. Ensemble increased performance by 1% but overall recall and precision went down. KNN with Random OverSampling has given: accuracy: 76%, Cross Validation Score=90% and AUC=51%

### Abstract

The data is dedicated to the classification problem related to the post-operative life expectancy in the lung cancer patients: class 1 - death within one year after surgery, class 2 - survival.

## Libraries and Modules Used
The following libraries were used in this project 
* Numpy
* Pandas
* Seaborn
* Matplotlib
* Random Forest
* K-Nearest Neighbors
* Gaussian Naive Bayes
* Decision Tree
* Logistic Regression
* Support Vector Machines