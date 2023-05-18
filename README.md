# Credit Risk Default Risk using Machine Learning models: Accuracy 97%

Credit risk analysis is a crucial task for financial institutions as it enables them to determine the likelihood of default for potential borrowers. In this project, we analyze credit risk using logistic regression and other machine learning models on the American Express dataset. Our aim is to identify the best performing model in predicting credit card defaults and to determine the most important variables in credit risk analysis. Our study shows that XGBoost is the best performing model, with an accuracy of 0.97, precision of 0.91, F1-score of 0.91, AUC value of 0.92. Logistic Regression and other models also performed well, but not as well as XGBoost. Our findings indicate that the most significant variables in predicting credit card defaults are credit score, credit limit utilization, and number of days employed. Furthermore, we find that the age of the borrower is not a significant factor in predicting credit card defaults. This highlights the importance of considering other variables when analyzing credit risk. Our study provides practical implications for financial institutions in improving their credit risk analysis models. By using machine learning techniques such as XGBoost, they can better identify and manage credit risk, thus reducing their losses due to defaults.

## Dataset

The data used in this project comes from the **"AmExpert 2021 CODELAB - Machine Learning Hackathon"** competition hosted on the online coding platform, HackerEarth. The dataset can be accessed here, belongs to American Express, a company that provides customers with various payment products and services.

The original dataset consisted of 45528 rows and 19 columns, but for this study, a subset of 30000 rows and 19 columns was used. The target variable of our data frame is “credit_card_default”, which is a binary variable, whose values are 0 and 1. Credit card default risk is the chance that companies or individuals will not be able to return the money lent on time. Data frame has 6 categorical features and 13 numeric features.

Dataset can be download at: https://www.kaggle.com/datasets/pradip11/amexpert-codelab-2021

## EDA - Feature Engineering - Modeling
The detailed processes can be found in our notebook. 
You can access full here: https://github.com/maixbach/credit-risk-analysis-using-ML/blob/main/Credit%20Risk%20Analysis%20-%20Mai%20Xuan%20Bach.ipynb

## Experimental result
Model         | Accuracy
------------- | -------------
Logistic Regression | 0.9464
Random Forest | 0.9650
Decision Tree | 0.9663
LightGBM  | 0.9668
KNN | 0.9681
CatBoost | 0.9683
XGBoost | 0.9734

## Further developments
Future development in this area could focus on comparing the performance of other machine learning models such as Support Vector Machines, Neural Networks, and Deep Learning, among others. This can help in identifying which models perform best in different scenarios and can further improve the accuracy and precision of credit risk analysis. Additionally, future studies can explore the use of alternative data sources such as social media and other online activities to further improve credit risk analysis.
