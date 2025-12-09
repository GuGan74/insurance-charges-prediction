# Insurance Charges Prediction (Regression)

This project predicts medical insurance charges using Machine Learning models such as Linear Regression, Ridge, Lasso, Random Forest, and XGBoost.  
XGBoost achieved the best performance with an R² score of **0.867**.

## Contents
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Preprocessing Pipeline (OneHotEncoder + StandardScaler)
- Model Training and Evaluation
- Hyperparameter Tuning (GridSearchCV)
- Feature Importance
- Model Saving (`insurance_xgb_model.pkl`)
- Jupyter Notebook

## Best Model Performance (XGBoost)
- **MAE:** 2576  
- **RMSE:** 4546  
- **R²:** 0.867  

## How to Run
pip install -r requirements.txt
jupyter notebook


## Files
- `notebooks/insurance_analysis.ipynb` — full workflow  
- `data/insurance.csv` — dataset  
- `insurance_xgb_model.pkl` — saved model  
- `requirements.txt` — dependencies

- <img width="664" height="866" alt="image" src="https://github.com/user-attachments/assets/529f467a-70e2-4409-97ed-56eead6c56ea" />


