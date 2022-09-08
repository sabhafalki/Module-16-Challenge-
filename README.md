# Module-16-Challenge  Amazon_Vine_Analysis
# Overview of Project #
The purpose of this Project is to analyze Amazon reviews form paid Amazon Vine program to determine if there is any bias favorable reviews from Vine members.The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We are using PySpark to perform the ETL process to extract the dataset focused on the US reviews for wireless products. 

The analysis consisted of the following:
1. Perform ETL on Amazon Wireless Product Reviews.
2. Determine Bias of Vine Reviews.

# Resources #
Software: JGoogle Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS<br>
Data Sources: Amazon Wireless review datasets

# Results #
### How many Vine reviews and non-Vine reviews were there? ###
### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? ###
### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? ###


![Easy_Ensemble_AdaBoost_Classifier](/Image/Easy_Ensemble_AdaBoost_Classifier.png)

# Summary #
From our analysis, we were able to conclude that the following:
1. This analysis is trying to find the best model that can detect if a loan is high risk or not. Becasue of that, we need to find a model that lets the least amount of high risk loans pass through undetected.
2. When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model.
3. The Easy Ensemble AdaBoost Classifier is the best model for the Credit_Risk_Analysis with 93% Accuracy Score.
4. The most weakest model in predicting the credit card risk is undersampling method which shows the lowest f1 score.

