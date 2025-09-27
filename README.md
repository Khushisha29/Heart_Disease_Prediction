# Heart_Disease_Prediction

This repository contains a Jupyter Notebook that demonstrates a complete machine learning workflow to predict the presence of heart disease. The project uses a dataset containing various health metrics and applies several classification algorithms to build and evaluate a predictive model.

# Project Overview

The primary goal of this project is to accurately predict whether a person has heart disease based on their health data. The notebook covers the following key stages of a machine learning pipeline:

Data Loading and Cleaning: The dataset is loaded and prepared for analysis. This includes handling missing values, which are converted from '?' to NaN and then dropped.

Exploratory Data Analysis (EDA): The data is visualized to understand the distribution of features, the relationships between them, and the characteristics of the target variable.

Data Preprocessing: Features are prepared for model training. This involves handling categorical data using one-hot encoding, and scaling numerical features to ensure they contribute equally to the models.

Model Building and Evaluation: Several supervised learning models are trained and tested on the data, including:

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree

Random Forest

Naive Bayes

Logistic Regression

Performance Metrics: The models are evaluated using various metrics, including accuracy, precision, recall, and F1-score. The notebook also generates confusion matrices to provide a clear visual representation of each model's performance.
