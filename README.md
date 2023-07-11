# XGBoost-Classifier-starbucks-customer-survey

This project is an implementation of the [XGBoost classifier](https://xgboost.readthedocs.io/en/stable/) on [Starbuck Customer Survey data](https://www.kaggle.com/datasets/mahirahmzh/starbucks-customer-retention-malaysia-survey). The XGBoost classifier predicts whether the customer will continue buying at Starbucks-or not- according to survey answers. 

### About XGBoost

XGBoost can be used directly for regression predictive modeling and classification.

It dominates structured or tabular datasets on classification and regression problems(for example: Kaggle competitions on 2018)
It is constructed from decision tree models. Trees are added one at a time to the ensemble and fit to correct the prediction errors made by prior models.

A first tree is trained and evaluated, after that the incorrect predicted data points are given more weightage in the next iteration. Then a next tree is trained and evaluated and the wrong predictions are given more weightage in the following iteration etc.

Models are fit using any arbitrary differentiable loss function and gradient descent optimization algorithm. This gives the technique its name, “gradient boosting,” as the loss gradient is minimized as the model is fit, much like a neural network.

### About Dataset
This dataset is includes survey questions of over 122 respondents for their shopping behavior at Starbucks.
Income is show in Malaysian Ringgit (RM)

### Context
Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs

### Content
Demographic info about customers – gender, age range, employment status, income range
Their current behavior in buying Starbucks
Facilities and features of Starbucks that contribute to the behavior

Inspiration
What are the characteristic of customer that will continue buying Starbucks?
