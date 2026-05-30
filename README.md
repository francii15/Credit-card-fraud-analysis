# Credit Card Fraud Analysis

## Project Overview

This project performs an exploratory data analysis (EDA) on credit card transaction data to uncover patterns associated with fraudulent activities and understand customer transaction behavior. The analysis focuses on identifying fraud trends, transaction amount distributions, time-based transaction patterns, and risk indicators through statistical analysis and data visualization.

The objective is to derive actionable business insights that can help financial institutions strengthen fraud monitoring strategies and minimize financial losses.



## Dataset Information
The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/code/minanabil11111212/credit-card-fraud-detection/input

Due to file size limitations, the dataset is not included in this repository.

The dataset contains anonymized credit card transactions made by cardholders, including:

* Transaction Time
* Transaction Amount
* Anonymized Features (V1–V28)
* Fraud Label (Class)

  * 0 → Legitimate Transaction
  * 1 → Fraudulent Transaction



## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn



## Project Workflow

### 1. Data Exploration

* Examined dataset structure and dimensions
* Checked data types and summary statistics
* Identified missing values and duplicates

### 2. Data Cleaning

* Removed duplicate records
* Verified data consistency
* Prepared data for analysis

### 3. Exploratory Data Analysis (EDA)

#### Fraud Distribution Analysis

* Compared fraudulent and legitimate transaction counts
* Calculated fraud percentage

#### Transaction Amount Analysis

* Distribution of transaction amounts
* Fraud vs non-fraud transaction amount comparison
* Outlier detection

#### Log Transformation Analysis

* Applied log transformation to reduce skewness
* Improved visualization of transaction amount patterns

#### Time-Based Analysis

* Transaction activity by hour
* Fraud occurrence across different hours
* Fraud rate by hour

#### Correlation Analysis

* Examined relationships between variables
* Identified feature dependencies

#### High-Value Transaction Analysis

* Segmented transactions into high-value and low-value groups
* Compared fraud rates across transaction categories

---

## Key Findings

* Fraudulent transactions represent only a very small percentage of total transactions, indicating severe class imbalance.
* Transaction amounts are highly right-skewed, with a small number of extremely large transactions.
* Log transformation improves the interpretability of transaction amount distributions.
* Fraud activity varies across different hours of the day, suggesting temporal fraud patterns.
* High-value transactions exhibit relatively higher fraud rates than low-value transactions.
* Most features show weak correlations, indicating that each variable contributes unique information about transaction behavior.



## Business Insights

* Even though fraud occurrences are rare, they pose significant financial risks.
* Monitoring high-value transactions can improve fraud prevention efforts.
* Time-based fraud patterns can help financial institutions allocate resources more effectively.
* Risk-based transaction monitoring can reduce losses while maintaining a smooth customer experience.



## Conclusion

The analysis demonstrates that fraudulent transactions exhibit distinct behavioral patterns in terms of transaction amounts and timing. By leveraging transaction amount analysis, time-based monitoring, and anomaly detection strategies, financial institutions can strengthen fraud prevention mechanisms and reduce exposure to financial risks.

---

## Future Enhancements

* Build an interactive dashboard using Power BI or Tableau
* Develop machine learning models for fraud detection
* Perform advanced anomaly detection analysis
* Create real-time fraud monitoring visualizations

---


