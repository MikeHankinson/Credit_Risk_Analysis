# Credit_Risk_Analysis
----------------------------------------------------------------------------------

## Overview of Loan Prediction Risk Analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  In this assessment, machine learning models were applied to a large dataset in order to to build and evaluate loan risk factors.   Multiple models and sampling techniques were employed to train and evaluate unbalanced class data.

## Data Sources and Coding File
Data for analysis was proivided in a 91 kb csv file entitled **LoanStats_2019Q1.csv**.  The file is located in   [this zipped repository](/Module-17-Challenge-Resources.zip). The file must be unzipped in order to complete the analysis.  

## Analysis Methodology
Python, in Jupyter Notebook, was used to build and evaluate the models.  The supervised learning pattern used for each model included the following steps:  
1. Load data
2. Split data into targets and features
3. Split data into training and testing buckets
4. Fit/train the model with training data
5. Create predictions based upon developed model
6. Validate the model using testing data

A total of 6 models were developed and are as follows:
1. Logistic Regression using oversampling with **RandomOverSampler** algorithm
2. Logistic Regression using oversampling sampling with **SMOTE** algorithm
3. Logistic Regression using undersampling sampling with **ClusterCentroids** algorithm
4. Logistic Regression using combined approach of over- and undersampling with **SMOTEENN** algorithm
5. Logistic Regression using **BalancedRandomForestClassifier**
6. Logistic Regression using **EasyEnsembleClassifier**

The analysis was completed on two python files; [credit_risk_ensemble](credit_risk_ensemble.ipynb) and [credit_risk_resampling](credit_risk_resampling.ipynb)

## Results




 ![Sudy Summary](Vine_Summary_DF.PNG)

