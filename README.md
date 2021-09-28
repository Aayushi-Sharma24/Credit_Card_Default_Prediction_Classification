# Credit_Card_Default_Prediction
## Problem Statement
A Taiwan-based credit card issuer wants to better predict the likelihood of default for its customers, as well as identify the key drivers that determine this likelihood. This would inform the issuer’s decisions on who to give a credit card to and what credit limit to provide. 
It would also help the issuer have a better understanding of their current and potential customers, which would inform their future strategy, including their planning of offering targeted credit products to their customers.
## Dataset Information
* No of observations – 30000
*	No of features  - 25

## Features information:
The dataset contains features like:
###Independent Variables
*	X1: Amount of the given credit 
*	X2: Gender (1 = male; 2 = female).
*	X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
*	X4: Marital status (1 = married; 2 = single; 3 = others).
*	X5: Age (year).
*	X6 - X11: History of past payment. (-1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.)
*	X12-X17: Amount of bill statement 
*	X18-X23: Amount of previous payment
### Target Variable
*	default.payment.next.month: default payment  (1=yes,0=no)

## Project WorkFlow
* Loading the Data
* EDA
* Handling Imbalanced Data
* Feature Engineering
* Feature Scaling
* Feature Selection
* Modelling
* Hyperparameter Tuning
* Evaluation of Models
* Model Selection

## Models Used:
1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier
4. SVC

## Conclusion
We have built predictive model for credit card agency to predict if a person would default on his/her payment of credit card.
We have performed feature engineering, feature selection, hyperparameter tuning to prevent overfitting and decrease error rate in the model.
Since the business nature of credit card default prediction requires model to have a high recall. Therefore, we selected XGBoost Classifier as our best model.
