# Regression-Assignment
 The objective of this assignment is to evaluate your understanding of regression techniques in supervised learning by applying them to a real-world dataset.
 
## Linear Regression
 Linear Regression is a supervised learning algorithm that models the relationship between a dependent variable (target) and one or more independent variables (features) by fitting a linear equation to the data.
The California Housing dataset has a mix of numerical and categorical features, but the target variable (median house price) is numerical and might have a linear relationship with some features.

## Decision Tree Regressor
Decision Tree Regressor is a supervised learning algorithm that uses a tree-like model to predict the target variable. The algorithm recursively splits the data into subsets based on feature values, creating a tree with decision nodes and leaf nodes.
Decision Tree Regressor can handle categorical features and non-linear relationships, making it a good fit for datasets with complex interactions between features. The California Housing dataset has some categorical features (e.g., ocean proximity) that might interact with numerical features in non-linear ways.

##Random Forest Regressor
Random Forest Regressor is an ensemble learning algorithm that combines multiple Decision Tree Regressors to improve prediction accuracy. Each tree is trained on a random subset of features and samples, reducing overfitting and improving generalization.
Random Forest Regressor is a robust and flexible algorithm that can handle high-dimensional datasets with complex interactions between features. The California Housing dataset has a moderate number of features (8), but Random Forest Regressor can still provide good results by reducing overfitting and improving generalization.

## Gradient Boosting Regressor
Gradient Boosting Regressor is an ensemble learning algorithm that combines multiple weak models (Decision Trees) to create a strong predictive model. The algorithm iteratively trains each tree to correct the errors of the previous tree, using gradient descent to optimize the loss function.
The California Housing dataset has some non-linear relationships between features (e.g., between median income and house price), making Gradient Boosting Regressor a good fit.

## Support Vector Regressor (SVR)
Support Vector Regressor is a supervised learning algorithm that uses the concept of support vectors to find the best hyperplane that minimizes the loss function. The algorithm uses kernel tricks to handle non-linear relationships between features.
The California Housing dataset has some non-linear relationships between features, making SVR a good fit. However, SVR can be computationally expensive and might require careful tuning of hyperparameters.
