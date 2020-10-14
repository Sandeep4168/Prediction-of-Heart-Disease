# Prediction-of-Heart-Disease
# Goal
Predicting the heart disease in a person based on the medical conditions such as Blood Pressure, Glucose content, BMI and life styles such as cigerettes per day. The data is collected from the open source Kaggle.com. This can help in determining the key feature which has higher impact in causing heart disease. 


# Steps
* Data reading from csv file
* Handling Missing Data
* Exploratory Data Analysis
* Fitting the ML model for Classification
* Evaluating the ML models
* Data insights 

# Results
For classification problem, the F1 score is found to be important than the accuracy, below are the models with their F1 score.
* Logistic regression: 0.92
* SVC: 0.92
* DecisionTree:0.86
* RandomForest:0.92
From the analysis it was seen that LogisticRegression, SVC performed better than the others.

## Feature importances
![pie]()

