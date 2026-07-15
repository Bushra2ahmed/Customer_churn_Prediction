# 📉 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn prediction helps businesses identify customers who are likely to discontinue their services. This project builds an end-to-end machine learning pipeline to predict customer churn using customer demographics, account information, and service usage patterns.

The project compares multiple machine learning models and includes a **Streamlit web application** for interactive churn prediction.

---

## 🎯 Objectives

* Analyze customer behavior and churn patterns.
* Perform exploratory data analysis (EDA).
* Preprocess and engineer features for machine learning.
* Train and compare multiple classification models.
* Predict customer churn with high accuracy.
* Deploy the trained model using Streamlit.

---

## 📂 Dataset

The dataset contains customer information including:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Joblib
* Streamlit
* Jupyter Notebook

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

The best-performing model was selected for customer churn prediction.

---

## 🔄 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Encoding
6. Feature Scaling
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Churn Prediction
12. Streamlit Deployment

---

## 📊 Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

The comparative evaluation helps identify the most effective model for predicting customer churn.

---

## 📈 Exploratory Data Analysis

The project explores the relationship between churn and:

* Customer tenure
* Monthly charges
* Contract type
* Internet service
* Payment method
* Senior citizen status
* Partner and dependents
* Demographic characteristics

Visualizations include:

* Count plots
* Histograms
* Correlation heatmaps
* Distribution plots
* Box plots

---

## 💡 Business Value

This solution enables businesses to:

* Identify customers at risk of churning.
* Improve customer retention strategies.
* Reduce revenue loss.
* Support data-driven decision-making.
* Enhance customer relationship management.

---

## 🌐 Streamlit Application

The repository includes a Streamlit application that allows users to:

* Enter customer information.
* Predict whether a customer is likely to churn.
* Display prediction results instantly through an interactive web interface.

---

## 📁 Repository Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Dissertation_Enhanced.ipynb
├── app.py
├── model/
├── dataset/
├── dashboard/
├── requirements.txt
└── README.md
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/Bushra2ahmed/customer-churn-prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook for model training.

Launch the Streamlit application:

```bash
streamlit run app.py
```

---

## 🚀 Future Improvements

* Hyperparameter optimization
* Model explainability using SHAP
* Cloud deployment
* Real-time prediction API
* Automated model retraining

---

## 👩‍💻 Author

**Bushra Ahmed**

🎓 MSc Computer Science – Banaras Hindu University

💻 Aspiring Data Analyst | Data Scientist | Python Developer

---

## ⭐ Acknowledgement

This project demonstrates the practical application of machine learning for customer churn prediction and deployment using Streamlit, combining data analysis, predictive modeling, and interactive visualization in a real-world business scenario.
