# Supervised_ML_classification_and _regression
 predicting house prices in Iowa 


## Overview and task

This project is a classic competition from [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview) to predict House prices from a dataset with 79 features. 

### Classification
Before entering the competition on Kaggle an alternative version of the dataset was used to classify all houses into the categories cheap or expensive.

The classification data and notebook can be found [here].
Steps in this part of the project were
- exploring the data and intuitive model in this [notebook]
- building a pipe using SimpleImputer, onHotEncoder, OrdinalEncoding to test DecisionTreeClassifier and RandomForestClassifier
- buildig a pipe using SimpleImputer, onHotEncoder, Scaling and OrdinalEncoding to test KNeighborsClassifier
- Grid Search to test best parameters for the models
- Submission of the best model results

The prediction could improve from an accuracy of 85% in the intuitive approach to 98% with a RandomForest model

### Regression

In a second step the original kaggle dataset was then used with a regression model to predict the actual price for each house. 
This data and notebook is in the folder [regression].

Steps in this part of the project were
- intuitive model
- ordinal encoding
- building a pipe using SimpleImputer, OneHotEncoder, OrdinalEncoder and different models
- tested models: GradientBoostingRegressor, RandomForestRegressor

Result in the comptetion was a mean absolute error of 0.139