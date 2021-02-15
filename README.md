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



Using PySPark and Pandas, data was filtered, parsed and coalesced into a format to evaluate and determine if there exists a bias towards reviews written as part of the Vine program.  The evaluation was performed using a Google Colab Notebook, [Vine_Review_Analysis](Vine_Review_Analysis.ipynb). 

## Results
The figure below is the resulting Vine Summary Data Frame. Clearly, the volume of non-Vine reviews dwarfs that of those within the Vine program.  In order to determine bias, this study evaluated 5-Star reviews from within and outside the program.  With this data sample, there was a fairly significant difference of 5-Star grades for video games between the two data sub-sets.  Vine reviewers were more inclined to provide the highest rating (51.1% of reviews) as compared to non-vine reviewers (38.7% reviews). 

Further analysis should be performed for each star grade bucket (1-5) to further support the bias claim.  

 ![Sudy Summary](Vine_Summary_DF.PNG)

