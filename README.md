# Insurance Charges Prediction (Regression)

This project predicts medical insurance charges using Machine Learning models such as Linear Regression, Ridge, Lasso, Random Forest, and XGBoost.  
XGBoost achieved the best performance with an R² score of **0.867**.

## Contents
- Exploratory Data Analysis (EDA)
- <img width="664" height="866" alt="image" src="https://github.com/user-attachments/assets/529f467a-70e2-4409-97ed-56eead6c56ea" />
<img width="664" height="866" alt="image" src="https://github.com/user-attachments/assets/5c6820b7-e5c9-4edc-9614-c1de44371f31" />
<img width="664" height="866" alt="image" src="https://github.com/user-attachments/assets/bab3cabf-e130-4f81-814d-aab9a7aa614f" />


- Feature Engineering
- Preprocessing Pipeline (OneHotEncoder + StandardScaler)
- <img width="664" height="866" alt="image" src="https://github.com/user-attachments/assets/8aa989ee-c985-4467-90f4-7e48f26e7643" />

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


