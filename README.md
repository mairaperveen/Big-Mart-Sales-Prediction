Projectworlds > Blog > Machine Learning Projects With Source Code > Big Mart Sales Prediction using Machine Learning Web App
Big Mart Sales Prediction using Machine Learning Web App
Posted on August 1, 2024 by Yugesh Verma
Big Mart is a retail chain that operates numerous stores across various locations. Predicting sales can help in optimizing inventory, improving sales strategies, and enhancing overall profitability. This project aims to build a predictive model using machine learning techniques to forecast the sales of products in different stores.

Objective
The main objective of this project is to predict the sales of products in different Big Mart outlets based on historical sales data and product attributes.

Data Collection and Preprocessing
Data Description
The dataset used in this project consists of various attributes of products and historical sales data. The key features include:

Datasets Link : - kaggle

Item Identifier
Item Weight
Item Fat Content
Item Visibility
Item Type
Item MRP
Outlet Identifier
Outlet Establishment Year
Outlet Size
Outlet Location Type
Outlet Type
Item Outlet Sales (Target Variable)
Model Building
Model Selection
Several machine learning algorithms were considered, including:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Model Training
The dataset was split into training and testing sets. Hyperparameter tuning was performed using GridSearchCV to find the best parameters for each model.

Model Evaluation
Models were evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²) score.
