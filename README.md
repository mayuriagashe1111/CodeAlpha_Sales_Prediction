## Sales Prediction using Regression Models & XGBoost
Predict product sales using various regression models including a hyperparameter-tuned XGBoost Regressor.

---

## Table of Contents
i)Project Overview <br>
ii)Dataset <br>
iii)Installation <br>
iv)Usage <br>
v)Results & Visualization <br>
vi)Contributing <br>
vii)Contact <br>

---


## 1. Project Overview
This project focuses on predicting sales based on advertising budgets across TV, Radio, and Newspaper channels. Multiple regression models like Linear Regression, Random Forest, and SVR are trained and compared. The final model is a tuned XGBoost Regressor, which delivers superior accuracy and feature insights.

---

## 2. Dataset
The dataset used is Advertising.csv, which includes the following columns:<br>
i)TV: Budget allocated to TV ads<br>
ii)Radio: Budget allocated to Radio ads<br>
iii)Newspaper: Budget allocated to Newspaper ads<br>
iv)Sales: Actual sales figures (target variable)<br>

Preprocessing steps include:<br>
i)Dropping nulls and duplicates<br>
ii)Removing unnecessary columns<br>
iii)Splitting into features and target<br>
iv)Train-test split (70-30)<br>

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

a)Model Evaluation Metrics (MAE, MSE, MAPE, R²)
b)XGBoost Best R² Score: ~0.9886
c)Feature Importance Graph
d)Actual vs Predicted Sales Plots
e)Regplot Analysis for each advertising channel

---

## 6. Contributing
Contributions are welcome! Feel free to:<br>
Raise issues<br>
Submit pull requests

---

## 7. Contact
For any queries, reach out:<br>
📧 Email: mayuriagashe2001@gmail.com <br>
💻 GitHub: mayuriagashe1111
