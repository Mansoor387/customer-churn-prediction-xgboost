# customer-churn-prediction-xgboost


## 📌 Objective
Identify customers who are likely to leave the bank using **XGBoost Classifier**.

## 📂 Dataset
The dataset used is `Churn_Modelling.csv` containing customer demographics, account information, and whether they exited (`Exited` column).

## ⚙ Steps
1. Load & explore dataset.
2. Clean and prepare data.
3. Encode categorical variables (`Gender`, `Geography`).
4. Train-test split.
5. Train **XGBoost** model.
6. Evaluate performance.
7. Analyze feature importance.

## 📊 Results
- Model accuracy: ~**85-87%** (varies with parameters)
- Feature importance chart included.




# Run script
python src/churn_model.py
