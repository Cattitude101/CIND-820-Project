# Predictive Analysis on Credit Card Defaults Based on Demographic Factors and Payment Behaviour
## Introduction
In the evolving landscape of financial transactions, credit cards have replaced cash, introducing contactless transactions but also escalating default risks. The frequency of credit card defaults is rising, particularly among specific demographics and influenced by limit allocations. A study in Surabaya explored the correlation between demographic factors and credit card usage behavior, employing Chi-squared tests and cross-tabulation. 
Another analysis compared data mining techniques for predicting credit card defaults, evaluating six models. This project aims to delve into credit card usage patterns, considering demographic factors, limits, and payment behavior, utilizing a substantial dataset for predictive analysis on influential factors in credit card defaults.
## Dataset
The dataset was collected from UCI Machine Learning Repository. The dataset includes a total of 23 variables and 30000 structured data points. The database presents factors such as:
* X1: Amount of the given credit (NT dollar)
* X2: Gender (1 = male; 2 = female).
* X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
* X4: Marital status (1 = married; 2 = single; 3 = others).
* X5: Age (year).
* X6 - X11: past payment history. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 9 = payment delay for nine months and above.
* X12-X17: Amount of bill statement (NT dollar September-April)
* X18-X23: Amount of previous payment (NT dollar September-April)
  
Dataset link: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
## User instrction:
This project used python 3.10.12 and the code files are in ipynb version.

## Project Structure

* Abstract

  * Introduction
  * Scope of the study
  * Research question
  * Methodology
  * The Dataset
  
* Literature Review

* Data Description

* Data Observation and cleaning

* Correlation Analysis

  * Heat map for Demographic variables and LIMIT_BAL
  * Heat map for Demographic variables and default payment on the next month
  * Data Balancing
* Principal Component Analysis
  * Feature Selection
* Data Analysis process
  * Modelling algorithms
    * Decision Tree
    * Logistic regression
    * Support Vector Machine (SVM)
* Model Evaluation and comparison
* Model Outcome Analysis
* Conclusion

## Project Question:
Predictability of credit card default based on spending pattern, demographic behaviour and limit allocation.

## Content 
* Data:
  * default of credit card clients.xls (raw data)
  * card_default_cleaned.csv (cleaned data)
* Code: 
  * Codes for data pre-processing and EDA
  * Codes for model run and model effectiveness
* Docs:
  * Abstract
  * Revised Abstract and Literature review
  * Final report 
