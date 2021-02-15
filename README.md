# Credit_Risk_Analysis
----------------------------------------------------------------------------------

## Overview of Loan Prediction Risk Analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  In this assessment, machine learning models were applied to a large dataset in order to to build and evaluate loan risk factors.   Multiple models and sampling techniques were employed to train and evaluate unbalanced class data.

## Data Sources and Coding File
Data for analysis was obtained from an [Amazon AWS S3 data repository](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz).

## Analysis Methodology
Customer reviews were imported from an Amazon AWS S3 data repository into a user-specific AWS S3 account.  A database was created in pgAdmin and tied to an Amazon AWS RDS server.  Project data was extracted and transformed using a Google Colab Notebook, [Amazon_Reviews_ETL](Amazon_Reviews_ETL.ipynb).  

Using PySPark and Pandas, data was filtered, parsed and coalesced into a format to evaluate and determine if there exists a bias towards reviews written as part of the Vine program.  The evaluation was performed using a Google Colab Notebook, [Vine_Review_Analysis](Vine_Review_Analysis.ipynb). 

## Results
The figure below is the resulting Vine Summary Data Frame. Clearly, the volume of non-Vine reviews dwarfs that of those within the Vine program.  In order to determine bias, this study evaluated 5-Star reviews from within and outside the program.  With this data sample, there was a fairly significant difference of 5-Star grades for video games between the two data sub-sets.  Vine reviewers were more inclined to provide the highest rating (51.1% of reviews) as compared to non-vine reviewers (38.7% reviews). 

Further analysis should be performed for each star grade bucket (1-5) to further support the bias claim.  

 ![Sudy Summary](Vine_Summary_DF.PNG)

