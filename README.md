# ML "Combined cycle power plant" project

This is a machine learning project using regressors to predict Electrical energy output (EP) of the plant, using data from excel file

A several visual aids like graphs and confusion matrix have been created, to show and analyze the results.

## Content
- [Project](#Project)
    - [About dataset](#About_Dataset)
    - [Scope](#Scope)
    - [Data Preprocessing](#Data_Preprocessing)
    - [Model development](#Model_Development)
- [Libraries and Algorithms used](#Liabraries_and_Algorithms)
    - [Libraries](#Libraries_and_Modules)
    - [Algorithms](#Algorithms)

## Project

The project was developed as part of a team project during studies at the online academy "VeraVla Edu". The main point was to perform data preprocessing, ML model training.

### About_Dataset

A combined cycle power plant (CCPP) is composed of gas turbines (GT), steam turbines (ST) and heat recovery steam generators. 
In a CCPP, the electricity is generated by gas and steam turbines, which are combined in one cycle, and is transferred from one turbine to another. 
While the Vacuum is collected from and has effect on the Steam Turbine, he other three of the ambient variables effect the GT performance.
The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load.

### Scope

Project scope:

*   performing of Data Preprocessing
*   visualizing of data
*   model developing
    
### Data_Preprocessing

    - perform imputation
    - perform normalization 
    
### Model_Developing
 
    - by choosing optimal Algorithm
    - by hyper parameters tuning via grid search

## Libraries_and_Algorithms
### Libraries_and_Modules

libraries and modules, their implementation in current project:

*   [pandas](https://pandas.pydata.org/) - Data manipulation and analysing
*   [numpy](https://numpy.org/) - for scientific computing with Python
*   [matplotlib](https://matplotlib.org/) - for creating static, animated, and interactive visualizations in Python
*   [seaborn](https://seaborn.pydata.org/) - statistical data visualization
*   [sklearn](https://scikit-learn.org/stable/) - Machine Learning in Python
*   [feature_engine](https://feature-engine.readthedocs.io/en/latest/) - Python library with multiple transformers to engineer and select features to use in machine learning models
*   [openpyxl](https://openpyxl.readthedocs.io/en/stable/) -  for reading/writing Excel 2010 xlsx/xlsm/xltx/xltm files

### Algorithms

*   [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html) - Meta estimator that fits a number of classifying decision trees on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting
*   [SVR](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html) - Epsilon-Support Vector Regression
*   [XGBoost Regressor](https://xgboost.readthedocs.io/en/stable/index.html) - machine learning algorithms under the Gradient Boosting framework
*   [KNeighborsRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html) - regression based on k-nearest neighbors
*   [GradientBoostingRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html) - estimator builds an additive model in a forward stage-wise fashion, it allows for the optimization of arbitrary differentiable loss functions
