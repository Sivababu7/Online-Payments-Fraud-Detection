# Online-Payments-Fraud-Detection

## Introduction

The adoption of digital payment methods has undoubtedly improved the convenience of making payments. However, this has also led to a surge in fraudulent activities related to online payments. Payment fraud can occur with any payment system, particularly when credit cards are used to make payments. Therefore, it is crucial for credit card companies to identify and prevent online payment frauds to safeguard their customers from being billed for goods and services they never authorized. This article aims to provide insights into detecting online payment fraud through the use of machine learning techniques with Python programming.

## Online Payment Fraud Detection with Machine Learning

To employ machine learning in the detection of online payment fraud, it is imperative to train a machine learning model to classify payments as fraudulent or non-fraudulent. This necessitates obtaining a dataset that encompasses information on online payment fraud to gain insight into the nature of transactions that are susceptible to fraudulent activities. In this regard, a suitable dataset was collected from Kaggle, which contains comprehensive historical data on fraudulent transactions. This dataset can be leveraged to identify and flag fraudulent online payments. The dataset comprises various columns that contain relevant information on fraudulent transactions.
This project aims to provide insights into detecting online payment fraud through the use of machine learning techniques with Python programming. We’ll train a Decision Tree model to classify payments as fraudulent or non-fraudulent.
## Dataset
To employ machine learning in the detection of online payment fraud, we need a dataset that encompasses information on fraudulent transactions. For this project, we’ll use a suitable dataset collected from Kaggle, which contains comprehensive historical data on fraudulent transactions. The dataset comprises various columns, including:

Step: A unit of time that represents one hour. This refers to the time at which an online transaction occurred.

Type: Refers to the type of online transaction that took place (e.g., purchase, transfer, etc.).

Amount: The amount of money involved in the transaction (in any currency, such as USD, EUR, or GBP).

NameOrig: The name of the customer who initiated the transaction (sender).

OldbalanceOrg: The balance in the customer’s account before the transaction took place.

NewbalanceOrig: The balance in the customer’s account after the transaction took place.

NameDest: The name of the recipient of the transaction (receiver).

OldbalanceDest: The balance in the recipient’s account before the transaction took place.

NewbalanceDest: The balance in the recipient’s account after the transaction took place.
