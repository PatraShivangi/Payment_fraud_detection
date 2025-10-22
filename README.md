# Payment_fraud_detection
Random Forest model to detect credit card fraud (~67% accuracy). Handles data cleaning, missing values, and EDA. Performs well on normal transactions; detecting rare fraud is challenging due to class imbalance. Serves as a baseline for improving fraud detection models.

This project implements a Random Forest Classifier to detect credit card fraud using historical transaction data. The model achieved ~67% accuracy, with a precision of 0.33 and recall of 0.04 for fraudulent transactions. While it identifies normal transactions effectively (96% recall), detecting fraud remains challenging due to the class imbalance.

Workflow
Data Cleaning: Removed duplicates, handled missing values (mean/median for numerical, 'Unknown' for categorical), and dropped rows with missing target labels.
Exploratory Data Analysis (EDA): Examined class distribution, transaction trends, and patterns in card types and locations to understand factors influencing fraud.
Feature Engineering: Converted categorical features into numeric form using Label Encoding.
Modeling: Split data into training (80%) and testing (20%) sets; trained a Random Forest Classifier and evaluated performance using accuracy and classification metrics.

Key Insights:
Fraud detection is inherently difficult due to imbalanced data.
Thorough data preprocessing and EDA are essential for model reliability.
Random Forest serves as a strong baseline; further techniques like resampling can improve detection of rare fraud cases.
