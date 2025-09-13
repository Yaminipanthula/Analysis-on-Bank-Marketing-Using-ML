Analysis_on_Bank_Marketing_Using_ML

This project applies Machine Learning classification algorithms to analyze and predict the outcome of direct marketing campaigns of a Portuguese bank.
The goal is to predict whether a client will subscribe to a term deposit based on demographic, financial, and campaign-related features.

PROJECT OVERVIEW:

Dataset: Bank Marketing Dataset (45,211 instances, 16 features + target y).
Target Variable: y
yes: Client subscribed to the term deposit
no: Client did not subscribe

OBJECTIVE:
Clean and preprocess data
Perform Exploratory Data Analysis (EDA)
Apply ML models to classify client subscription outcome
Identify the best-performing model

Data Preprocessing
Dropped unnecessary columns.
Verified there were no missing values.
Handled outliers using the IQR method.
Converted categorical/object features into numeric format.
Encoded target variable: yes = 1, no = 0.

Exploratory Data Analysis (EDA)
Bar & Pie Charts: Subscription rates across job types, education levels, and months.
Line Charts: Subscription rates by age group and month.
Histograms: Distributions of numerical features (age, balance, campaign, duration, etc.).
Heatmap: Correlation between features and target variable.
Key Finding: duration of the last contact has the strongest positive correlation with subscription.

Best Model Performance:
After testing multiple models (Logistic Regression, KNN, SVC, Decision Tree, Random Forest, Gradient Boost, XGBoost, Bagging, AdaBoost, and ANN):

Random Forest Classifier

Accuracy: 0.9079 (90.8%) at 60:40 split
Artificial Neural Network (ANN)

Accuracy: 0.9078 (90.8%) at 80:20 split
Best Models: Random Forest Classifier and ANN, both achieving ~91% accuracy.
