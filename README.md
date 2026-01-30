# Automobile-Mileage-Prediction-using-Logistic-Regression-
## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Methodology](#methodology)
- [Results](#results)
### Project Overview
This project focuses on building a machine learning model to predict the Miles Per Gallon (MPG) of automobiles using historical vehicle data. The goal is to understand how different vehicle attributes influence fuel efficiency and to develop a reliable regression model for MPG prediction.
### Objective
The objective of this project is to build a predictive modeling algorithm to predict mileage of cars based on given input variables.
### Dataset Description
- Horsepower
- Displacement
- Weight
- Number of cylinders
- Acceleration
- Origin
- Car name
- Mileage (MPG – target variable)
### Methodology
1. Before model training, the dataset was cleaned and prepared by:
  - Handling missing values
  - Removing outliers
  - Encoding categorical variables
  - Verifying data consistency and distributions
2. Train-Test Split
   The processed dataset was randomly split into:
   - 70% training data
   - 30% test data
3. Feature Selection
   Significant features were identified using the SelectKBest method to retain the most influential predictors and reduce noise in the model.
4. A Linear Regression model was trained using the selected input features to predict MPG. The most influential predictors identified were:
   - Horsepower
   - Displacement
   - Weight
   - Number of cylinders
5. Model Evaluation
   The model was evaluated on the test dataset using R-squared (R²) as the performance metric.
   - R² score: 0.76, indicating a good fit and strong predictive capability.
### Results
- The developed model successfully captured the relationship between vehicle characteristics and fuel efficiency, with displacement, horsepower, weight, and cylinder configuration (4-cylinder and 8-cylinder engines) identified as the key drivers influencing mileage (MPG).
- The predictions on the test data closely aligned with actual MPG values, showing the model’s effectiveness in capturing underlying patterns in the data.


