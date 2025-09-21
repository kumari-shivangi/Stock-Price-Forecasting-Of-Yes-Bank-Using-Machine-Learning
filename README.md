# 📈 Yes Bank Stock Price Prediction (ML Regression Project)

## 🧠 Overview

This project predicts the **monthly closing prices** of **Yes Bank** using various **Machine Learning regression models** like **Random Forest**, **XGBoost**, and **Ridge Regression**. The model with the best performance (**R² ≈ 0.98**) is saved for deployment.

---

## 🚀 Objectives

- Load and preprocess stock price data
- Perform detailed EDA and visualization
- Apply feature engineering and scaling
- Train multiple ML models
- Optimize hyperparameters using GridSearchCV
- Evaluate using regression metrics (MAE, RMSE, R²)
- Save the best model using `pickle`
- Predict unseen data for deployment sanity check

---

## 🔍 Dataset

- **Source**: Historical stock data of **Yes Bank**
- **Frequency**: Monthly closing prices
- **Features**: Date, Open, High, Low, Close, Volume, etc.

---

## 📊 Models Used

- ✅ **Random Forest Regressor** *(Best Model – R²: 0.98)*
- XGBoost Regressor
- Ridge Regression

All models were trained with **cross-validation** and **hyperparameter tuning** using **GridSearchCV**.

---

## 📈 Evaluation Metrics

- **MAE** – Mean Absolute Error
- **MSE** – Mean Squared Error
- **RMSE** – Root Mean Squared Error
- **R² Score** – Goodness of fit

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Pickle

---

## ✅ Results

- **Best Model**: Random Forest Regressor
- **Final R² Score**: 0.98
- Model successfully predicts unseen data with high accuracy

---

## 💾 Deployment Ready

- Trained model saved as `rf_model.pkl`
- Ready to be integrated into a Flask app or prediction script

---

## 👩‍💻 Author

**Kumari Shivangi**  
_Data Science Trainee at AlmaBetter_  
Let’s connect on [LinkedIn](https://www.linkedin.com/in/kumarishivangi7) 🚀

---

