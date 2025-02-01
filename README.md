# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: MADHURI PANCHAKSHRI

*INTERN ID*: CT08JAI

*DOMAIN*: DATA ANALYSIS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

Credit Card Fraud Detection Project

Description

This project focuses on detecting fraudulent credit card transactions using machine learning. It leverages a logistic regression model to classify transactions as either legitimate or fraudulent based on their features. The dataset is highly imbalanced, so under-sampling is applied to balance the data and improve model performance.

Features
Data Preprocessing:
Handles missing values and performs exploratory data analysis (EDA).
Separates data into legitimate and fraudulent transactions for detailed analysis.
Class Balancing:
Uses under-sampling to create a balanced dataset for training.
Model Training:
Implements logistic regression for fraud detection.
Evaluation Metrics:
Measures training and testing accuracy.
Provides insights into model performance.

Highlights
Focus on addressing class imbalance through under-sampling.
Uses train_test_split with stratification to maintain class distribution.
Ensures data preparation for effective machine learning.
Technology Stack
Programming Language: Python
Libraries:
numpy, pandas for data manipulation
scikit-learn for machine learning and model evaluation
Dataset
The project uses a credit card transaction dataset containing:

Normal transactions labeled as 0
Fraudulent transactions labeled as 1
How to Use
Clone this repository:
git clone <repository-url>
Navigate to the project directory:
cd credit-card-fraud-detection
Install required dependencies:
pip install -r requirements.txt
Run the script:
python fraud_detection.py

Accuracy Scores:
Training accuracy
Testing accuracy
Future Improvements
Incorporate feature scaling for better model performance.
Experiment with advanced machine learning models (e.g., Random Forest, XGBoost).
Use alternative techniques like SMOTE for handling class imbalance.
Evaluate model performance using precision, recall, F1-score, and AUC-ROC.
