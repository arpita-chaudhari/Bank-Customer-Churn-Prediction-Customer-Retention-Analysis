# Bank Customer Churn Prediction

## Overview

Machine Learning project to predict bank customer churn and identify customer segments that may require retention efforts.

## Objectives

* Analyze customer churn patterns.
* Perform data cleaning and exploratory data analysis.
* Build and compare classification models.
* Identify important factors influencing churn.
* Derive business insights for customer retention.

## Dataset

The project uses the **Churn Modelling** dataset containing 10,000 customer records.

**Target:** `Exited` — 1 = Churned, 0 = Not Churned.

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest

## Evaluation

Models were compared using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

Confusion matrices and ROC curves were also analyzed.

## Key Analysis

* Churn by Geography
* Churn by Gender
* Age vs Churn
* Active Membership vs Churn
* Credit Score vs Churn
* Number of Products vs Churn
* Random Forest Feature Importance

## Tech Stack

**Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Google Colab**

## Repository Structure

```text
Bank-Customer-Churn-ML/
│
├── data/
│   └── Churn_Modelling.csv
│
├── Bank_Customer_Churn_Prediction.ipynb
├── README.
```
