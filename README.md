# House Price Prediction using Machine Learning

## Project Overview
This project focuses on predicting house prices in California using various machine learning algorithms. The dataset used contains features such as median income, number of rooms, and geographical location. The goal of this project is to explore, preprocess, and model the data to predict house prices with high accuracy.

## Dataset
The dataset used for this project is a modified version of the California Housing dataset. It includes the following features:

- longitude: The longitude of the block
- latitude: The latitude of the block
- housing_median_age: Median age of the houses
- total_rooms: Total number of rooms in the block
- total_bedrooms: Total number of bedrooms in the block
- population: Population of the block
- households: Number of households in the block
- median_income: Median income of the block
- median_house_value: Median house value in the block
- ocean_proximity: Proximity of the block to the ocean

## Project Steps
1. Data Cleaning and Preprocessing:

- Handled missing values for the total_bedrooms feature.
- Removed outliers and standardized numerical features for better model performance.
- Encoded the categorical feature ocean_proximity using one-hot encoding.
2. Exploratory Data Analysis (EDA):

- Visualized the distribution of house prices and other features.
- Analyzed correlations between features using heatmaps.
- Explored the relationship between geographical location and house prices.
3. Modeling:

- Implemented multiple machine learning models to predict house prices:
- Linear Regression
- Decision Tree
- Random Forest
- XGBoost
- AdaBoost
- Used GridSearchCV for hyperparameter tuning to improve model accuracy.
- Compared models based on metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-Squared (R²) values.
4. Model Evaluation:

- The best performing model was XGBoost, achieving an R² score of 0.80 on the test set.
- Feature importance analysis revealed that median_income had the highest impact on house prices.
## Results
- The Random Forest and XGBoost models performed the best in terms of predictive power.
- The project demonstrates that ensemble models like XGBoost provide a significant improvement in performance compared to simpler models like Linear Regression.
## Conclusion
The project highlights the effectiveness of machine learning algorithms in predicting house prices, with an emphasis on data cleaning, preprocessing, and model tuning. Further improvements could be made by experimenting with additional features and more complex models.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
     - numpy
    - pandas
    - matplotlib
    - seaborn
    - scikit-learn
    - xgboost
    - tensorflow (for neural network implementation)



