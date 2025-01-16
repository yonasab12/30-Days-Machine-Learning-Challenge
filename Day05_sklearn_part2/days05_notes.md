Machine Learning Regression Pipelines

This repository demonstrates the creation and usage of various machine learning regression pipelines. Each pipeline integrates data preprocessing, feature scaling, and specific regression models to predict the target variable: Performance Index.



The project is focused on building regression pipelines using scikit-learn to automate preprocessing and modeling for different regression techniques:

Linear Regression

Lasso Regression

Ridge Regression

ElasticNet Regression

Random Forest Regression

Decision Tree Regression

Pipelines Overview

Each pipeline includes the following steps:

One-Hot Encoding: Encodes categorical variables into a sparse matrix representation.

Imputation: Handles missing values using the SimpleImputer with the mean strategy.

Scaling: Scales numerical features using the StandardScaler with with_mean=False (to handle sparse matrices).

Regression Model: Applies a specific regression model, such as Linear, Lasso, Ridge, ElasticNet, Random Forest, or Decision Tree.