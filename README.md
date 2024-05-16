# Credit-Risk

Background

In this project, we aim to develop a model for assessing loan risk using historical lending data from a peer-to-peer lending services company. The objective is to build a model that can accurately predict the creditworthiness of borrowers, distinguishing between healthy loans (label 0) and high-risk loans (label 1).

Split the Data into Training and Testing Sets

Read the data from lending_data.csv into a Pandas DataFrame.
Create labels (y) from the "loan_status" column, where 0 signifies a healthy loan and 1 indicates a high-risk loan.
Create features (X) DataFrame from the remaining columns.
Split the data into training and testing datasets using train_test_split.
Create a Logistic Regression Model with the Original Data

Fit a logistic regression model using the training data (X_train and y_train).
Predict the labels for the testing data (X_test) using the trained model.
Evaluate the model's performance:
Generate a confusion matrix.
Print the classification report.
Answer the question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Write a Credit Risk Analysis Report

Overview of the Analysis:
The purpose of this analysis is to develop a machine learning model that accurately predicts loan risk based on historical lending data. By assessing the creditworthiness of borrowers, the model aims to aid the lending company in making informed decisions to minimize default risks.

Results:

Accuracy Score: The accuracy score measures the overall correctness of the model's predictions.
Precision Score: Precision indicates the proportion of true positive predictions out of all positive predictions made by the model.
Recall Score: Recall measures the proportion of actual positives that were correctly identified by the model.
Summary:
The logistic regression model exhibits high performance in predicting healthy loans and high-risk loans. It demonstrates high precision, recall, and accuracy for healthy loans, indicating robustness in identifying low-risk borrowers. Additionally, the model shows reasonable precision and recall for high-risk loans, suggesting its effectiveness in flagging potentially risky borrowers. Since there is a larcg gap between the high- risk loans and healthly loans, I would recommend deploying this model for assessing loan risk as it provides reliable predictions for the lending company to make informed decisions but I would recommend balancing the data to similar # of cases.


