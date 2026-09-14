# Bank-Customer-Churn-Prediction-Customer-Retention-Analysis

Project Overview

Customer churn is an important business problem for banks, as losing existing customers can negatively affect customer relationships and revenue.

This project uses Machine Learning to predict whether a bank customer is likely to churn and analyzes customer characteristics associated with churn.

The project combines Exploratory Data Analysis, data preprocessing, classification models, model evaluation, and business analysis to identify customer segments that may require targeted retention efforts.

Objectives
Analyze customer churn patterns using Exploratory Data Analysis.
Clean and preprocess customer data for Machine Learning.
Build classification models to predict customer churn.
Compare model performance using multiple evaluation metrics.
Identify important features associated with customer churn.
Derive business insights that can support customer retention strategies.
Dataset

The project uses the Churn Modelling dataset containing information about 10,000 bank customers.

The target variable is:

Exited — 1 indicates that the customer churned and 0 indicates that the customer did not churn.
Features Used
CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary

The columns RowNumber, CustomerId, and Surname were removed because they are identifiers and do not provide useful predictive information for the model.

Project Workflow
1. Data Exploration
Dataset structure and dimensions
Data types
Missing value analysis
Duplicate record analysis
Churn distribution
2. Exploratory Data Analysis

The following relationships were analyzed:

Churn by gender
Churn by geography
Age vs churn
Active membership vs churn
Credit score vs churn
Number of products vs churn
3. Data Preprocessing
Removed unnecessary identifier columns.
Separated features and target variable.
Applied one-hot encoding to categorical variables.
Split the dataset into training and testing sets.
Applied feature scaling for Logistic Regression.
4. Machine Learning Models

Three classification algorithms were implemented:

Logistic Regression
Decision Tree
Random Forest
5. Model Evaluation

The models were evaluated using:

Accuracy
Precision
Recall
F1 Score
ROC-AUC

Confusion matrices and ROC curves were also used to compare model performance.

6. Feature Importance

Random Forest feature importance was analyzed to identify the variables that contributed most to churn prediction.

7. Business Analysis

Customer segments were analyzed based on churn rates to identify groups that may require additional customer-retention efforts.

Business Insights

The analysis can help a bank identify customer segments with relatively higher churn rates and prioritize them for retention initiatives.

Potential applications include:

Identifying customers at higher risk of churn.
Prioritizing customers for retention campaigns.
Increasing engagement with inactive customers.
Monitoring customer segments with relatively high churn.
Using churn probabilities to support data-driven customer retention decisions.

The specific insights are based on the results generated in the notebook.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab
Repository Structure
Bank-Customer-Churn-ML/
│
├── data/
│   └── Churn_Modelling.csv
│
├── Bank_Customer_Churn_Prediction.ipynb
│
├── README.md
│
└── requirements.txt
How to Run
Clone or download this repository.
Open Bank_Customer_Churn_Prediction.ipynb using Jupyter Notebook or Google Colab.
Ensure that Churn_Modelling.csv is present inside the data folder.
Install the required dependencies:
pip install -r requirements.txt
Run the notebook cells sequentially.
Conclusion

This project demonstrates an end-to-end Machine Learning workflow for a business problem, covering data exploration, preprocessing, model development, evaluation, feature analysis, and business interpretation.

The approach can be used to identify customers who are potentially at higher risk of churn and support data-driven customer retention strategies.
