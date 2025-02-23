# PHASE-3-PROJECT
SYRIATEL, A TELECOMMUNICATIONS COMPANY

## PROJECT OVERVIEW
This project aim to build a model that will predict whether a customer is likely to leave SyriaTel soon.
The dataset i used its [here(https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)]
## PROBLEM STATEMENT
SyriaTel, a telecommunications company, is dealing with a critical concern which is customer churn. This poses threats to revenue, and deepens the issue of long-term sustainability. They are presented with the task of determining which customers are most likely to stop using their services, as well as understanding the reasons why these choices are made so that the company can address these concerns.
##  MAIN OBJECTIVES¶
To analyze customer behaviour,call usage and the interaction with customer services inorder to discover factors contributing to customer churn behaviour
### SPECIFIC OBJECTIVES
1.	Identify how the number of customer service interactions relates to the probabilities of customer churn for your business.
2.	Examine the elements that lead to customer churn and estimate the clients poised to exit.
3.	To examine customer behavour by analyzing day,night calls and their correlation to churn
4.	To identify the relationship between the charge and the charge both during the day and the night
5.	To identify if customers from international calls are likely to churn more
6.	To identify the relationship between the day/night minutes and there charge
## DATA UNDERSTANDING
The following activities are conducted:
1. Import the relevant libraries
2. Loading the data set
3. Checking the head and tail to determine if they are corrupted or not
4. Checking the shape,dtypes and info
5. Checking the statistical summary
## DATA PREPARATION
They include the following activities:
1. checking the unique values in each categorical columns
2. checking the missing values.
3. checking for duplicates
4. dropping unnecessary columns
## EDA
I carried out several analysis including univariate,bivariate and multivariates.
The analysis between the count of churn showed that it was not balanced.
## MODELING
I performed 2 classification modelling that is:
1. Logistic Regression 
2. Decision Tree
### Logistic Regression 
Under logistic regression I was able to do regression with unbalanced class and balanced class.In the unbalanced class I was able to get high accuracy of 89% while in the balanced I was able to get an accuracy of 48%.
### Decision tree using hyperparameter tuning
I was able to perform decision tree using hyperparameter and got an accuracy of 85%
##  EVALUATION
My best model is decision trees because of high accuracy since logistic has high accuracy but the class is not balanced.

