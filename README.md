# Insurance Charges Prediction (Regression)

Machine Learning project to predict medical insurance charges using regression algorithms.
The workflow includes EDA, feature engineering, preprocessing pipelines, model training, hyperparameter tuning, and model deployment readiness.



#Summary 
| Metric       | Score     |
| ------------ | --------- |
| **MAE**      | 2576      |
| **RMSE**     | 4546      |
| **R² Score** | **0.867** |

#📂 Project Structure

insurance-charges-prediction/
│
├── data/
│   └── insurance_dataset.csv
│
├── notebooks/
│   └── insurance_analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train_models.py
│   └── evaluate.py
│
├── insurance_xgb_model.pkl
├── requirements.txt
└── README.md

##🔍 Exploratory Data Analysis (EDA) 
- Age, BMI, children distribution analysis
- Charges distribution skewness
- Categorical variable visualizations
- Correlation matrix analysis
- <img width="702" height="956" alt="image" src="https://github.com/user-attachments/assets/86525430-619d-41f1-a34a-e076d5d2b1c9" />
- <img width="702" height="956" alt="image" src="https://github.com/user-attachments/assets/465fde29-a8da-47d6-b249-7d863dec1b58" />
- <img width="702" height="956" alt="image" src="https://github.com/user-attachments/assets/04e61771-a87b-4e30-bd94-44e1782753d0" />


## ⚙️ Features & Preprocessing

-OneHotEncoding for categorical variables (sex, smoker, region)
-Standard scaling for numerical features
- Pipeline used to avoid data leakage
- <img width="702" height="956" alt="image" src="https://github.com/user-attachments/assets/f4ce1a78-54ba-41f6-942e-46dc6c935626" />


##🧪 Models Trained
1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. Random Forest Regressor
5. XGBoost Regressor (Best)

Hyperparameter tuning used:
GridSearchCV
Cross-validation (cv=5)

##🚀 How to Run the Project

1. Install dependencies
pip install -r requirements.txt

2. Launch Jupyter Notebook
jupyter notebook

3. Open:
notebooks/insurance_analysis.ipynb

##💾 Saved Model

The trained XGBoost model is saved as:
insurance_xgb_model.pkl
This can be loaded using joblib or pickle.

##📬 Contact

Gugan S
-Machine Learning | Data Analysis | Software Development
-GitHub: https://github.com/GuGan74
-LinkedIn: https://linkedin.com/in/gugan-s-610446355





