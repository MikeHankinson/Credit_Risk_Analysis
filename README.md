# Credit_Risk_Analysis
----------------------------------------------------------------------------------

## Overview of Loan Prediction Risk Analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  In this assessment, machine learning models were applied to a large dataset in order to to build and evaluate loan risk factors.   Multiple models and sampling techniques were employed to train and evaluate unbalanced class data.

## Data Sources and Coding File
Data for analysis was proivided in a 91 kb csv file entitled **LoanStats_2019Q1.csv**.  The file is located in   [a zipped repository](/Module-17-Challenge-Resources.zip). The file must be unzipped in order to complete the analysis.  

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
2. Logistic Regression using oversampling with **SMOTE** algorithm
3. Logistic Regression using undersampling with **ClusterCentroids** algorithm
4. Logistic Regression using combined approach of over- and undersampling with **SMOTEENN** algorithm
5. Logistic Regression using **Balanced Random Forest Classifier**
6. Logistic Regression using **Easy Ensemble Classifier**

The model included nearly 100 features while predicting the loan status (target) as either high or low risk. 

Models are graded upon accuracy, precision, recall and F1.
- accuracy: The raio of correct number of predictions to total number of predictions. 
- precision: The ratio of what was accurately predicted as true to the total that were actually true. Measure of reliability of a classification.   
- sensitivity (recall): The ratio of true positives to true postives and false negatives.  Provides a measure of how many trues were correctly diagnosed. 
- F1: Takes both precision and recall into account to ultimately measure the accuracy of the model

The analysis was completed in two python files; [credit_risk_ensemble](credit_risk_ensemble.ipynb) and [credit_risk_resampling](credit_risk_resampling.ipynb)

## Results

### Logistic Regression Using Oversampling with RandomOverSampler Algorithm

 ![1](/Images_Readme/Random_Oversampling.PNG)
 
 z fds df
 
 ### Logistic Regression Using Oversampling Sampling with SMOTE Algorithm

 ![2](/Images_Readme/SMOTE_Oversampling.PNG)
 
 z fds df
 

### Logistic Regression Using Undersampling with ClusterCentroids Algorithm

 ![3](/Images_Readme/ClusterCentroids_Undersampling.PNG)
 
 z fds df
 
 ### Logistic Regression Using Combined Approach with SMOTEENN Algorithm

 ![4](/Images_Readme/SMOTEENN_Over_Under.PNG)
 
 z fds df
 
 ### Logistic Regression Using Balanced Random Forest Classifier

 ![5](/Images_Readme/Balanced_Random_Forest_Classifier.PNG)
 
 z fds df
 
 ![6](/Images_Readme/Top10_Features_Balanced_Forest.PNG) 
 
 dfssD
 
  ### Logistic Regression Using Easy Ensemble Classifier

 ![7](/Images_Readme/Easy_Ensemble_Classifier.PNG)
 
 z fds df
 
 ## Summary
 ASDXc
 
 Improve models
 1. Keep the top 5-10 influencing features while removing the others from the model.  
 
 
