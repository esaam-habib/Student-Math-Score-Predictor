# 📊 Student Math Score Predictor

A machine learning-based web application that predicts a student's math score using multiple algorithms. The app includes comprehensive data preprocessing, model evaluation, visualization, and deployment on AWS.

---

## 🔍 Overview

This project demonstrates the full lifecycle of a machine learning application—from data preprocessing and model training to deployment on AWS. It aims to accurately predict student math scores based on features such as gender, parental education, test preparation, and more.

---

## 🚀 Features

- 📈 Predict math scores using:
  - Linear Regression
  - Decision Tree
  - Random Forest (with hyperparameter tuning)
- 🧼 Robust data preprocessing:
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling
- 📊 Visualizations with Matplotlib and Seaborn
- ☁️ Deployed on **AWS EC2** via Docker image from **AWS ECR**
- 🌐 Accessible via a user-friendly web interface

---

## 🧰 Tech Stack

| Component              | Technology                      |
|------------------------|----------------------------------|
| Language               | Python 3.x                      |
| ML Libraries           | Scikit-learn, Pandas, NumPy     |
| Visualization          | Matplotlib, Seaborn             |
| Web Framework          | Flask / Streamlit (based on your setup) |
| Deployment             | Docker, AWS ECR, AWS EC2        |
| Others                 | joblib, pickle (for model storage) |

---

## 🧠 Machine Learning Approach

### Algorithms Used:
- 🔹 Linear Regression
- 🔹 Decision Tree Regressor
- 🔹 Random Forest Regressor (with GridSearchCV for hyperparameter tuning)

### Metrics:
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

---

## 📊 Visualizations

The following charts help understand feature relationships and model insights:

- Correlation heatmaps
- Distribution plots
- Box plots for outlier detection
- Actual vs Predicted Score plots

---

## 📝 Sample Input Features

gender: Male / Female

parental level of education: Bachelor’s / Master’s / etc.

test preparation course: completed / none

socio-economic status of student: numeric

student studying hours: numeric

school infrastructure: good / better / best / bad / worst



## 👨‍💻 Author
Developed by Esaam Habib



