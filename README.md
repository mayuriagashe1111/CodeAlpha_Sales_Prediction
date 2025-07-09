# CodeAlpha_Sales_Prediction
## Sales Prediction using Regression Models & XGBoost

This project demonstrates how machine learning regression techniques can be used to predict sales based on advertising budgets allocated to TV, Radio, and Newspaper. The dataset used is a classic Advertising dataset commonly used for introductory regression problems.

---
## Project Objective

To predict the **Sales** of a product using multiple regression algorithms and evaluate their performance, ultimately applying hyperparameter-tuned **XGBoost Regressor** to achieve optimal accuracy.

---
## Dataset

- **Source**: `Advertising.csv`
- **Features**:
  - `TV`: Advertising budget spent on TV (in thousands of dollars)
  - `Radio`: Advertising budget spent on Radio
  - `Newspaper`: Advertising budget spent on Newspaper
- **Target**:
  - `Sales`: Sales value in thousands of units

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (Data Visualization)
- Scikit-learn (Regression Models)
- XGBoost (Extreme Gradient Boosting)

---

## Workflow Summary

1. **Data Cleaning**:
   - Removed missing values and duplicates.
   - Dropped unnecessary columns.

2. **Data Visualization**:
   - Visualized relationship between features and sales using regplot.

3. **Model Training & Evaluation**:
   - Trained multiple regression models:
     - Linear Regression
     - Decision Tree
     - Random Forest
     - SVR
     - K-Nearest Neighbors
     - Gradient Boosting
   - Evaluated each model using:
     - MAE, MSE, MAPE, and R² Score

4. **XGBoost Regression**:
   - Applied hyperparameter tuning using `GridSearchCV`
   - Evaluated the best estimator
   - Visualized feature importance
   - Compared actual vs predicted results

---

## Evaluation Metrics
XGBoost MAE: 0.3907<br>
XGBoost MSE: 0.2842<br>
XGBoost MAPE: 0.0288<br>
XGBoost R² Score: 0.9886<br>


---

## Results

- XGBoost outperformed all other regression models with an R² score of **~98.86%**, showing excellent predictive capability.
- TV and Radio were found to be more influential on sales than Newspaper.

---

## Visual Outputs

- Regplots for each feature vs Sales
- Actual vs Predicted Sales line plot
- XGBoost feature importance bar chart

---

## Future Scope

- Extend the model to time-series forecasting
- Add interaction terms or polynomial features
- Deploy using Flask or Streamlit for live predictions

---

## Contact

**Author**: Mayuri Sanjay Agashe<br>
**GitHub**:https://github.com/mayuriagashe1111 <br>
**Email**: mayuriagashe2001@gmail.com

