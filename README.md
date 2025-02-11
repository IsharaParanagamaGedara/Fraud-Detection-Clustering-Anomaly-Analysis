# 🚨 Fraud Detection: Clustering & Anomaly Analysis

## Overview

This project leverages clustering and anomaly detection techniques to identify fraudulent transactions within a dataset. It employs various machine learning algorithms to uncover patterns that may indicate fraud.

## Features

- **Data Exploration**: Comprehensive analysis of transaction data, including distributions of transaction amounts, customer ages, and login attempts.
- **Clustering Analysis**: Utilizes K-means and DBSCAN clustering to group similar transactions together and identify outliers.
- **Anomaly Detection**: Employs Isolation Forest to detect anomalies in the dataset.
- **Visualization Tools**: Includes plots for visualizing clusters, anomalies, and distributions using the 'YlOrBr' color palette.

## Dataset Overview 📊

The dataset used in this project contains detailed transaction data designed for analyzing potential fraudulent activities. It includes attributes providing insights into transactional behavior, customer profiles, and contextual details.

### Key Features:
- **🆔 TransactionID:** A unique identifier for each transaction.
- **👤 AccountID:** A unique identifier for the account associated with the transaction.
- **💰 TransactionAmount:** The monetary value of each transaction, varying from small expenses to large purchases.
- **📅 TransactionDate:** The date and time when the transaction occurred.
- **🔄 TransactionType:** Categorical value indicating whether the transaction was a 'Credit' or 'Debit'.
- **📍 Location:** The geographic location where the transaction took place.
- **📱 DeviceID:** A unique identifier for the device used to perform the transaction.
- **🌐 IP Address:** The IP address associated with the transaction.
- **🏪 MerchantID:** A unique identifier for merchants involved in the transaction.
- **📡 Channel:** Indicates the channel through which the transaction was conducted (e.g., Online, ATM, Branch).
- **💵 AccountBalance:** The balance remaining in the account after the transaction.
- **⏱️ TransactionDuration:** Duration of the transaction in seconds.
- **🔐 LoginAttempts:** The number of login attempts made before the transaction.

### Objectives:
1. 🕵️‍♂️ Fraud Detection: Use clustering algorithms and anomaly detection techniques to identify potential fraudulent transactions efficiently by highlighting outliers from normal patterns.

2. 📈 Behavioral Insights: Gain insights into typical vs. anomalous behavior through comprehensive analysis.


## Technologies Used

This project utilizes Python as its primary programming language along with several key libraries:

1. Pandas: For data manipulation and analysis
2. NumPy: For numerical computations
3. Matplotlib & Seaborn: For creating visualizations such as plots
4. Scikit-Learn: Provides implementations of K-means clustering, DBSCAN clustering, Isolation Forest

## Conclusion

This project showcases the power of machine learning techniques in detecting fraud within financial transaction datasets. By using clustering and anomaly detection methods, we can identify unusual patterns and flag potentially fraudulent activities. The combination of these techniques enhances fraud detection efficiency, making this project a practical application of machine learning in finance.


