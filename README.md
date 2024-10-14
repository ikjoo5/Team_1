# Team_1

Mentor: John Oh, Arden Kim  
Member: Beomseong Kim, Ikjoo Oh

## Table of Contents
1. [Overview](#overview)
2. [Problem Statement](#Problem_Statement)
3. [Data Description](#Data_Description)
4. [Data Preprocessing](#Data_Preprocessing)
5. [Exploratory Data Analysis](#Exploratory_Data_Analysis)
6. [Model Selection](#Model_Selection)
7. [Model Training and Evaluation](#Model_Training_and_Evaluation)
8. [Hyperparameter Tuning](#Hyperparameter_Tuning)
9. [Conclusion](#Conclusion)

## Overview

This is a Data Science project by Beomseong Kim and Ikjoo Oh under the guidance of mentors John Oh and Arden Kim. 

## Problem Statement

The objective of this project is to predict whether a customer will leave the bank based on historical data. Understanding the predictors of customer churn can help the bank in designing effective retention programs and improving customer satisfaction.

## Data Description

1. CreditScore — Customer credit score
2. Geography — Customer location
3. Gender — Gender of the customer
4. Age — Customer age
5. Tenure — Duration of the customer relationship with the bank
6. Balance — Account balance
7. NumOfProducts — number of products that a customer has purchased through the bank.
8. HasCrCard — denotes whether or not a customer has a credit card
9. IsActiveMember — Indicator of active membership status
10. EstimatedSalary — Customer Salary
11. Complain — Indicator of customer complaints
12. Satisfaction Score — Score provided by the customer for their complaint resolution
13. Card Type — Type of card hold by the customer.
14. Points Earned — Points earned by the customer through credit card usage
15. **Exited** — **Target feature** that indicate whether the customer left the bank

- Target Variable
  - Exited: `1` = the customer left, `0` = the customer stayed

- Unneeded Variables
1. RowNumber - indicates the row number and this feature doesn't affect analysis
2. CustomerId - A random identifier for customers, which also doesn't influence customer churn
3. Surname - The customer's surname has no impact on their decision to leave the bank

## Data Preprocessing

- Remove irrelevant features: `RowNumber`, `CustomerId`, `Surname`
- Handle missing values: all columns are free with missing values
- Feature Encoding: We need to convert features like `Geography`, `Gender`, `NumberOfProducts`, `HasCrCard`, `Tenure`, `IsActiveMember` using one-hot encoding or label encoding.

## Exploratory Data Analysis

## Model Selection

## Model Training and Evaluation

## Hyperparameter Tuning

## Conclusion


