# Customer Churn Prediction

## Project Overview
This repository contains a machine learning project aimed at predicting customer churn. The primary objective is to identify customers who are likely to discontinue their relationship with the company, thereby allowing for proactive retention strategies.
This project explores the dataset through data visualization and evaluates multiple classification algorithms to determine the most accurate and reliable model for predicting churn.

## Technologies and Libraries Used
The project is built using Python and relies on the following core libraries:
- **pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing and handling arrays.
- **Matplotlib**: For creating static, interactive, and animated visualizations.
- **Seaborn**: For statistical data visualization.
- **scikit-learn**: For machine learning model implementation, preprocessing, and evaluation metrics.

## Machine Learning Models Evaluated
To find the best performing algorithm for this dataset, the following classification models were implemented and compared:
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **Naive Bayes**

## Methodology
The project follows a standard machine learning pipeline:
- **Data Preprocessing:** Cleaning the dataset, handling missing values, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis (EDA):** Understanding data distributions and feature correlations using Matplotlib and Seaborn.
- **Model Training:** Splitting the data into training and testing sets, and training the five distinct classification models.
- **Evaluation and Comparison:** Assessing each model's performance using standard metrics such as Accuracy, Precision, Recall, F1-Score, and the Confusion Matrix to determine the most effective predictor of churn.