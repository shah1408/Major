# Major

Project Overview

This script processes a cinema ticket sales dataset to analyze and predict total sales using multiple machine learning models. It includes data visualizations, feature selection, data preprocessing, and training of Decision Tree, XGBoost, MLP, KNN, and Lasso models. The goal is to evaluate and compare model performance based on Mean Absolute Error (MAE) and R-squared (R²) scores.

Dataset Information

The dataset used in this script contains cinema ticket sales data, including various features influencing total sales. Key attributes include the number of tickets sold, ticket prices, show times, occupancy percentages, cinema capacity, and temporal features such as month, quarter, and day. The dataset is preprocessed by handling missing values and scaling numerical features before training the machine learning models.

Machine Learning Models Used

Decision Tree Regressor: A tree-based model that splits the data into branches to make predictions. MLP Regressor: A neural network model capable of capturing complex relationships. KNN Regressor: A distance-based model that predicts using the nearest neighbors. Lasso Regression: A linear model that helps with feature selection by applying L1 regularization.

Machine Learning Models Used

Decision Tree Regressor: A tree-based model that splits the data into branches to make predictions. MLP Regressor: A neural network model capable of capturing complex relationships. KNN Regressor: A distance-based model that predicts using the nearest neighbors. Lasso Regression: A linear model that helps with feature selection by applying L1 regularization.

Exploratory Data Analysis (EDA)

EDA is performed to gain insights into the dataset before applying machine learning models.

The distribution of total sales is analyzed using histograms.
The relationship between tickets sold and ticket price is visualized through scatter plots.
Trends in occupancy percentage over time are explored.
Monthly variations in total sales are examined using boxplots.
Show time distribution is analyzed to understand peak hours.
Correlation heatmaps are used to identify relationships between features.

Results

The performance of the models is evaluated based on MAE and R² scores. Lower MAE values indicate better predictive accuracy, while higher R² values suggest a stronger fit to the data. Decision Tree performed well but may overfit due to its nature. MLP Regressor, as a neural network model, exhibited moderate performance and required fine-tuning. KNN Regressor struggled with high-dimensional data but performed decently in local trends. Lasso Regression, a linear model, was useful for feature selection but had limitations in capturing complex patterns
