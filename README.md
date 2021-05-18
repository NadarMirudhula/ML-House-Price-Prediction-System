# ML-House-Price-Prediction-System

## Group Members 
1. Mirudhula Nadar - 46
2. Varsha Sablani - 54
3. Surabhi Soni - 61

## Problem Statement
In this project we have used various regression algorithms to predict the price of house the dataset used for house prediction is related to the house price system in USA

## Dataset 
<p>The data.csv file in the repository is used to predict the House price.</p>
<p>For implementation of regression algorithms we have used all the attributes in the dataset to predict the price value.</p>

## Implementation
We have used 4 regression algorithms for prediction

### 1. Linear Regression
Linear regression is one of the easiest and most popular Machine Learning algorithms. It is a statistical method that is used for predictive analysis. Linear regression makes predictions for continuous/real or numeric variables such as sales, price, etc. Linear regression algorithm shows a linear relationship between a dependent (y) and one or more independent (x) variables, hence called as linear regression. Since linear regression shows the linear relationship, which means it finds how the value of the dependent variable is changing according to the value of the independent variable.

### 2. Decision Tree Regression
Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problems. It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome. 

### 3. Random Forest Regression
A Random Forest is an ensemble technique capable of performing both regression and classification tasks with the use of multiple decision trees and a technique called Bootstrap and Aggregation, commonly known as bagging. The basic idea behind this is to combine multiple decision trees in determining the final output rather than relying on individual decision trees.


### 4. Gradient Boost Regression
Gradient boosting is a machine learning technique for regression and classification problems, which produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees. When a decision tree is the weak learner, the resulting algorithm is called gradient boosted trees, which usually outperforms random forest. It builds the model in a stage-wise fashion like other boosting methods do, and it generalizes them by allowing optimization of an arbitrary differentiable loss function.

## Results
<p>We have calculated the Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE) for all the regression algorithms but that doesn't help much in comparing accuracy of each algorithm. So we decided to plot the bar graph for actual value vs predicted value from which we have concluded that Gradient Boost regressor has less difference between actual and predicted value next to that Linear regression, Random Forest regression and at last Decision tree regression.</p> 
<p>Decision tree regression overfits the Training data as seen in the scatter plot of Y_train vs prediction of X_train values so while predicting for Test data it gives high residual value.</p>
