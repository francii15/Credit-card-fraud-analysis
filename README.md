# Credit Card Fraud Detection using Machine Learning

##  Project Overview

This project focuses on building a machine learning model to detect fraudulent credit card transactions. Since fraud cases represent only a small fraction of all transactions, the dataset is highly imbalanced. The project applies data preprocessing, feature engineering, and SMOTE to improve the model's ability to detect fraudulent transactions while maintaining good overall performance.



#  Problem Statement

Credit card fraud is a major concern for financial institutions, leading to significant financial losses every year. Due to the highly imbalanced nature of transaction data, traditional machine learning models often fail to detect fraudulent transactions effectively. The objective of this project is to develop a reliable fraud detection model that accurately identifies fraudulent transactions while minimizing false negatives.

---

#  Objectives

* Perform Exploratory Data Analysis (EDA) to understand the dataset.
* Clean and preprocess the data for model training.
* Engineer relevant features to improve prediction performance.
* Train and compare multiple machine learning classification models.
* Handle class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
* Evaluate model performance using metrics designed for imbalanced datasets.
* Identify the best-performing model for fraud detection.

---

# Dataset Summary

* **Dataset:** Credit Card Fraud Detection
* **Target Variable:** `Class`

  * `0` → Legitimate Transaction
  * `1` → Fraudulent Transaction
* **Features:**

  * `Time` – Seconds elapsed since the first transaction.
  * `V1–V28` – Anonymized features generated using Principal Component Analysis (PCA).
  * `Amount` – Transaction amount.
* The dataset is highly imbalanced, with fraudulent transactions accounting for only a small percentage of all records.

---

#  Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

#  Machine Learning Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier
* AdaBoost Classifier

---

#  Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* PR-AUC Score
* Balanced Accuracy
* Matthews Correlation Coefficient (MCC)

---

#  Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing and Scaling
6. Train-Test Split
7. Baseline Model Training
8. Baseline Model Evaluation
9. Handle Class Imbalance using SMOTE
10. Model Evaluation after SMOTE
11. Performance Comparison
12. Conclusion

---

#  Key Highlights

* Performed comprehensive EDA to understand transaction patterns and class imbalance.
* Applied preprocessing and feature engineering to prepare the dataset.
* Compared multiple machine learning algorithms using appropriate evaluation metrics.
* Used SMOTE to balance the minority class in the training data.
* Evaluated models on the original test set to ensure unbiased performance assessment.
* Selected the best-performing model based on Recall, F1-score, PR-AUC, and ROC-AUC.






