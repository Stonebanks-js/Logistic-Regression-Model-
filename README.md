# Logistic-Regression-Model-
A model that tests dataset based upon the working of Logistic Regression and uses classification process to split the data.

This code snippet demonstrates the implementation of logistic regression for binary classification using the scikit-learn library in Python. Here's a breakdown of what the code does:

The necessary libraries are imported, including numpy, matplotlib.pyplot, and pandas.
The dataset is imported from a CSV file called 'Social_Network_Ads.csv' using pandas.
The dataset is divided into features (X) and the target variable (y).
The dataset is split into training and test sets using the train_test_split function from sklearn.model_selection.
Feature scaling is applied to standardize the features using the StandardScaler from sklearn.preprocessing.
A logistic regression model is created using the LogisticRegression class from sklearn.linear_model and trained on the training set.
A new prediction is made on a sample input ([30, 87000]) using the trained classifier.
Predictions are made on the test set, and the predicted and actual values are printed.
The confusion matrix and accuracy score are calculated using the confusion_matrix and accuracy_score functions from sklearn.metrics.
The training set results are visualized using a contour plot, displaying the decision boundary of the logistic regression model.
The test set results are visualized in a similar manner to evaluate the model's performance.
It's important to note that this code assumes the CSV file 'Social_Network_Ads.csv' exists and contains the appropriate data. The dataset should have two numerical columns (age and estimated salary) and a binary target variable.
