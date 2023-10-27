# ML Regression Project with Cars Dataset

## Description
#### In the dataset, there were various columns relating to a car's attributes, and one realistic need for this dataset could be to try to figure out a vehicle's future value using the value of all the other features. Thus, this machine learning project set out to see if this dataset contained any modellable relations. In addition to this, I wanted to tackle a dataset that had a considerable amount of missing data and categorical information as to encounter the need for data cleaning and preparing. 

#### This Jupyter notebook involved deletion of data, based on the target features or similarly important features being missing. It also has a lot of graphic visualization, especially scatter plots and histograms, in addition to seeking correlations and trying to feature engineer new and valuable columns. After preprocessing that involved encoding categorical features and transforming some numeric features but scaling all numeric features, there was appropriate pipeline application and a column transformer. 

#### Several algorithms were applied to the training set and then the predictors would have their hyperparameters be tuned, with these algorithms involving linear regression, ridge regression, lasso regression, and elastic net regression. There was cross-validation and a comparison of root mean square errors, and then the optimal appearing model attained a considerably low generaliation error.

#### Python is used because of how it has one of the largest and ambitious communities, so it is not only user-friendly, but has a lot of libraries that help in data analysis and machine learning. NumPy was used because arrays are essential to anything and everything data analysis and machine learning in Python, and NumPy is also foundational to Pandas and Matplotlib. NumPy also provides several important transformations and applications throughout this project. Pandas provides tools to build off of and work with dataframes, which made it an essential library in this project. A dataframe was loaded into this Jupyter notebook through Pandas and this library provides methods and functions to check properties of each numeric and categorical column. Matplotlib provides several types of plotting tools and this helps guide individuals with what should be done and any trends and patterns that appear to be present. Seaborn was used to provide an important graph which also provided fitted linear regression items. Scikit-Learn was also used extensively, both for preprocessing data by cleaning, imputing, encoding, and setting up the items in the Jupyter notebook, but also to test out multiple algorithms and verify validity through root mean square error and k-fold cross-validation.

#### It was an extensive and tedious process to clean and prepare the data. Data cleaning is not so liked in the data science community, but it is essential to the practice and art of machine learning. If data cleaning is done inadequately or without enough thought, it can made a machine learning model perform suboptimally, or it may even prevent an algorithm from working! Likewise, feature engineering really correlative attributes was not so easy, but two were able to be formulated that had considerably high correlation with the target. Preprocessing, and applying each pipeline to each column correctly, took a considerable amount of time and can lead to many bugs, so debugging was an essential part of this project. Once data was cleaned and prepared, using algorithms and hyperparameter tuning was not as tedious, although the possible hyperparameters to tune can have a very large space with many options!

#### I hope to implement even more insightful attributes, and to calculate even better feature engineering. While several algorithms were applied, I would like to see or personally apply other algorithms with optimzed hyperparameters, with the goal of having an even lower root mean square error and an even better generalization.

## Use
#### Anaconda should be downloaded and with it, Jupyter notebooks should be a familiar topic to any user that wants to use this project. The dataset was downloaded from the Kaggle website, and it is under the CC0: Public Domain License. This specific project falls under the MIT License and should be treated accordingly.

## Features
#### Manufacturer - one of 26 different car manufacturers - categorical
#### Model - one of 118 different vehicle models - categorical
#### Sales_in_thousands - the amount that was sold divided by 1000 - numeric
#### __year_resale_value - the resell value of a vehicle - numeric
#### Vehicle_type - one of two types of vehicles - categorical
#### Price_in_thousands - cost of the car in an instance divided by 1000 - numeric
#### Engine_size - volumetric measurement of a car's engine - numeric
#### Horsepower - metric of power exhibited by an instance's vehicle - numeric
#### Wheelbase - distance between front and back wheels - numeric
#### Width - horizontal distance between one end of a vehicle to the other - numeric
#### Length - vertical distance betweeen the front end of a car to the back end - numeric
#### Curb_weight - weight of a vehicle without the inclusion of any passengers, items - numeric
#### Fuel_capacity - volumetric measurement of how much fuel a vehicle can hold - numeric
#### Fuel_efficiency - quantity relating to distance traveled per unit of fuel - numeric
#### Latest_Launch - date of a car's release - categorical
#### Power_perf_factor - measurement relating to utilizable power - numeric


## References
#### Géron, Aurélien. *Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems*. 3rd ed., O’Reilly Media, 2022.

## Dataset Citation
#### Bhatia, Gagan. (2017, October). Car sales, Version 1. Retrieved October 13, 2023 from https://www.kaggle.com/datasets/gagandeep16/car-sales/data
