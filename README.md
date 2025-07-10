## Sales Prediction using Regression Models & XGBoost
Predict product sales using various regression models including a hyperparameter-tuned XGBoost Regressor.

---

## Table of Contents
Project Overview <br>
Dataset <br>
Installation <br>
Usage <br>
Results & Visualization <br>
Contributing <br>
Contact <br>

---


## 1. Project Overview
This project focuses on predicting sales based on advertising budgets across TV, Radio, and Newspaper channels. Multiple regression models like Linear Regression, Random Forest, and SVR are trained and compared. The final model is a tuned XGBoost Regressor, which delivers superior accuracy and feature insights.

---

## 2. Dataset
The dataset used is Advertising.csv, which includes the following columns:
TV: Budget allocated to TV ads
Radio: Budget allocated to Radio ads
Newspaper: Budget allocated to Newspaper ads
Sales: Actual sales figures (target variable)
Preprocessing steps include:
Dropping nulls and duplicates
Removing unnecessary columns
Splitting into features and target
Train-test split (70-30)

---

## 3. Installation
To set up the project, follow these steps:

### Clone the repository
git clone https://github.com/your-username/sales-prediction-xgboost.git

### Navigate to the project directory
cd sales-prediction-xgboost

### Install required dependencies
pip install -r requirements.txt
Or manually install:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

---

## 4. Usage
i) Open the Jupyter Notebook (Sales_Prediction.ipynb). <br>
ii) Run the cells to load and explore the dataset. <br>
iii) Train different regression models and compare results. <br>
iv) Perform hyperparameter tuning using GridSearchCV for XGBoost. <br>
v) Visualize actual vs. predicted sales and feature importance.

---

## 5. Results & Visualization
Here are some insights and visualizations generated:

Model Evaluation Metrics (MAE, MSE, MAPE, R²)
XGBoost Best R² Score: ~0.9859
Feature Importance Graph
Actual vs Predicted Sales Plots
Regplot Analysis for each advertising channel

---

## 6. Contributing
Contributions are welcome! Feel free to:
Raise issues
Submit pull requests

---

## 7. Contact
For any queries, reach out:
📧 Email: mayuriagashe2001@gmail.com <br>
💻 GitHub: mayuriagashe1111
