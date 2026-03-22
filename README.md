![IEEE](https://ieeexplore.ieee.org/document/11167242)

# 🌫️ Air Quality Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting air quality levels using machine learning models trained on real-world environmental data. The goal is to analyze pollution patterns and build predictive models that can estimate air quality indicators based on historical data.

With increasing urbanization and pollution, accurate air quality prediction is essential for public health awareness and environmental planning.

---

## 🎯 Problem Statement
Air pollution has become a major concern in urban areas. Monitoring stations provide data, but predicting future air quality levels helps in:

- Early warnings  
- Policy planning  
- Health risk reduction  

### This project aims to:
- Analyze air quality data  
- Build multiple regression models  
- Compare their performance  
- Identify the best-performing model  

---

## 📂 Dataset
- **Dataset Used:** City Day Air Quality Dataset (`city_day.csv`)  

### Contains:
- City-wise pollution data  
- Parameters like:
  - PM2.5  
  - PM10  
  - NO2  
  - CO  
  - SO2  
- Air Quality Index (AQI)  

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Handling missing values using imputation  
- Data cleaning and formatting  
- Feature selection  
- Train-test split  

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Understanding pollution trends  
- Identifying correlations between features  
- Visual inspection of data distribution  

---

### 3️⃣ Model Building
The following regression models were implemented:

- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- ElasticNet  
- SGD Regressor  
- Support Vector Regressor (SVR)  
- Gradient Boosting Regressor  
- Random Forest Regressor  
- Decision Tree Regressor  

---

### 4️⃣ Model Evaluation
Models were evaluated using:

- 📊 **R² Score**  
- 📉 **Mean Squared Error (MSE)**  
- 📉 **Mean Absolute Error (MAE)**  

---

### 5️⃣ Model Selection
Based on performance comparison and feature ranking insights:

- ✅ **Linear Regression** and **Ridge Regression** were selected as the best-performing models  

### These models showed:
- Strong generalization  
- Stable performance  
- Better interpretability  

---

### 6️⃣ Ensemble Learning
- Built a **Voting Regressor** using:
  - Linear Regression  
  - Ridge Regression  

### Benefits of this approach:
- Reduced noise from weaker models  
- Improved prediction consistency  
- Balanced bias-variance tradeoff  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  

### Libraries Used:
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 💡 Key Highlights
- Implemented multiple regression models for comparison  
- Applied feature selection and ranking techniques  
- Performed intelligent model selection  
- Built a **targeted ensemble model (Linear + Ridge)**  
- Developed a complete end-to-end ML pipeline  

---
