# credit-risk-classification


The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers. 

The results:
Using the original imbalanced data, out of the 18,765 loan status's that are healthy (low-risk), the model predicted 18,663 as healthy correctly and 102 as healthy incorrectly.Out of the 619 loan status's that are non-healthy (high-risk), the model predicted 563 as non-healthy correctly and 56 as non-healthy incorrectly.
Using the oversampled data, out of the 18,765 loan status's that are healthy (low-risk), the model predicted 18,649 as healthy correctly and 102 as healthy incorrectly.Out of the 619 loan status's that are non-healthy (high-risk), the model predicted 615 as non-healthy correctly and 4 as non-healthy incorrectly.

Summary：I recommand using the oversampled data as it's more accurate. 

Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Predict a Logistic Regression Model with Resampled Training Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Calculate the accuracy score of the model.

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

