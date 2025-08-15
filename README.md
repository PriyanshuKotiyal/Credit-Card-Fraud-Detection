# Credit-Card-Fraud-Detection
This project focuses on building a machine learning model to detect fraudulent credit card transactions. Using a real-world dataset, we preprocess the data, train a classification model, and evaluate its performance in identifying fraud. This is a classic example of handling a highly imbalanced dataset.


# Overview
Credit card fraud is a major concern for financial institutions, leading to significant financial losses each year. This project implements a Logistic Regression model to classify transactions as either legitimate or fraudulent. The primary challenge addressed is the severe class imbalance present in the dataset, where fraudulent transactions are extremely rare compared to legitimate ones.

The complete workflow covers:

Data exploration and visualization

Data preprocessing and feature scaling

Handling the imbalanced dataset

Training a machine learning model

Evaluating the model's performance


# Dataset
The project uses the "Credit Card Fraud Detection" dataset, which is publicly available on Kaggle.

Source: Kaggle Credit Card Fraud Detection Dataset

Content: The dataset contains transactions made by European cardholders. Due to confidentiality, the original features have been transformed using Principal Component Analysis (PCA). The only features that have not been transformed are Time and Amount.

Key Feature: The dataset is highly imbalanced. The positive class (frauds) accounts for a very small percentage of all transactions.


# Technologies Used
Python 3.x

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Scikit-learn: For machine learning modeling, preprocessing, and evaluation.

Matplotlib & Seaborn: For data visualization.

Jupyter Notebook: For interactive development.


# Conclusion
This project successfully developed a Logistic Regression model to identify fraudulent credit card transactions. After addressing the severe class imbalance in the initial dataset through an under-sampling technique, the model was trained and evaluated on a new, balanced dataset.

The model's performance is highly effective, as demonstrated by the following accuracy scores:

Training Data Accuracy: 95.81%

Test Data Accuracy: 93.91%

The model achieved an accuracy of approximately 93.91% on the test data, which consists of data the model has never seen before. This strong result indicates that the model is highly capable of correctly classifying transactions. The close alignment between the training and test accuracy scores suggests that the model generalizes well and is not overfitting to the training data. Therefore, the trained Logistic Regression model is a reliable and accurate solution for this fraud detection task.
