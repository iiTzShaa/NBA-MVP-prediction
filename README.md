# NBA-MVP-prediction

NBA-MVP Prediction Project
Project Overview: This project aims to predict NBA MVP winners from 1991 to 2023 using a machine learning approach. The project involves data preprocessing, feature engineering, model training, and evaluation to achieve accurate predictions.

Key Components:

Data Collection:

Data includes NBA player statistics from 1991 to 2023.
Data is collected using HTTP requests, Beautiful Soup, and Selenium WebDriver.
Data Preprocessing:

Handled historical team name changes.
Cleaned and normalized data, including the addition of normalized columns (e.g., PTS_R, AST_R, STL_R).
Managed potential issues such as incorrect player names and missing values.
Feature Engineering:

Added normalized columns to the dataset to improve model performance.
Included features like points, assists, steals, blocks, and three-pointers with their respective normalized versions.
Model Training:

Used various regression models to predict MVPs, including Ridge Regression and RandomForestRegressor.
Applied data normalization before training and testing the models.
Evaluated model performance using metrics like mean average precision (mean_ap).
Model Evaluation:

Implemented backtesting to evaluate model performance over different years.
Compared results with historical MVP winners to determine accuracy.
Achieved a mean average precision (mean_ap) of up to 0.851.
Challenges and Iterations:

Addressed issues with normalization and model performance.
Experimented with different models and hyperparameters to improve accuracy.
Worked on refining the add_ranks function and handling data indexing issues.
Results:

Correctly predicted MVP winners for 14 out of the 33 years in the dataset.
Continuously refined the approach to improve prediction accuracy.
Future Work:

Explore additional features and models to enhance prediction accuracy.
Fine-tune hyperparameters and optimize data preprocessing.
Incorporate more advanced techniques such as ensemble methods or deep learning.
Repository Details:

The project repository contains code for data preprocessing, model training, and evaluation.
Includes scripts for feature engineering, model evaluation, and performance metrics calculation.
Documentation and comments are provided to explain the implementation and usage.
