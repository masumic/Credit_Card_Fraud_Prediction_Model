**Project Overview
This project aims to predict credit card fraud using machine learning techniques on a dataset of credit card transactions.

I began with loading and cleaning the dataset, checking for missing values and performing exploratory data analysis to understand variable relationships. Feature importance is then assessed using the Gini Index, with a visualization created to highlight influential features. Next I trained two machine learning models, Random Forest and Naive Bayes, to classify transactions as fraudulent or legitimate. Finally, model accuracy is evaluated using confusion matrices, with Random Forest showing better performance.

**Libraries Used
caret, ranger, randomForest, e1071, rpart, rpart.plot, tidymodels

**Results
The Random Forest model performs slightly better in terms of prediction accuracy compared to Naive Bayes. Transaction amount, category, and transaction time were found to be strong predictors of fraud.
