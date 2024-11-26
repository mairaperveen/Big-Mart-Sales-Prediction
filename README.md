# Big Mart Sales Prediction using Machine Learning Web App

Big Mart is a retail chain operating multiple stores across various locations. Predicting sales helps optimize inventory, improve sales strategies, and enhance overall profitability. This project leverages machine learning techniques to forecast the sales of products in different stores.

---

## Objective
The main goal of this project is to predict the sales of products in different Big Mart outlets using historical sales data and product attributes.

---

## Dataset

### Data Description
The dataset contains various attributes of products and their historical sales data. Key features include:

- **Item Identifier**: Unique product ID.
- **Item Weight**: Weight of the product.
- **Item Fat Content**: Categories such as "Low Fat" or "Regular".
- **Item Visibility**: Percentage of total display area allocated to the product in a store.
- **Item Type**: Category of the product.
- **Item MRP**: Maximum Retail Price of the product.
- **Outlet Identifier**: Unique store ID.
- **Outlet Establishment Year**: Year the outlet was established.
- **Outlet Size**: Size of the store (Small, Medium, High).
- **Outlet Location Type**: Type of city where the outlet is located.
- **Outlet Type**: Type of outlet (e.g., Grocery Store, Supermarket).
- **Item Outlet Sales**: Sales of the product at a particular outlet (Target variable).

### Dataset Link
The dataset used for this project is available on [Kaggle](https://www.kaggle.com).

---

## Model Building

### Model Selection
The following machine-learning algorithms were explored for this project:

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **Gradient Boosting Regressor**

### Model Training
- The dataset was split into training and testing sets.
- **Hyperparameter tuning** was performed using `GridSearchCV` to optimize the performance of each model.

---

## Model Evaluation
The models were evaluated using the following metrics:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared (R²) Score**

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BigMartSalesPrediction.git


## Features of the Web App
Predict sales for a given set of product and store attributes.
Visualize key trends in sales data.

## Technologies Used
**Programming Language**: Python
**Framework**: Flask (for web app development)
**Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss the proposed changes.

## License
This project is licensed under the MIT License.
