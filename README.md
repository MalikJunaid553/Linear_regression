# House Price Prediction using Linear Regression

A foundational machine learning project that predicts housing prices using a Linear Regression model. This project demonstrates end-to-end data preprocessing, train-test splitting, and model evaluation using a dataset sourced from Kaggle.

## 📊 Project Overview
* **Algorithm:** Linear Regression (`sklearn.linear_model.LinearRegression`)
* **Frameworks & Libraries:** Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Model Performance:** R² Score of **0.65**

## 🛠️ Workflow

### 1. Data Preprocessing
* Loaded and cleaned the Kaggle housing dataset.
* Dropped unnecessary features and separated the target variable (`price`).
* Formatted categorical data and handled missing values where necessary.

### 2. Model Training
* Split the processed dataset into training and testing sets using an **80/20 split** (`train_test_split`).
* Initialized and fitted the `LinearRegression` model on the training data.

### 3. Evaluation
* Generated predictions on the test dataset.
* Evaluated the model by plotting Actual vs. Predicted values against a "Perfect Prediction" baseline.

## 📉 Results & Insights
The model achieved an **R² score of 0.65**, demonstrating a solid baseline linear relationship between the chosen features and housing prices. 

Future iterations will focus on:
* **Feature Engineering:** Creating new interaction terms to capture non-linear patterns.
* **Advanced Models:** Transitioning to tree-based algorithms like Random Forests or Gradient Boosting to optimize predictive accuracy.
