# Creditcardfrauddetection
Credit Card Fraud Detection Project

This repository contains the code and documentation for a Credit Card Fraud Detection project using machine learning techniques. The project aims to build a robust model that can effectively identify fraudulent credit card transactions.

Introduction:

Credit card fraud is a significant concern for financial institutions and customers. Detecting fraudulent activities in real-time is crucial to prevent financial losses and protect customers from unauthorized charges. This project focuses on developing an accurate fraud detection system using machine learning algorithms.

Objective:

The main objective of this project is to build a machine learning model that can classify credit card transactions as genuine or fraudulent with high precision and recall. The model aims to minimize false negatives (fraudulent transactions misclassified as genuine) while maintaining a low false positive rate.

Dataset:

The dataset used for this project contains historical credit card transactions, labeled as genuine or fraudulent. The data is highly imbalanced, with the majority of transactions being genuine and only a small fraction being fraudulent.

Methodology:

Data Preprocessing: The data is preprocessed to handle missing values, normalize numerical features, and encode categorical variables.

Exploratory Data Analysis: An exploratory data analysis is performed to understand the distribution of genuine and fraudulent transactions and identify any patterns or anomalies.

Handling Class Imbalance: Since the dataset is imbalanced, various techniques are employed to address this issue. SMOTE (Synthetic Minority Over-sampling Technique) oversampling is used to create synthetic instances of the minority class, while random undersampling is also explored.

Model Selection: Several machine learning algorithms, including Decision Trees, Random Forest, XGBoost, and SVM, are trained and evaluated on the dataset to identify the best performing model.

Model Evaluation: The models are evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC curve to assess their performance.

Results:

The XGBoost model trained after SMOTE oversampling performed exceptionally well, achieving an accuracy of 99.98%, precision of 99.96%, recall of 100%, and F1-score of 99.98%. The ROC curve area was 1, indicating perfect classification performance.

Usage:

To use the code in this repository, follow these steps:

Clone the repository to your local machine.
Install the required libraries and dependencies using pip install -r requirements.txt.
Open the Jupyter notebook and run the code cells to reproduce the results.
Contributing:

Contributions to this project are welcome. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.






