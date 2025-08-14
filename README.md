# 🏡 California Housing Price Prediction with MLflow | MLOps Beginner Project

![MLflow](https://img.shields.io/badge/MLOps-MLflow-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.9+-yellow?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-0.24+-orange?style=for-the-badge)

## 📌 Project Overview
This is my **first step into MLOps**, where I explore the fundamentals of **ML model tracking, experiment management, and reproducibility** using **MLflow**.

The project uses the **California Housing dataset** from `sklearn.datasets` to build a **Random Forest Regression model** for predicting house prices.  
The aim is to integrate machine learning with MLflow to:
- Log model parameters
- Track performance metrics (Mean Squared Error)
- Save and version trained models

---

## 🚀 Features
- 📂 **Experiment Tracking** – Log parameters, metrics, and artifacts with MLflow.
- 📊 **Performance Metrics** – Mean Squared Error (MSE) to evaluate model performance.
- 🔄 **Model Versioning** – Store and register the best model in the MLflow Model Registry.
- 🛠 **Hyperparameter Tuning** – Grid Search on Random Forest parameters.
- 📈 **Reproducibility** – Track all runs to reproduce results anytime.

---

## 📚 Dataset
We use the **California Housing dataset** from `sklearn.datasets`.  
It contains features such as:
- Median income
- House age
- Average rooms
- Population
- Latitude & Longitude  
...and more, with the target variable being the **median house value**.

---

## 🏗 Project Workflow
1. **Data Preparation**
   - Load California Housing dataset from `sklearn.datasets`
   - Split into train/test sets
2. **Model Training & Tuning**
   - Random Forest Regressor
   - Hyperparameter tuning via `GridSearchCV`
3. **MLflow Tracking**
   - Log parameters, MSE, and trained models
   - Register best model in MLflow Model Registry
4. **Model Evaluation**
   - Predict on test set and calculate MSE

---

## 🛠 Tech Stack
- **Programming Language:** Python 🐍
- **ML Library:** Scikit-learn
- **MLOps Tool:** MLflow
- **Tracking URI:** Local MLflow Tracking Server

---

## 📸 Screenshots
### MLflow UI – Experiment Tracking
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/c09c9790-cf3d-4c64-95c6-9ab54919f776" />


---

## 🎯 Key Learning Outcomes
 - Understanding MLflow for experiment tracking & model versioning
 - Using sklearn for ML pipeline creation
 - Integrating hyperparameter tuning into MLOps workflow
 - Improving reproducibility and transparency of ML projects
 
 ---

## 📌 Future Improvements
 - Deploy best model as a REST API using FastAPI
 - Add Docker support for portability
 - Integrate with AWS S3 for remote MLflow artifact storage
