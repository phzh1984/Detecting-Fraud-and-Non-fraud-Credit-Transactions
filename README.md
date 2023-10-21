# Detecting-Fraud-and-Non-fraud-Credit-Transactions

Introduction

This dataset contains credit card transactions made by European cardholders in September 2013. The primary goal of this dataset is to enable credit card companies to recognize and prevent fraudulent credit card transactions, ensuring that customers are not charged for unauthorized purchases.

The dataset is highly unbalanced, with a vast majority of transactions being non-fraudulent. It is important to note that the positive class (frauds) only accounts for approximately 0.172% of all transactions, making this a challenging problem for machine learning models.

Dataset Details

Transactions: The dataset includes transactions that occurred over a period of two days.

Frauds: There are 492 fraudulent transactions out of a total of 284,807 transactions.

Features

The dataset primarily consists of numerical input variables resulting from Principal Component Analysis (PCA). Unfortunately, the original features and additional background information are not provided due to confidentiality concerns. Here are the primary features in the dataset:

Time: The time elapsed in seconds between each transaction and the first transaction in the dataset.

Amount: The transaction amount, which can be used for cost-sensitive learning.

V1, V2, ..., V28: Principal components obtained through PCA transformation.

The target variable is:

Class: A binary response variable, taking a value of 1 in case of fraud and 0 for genuine transactions.
