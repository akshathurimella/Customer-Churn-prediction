# 📉 Customer Churn Prediction System

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses such as telecom, banking, insurance, and streaming services. Acquiring a new customer is significantly more expensive than retaining an existing one.

This project develops a Machine Learning model to predict whether a customer is likely to leave (churn) based on customer demographics, account information, and service usage patterns. Early prediction enables businesses to take proactive actions such as offering discounts, personalized plans, or customer support to improve customer retention.

---

## 🎯 Objective

The primary objective of this project is to:

- Predict whether a customer will churn.
- Analyze customer behavior affecting churn.
- Compare multiple machine learning algorithms.
- Identify the most important factors influencing customer churn.
- Help businesses reduce customer attrition through data-driven insights.

---

## 📂 Dataset

The dataset contains customer information including:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn (Target Variable)

### Target Variable

| Value | Meaning |
|--------|----------|
| 0 | Customer Will Stay |
| 1 | Customer Will Churn |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Collection

- Load customer dataset
- Explore data structure

### 2. Data Preprocessing

- Handle missing values
- Convert TotalCharges to numeric
- Remove unnecessary columns
- Encode categorical variables using Label Encoder

### 3. Exploratory Data Analysis (EDA)

- Customer Churn Distribution
- Contract Type vs Churn
- Monthly Charges Distribution
- Customer Behavior Analysis

### 4. Feature Engineering

- Select input features
- Separate target variable

### 5. Model Building

The following machine learning models were implemented:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

### 6. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

### 7. Feature Importance

Random Forest Feature Importance was used to identify the most influential customer attributes affecting churn.

---

## 🤖 Machine Learning Algorithms

### Logistic Regression

Used as a baseline classification model.

**Advantages**
- Fast
- Easy to interpret
- Works well for linear relationships

---

### Random Forest

An ensemble learning algorithm that combines multiple Decision Trees.

**Advantages**

- High accuracy
- Reduces overfitting
- Handles nonlinear relationships
- Provides feature importance

---

### XGBoost

Extreme Gradient Boosting is an advanced ensemble algorithm that improves prediction accuracy by learning from previous errors.

**Advantages**

- Excellent performance
- High prediction accuracy
- Robust to overfitting
- Widely used in industry

---

## 📈 Evaluation Metrics

The project evaluates model performance using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📊 Visualizations

The project includes the following visualizations:

- Churn Distribution
- Contract Type vs Churn
- Monthly Charges Distribution
- Confusion Matrix
- Feature Importance
- Model Accuracy Comparison

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Customer Churn.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
└── requirements.txt
---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
jupyter
```

Install all packages using:

```bash
pip install -r requirements.txt
```

---

## 💼 Business Impact

This project helps organizations:

- Predict customers likely to churn.
- Improve customer retention strategies.
- Reduce revenue loss.
- Identify high-risk customer segments.
- Make informed business decisions using predictive analytics.

---

## 🚀 Future Enhancements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- SMOTE for handling class imbalance
- Deployment using Flask or Streamlit
- Real-time churn prediction dashboard
- Power BI integration for business reporting

---

## 👨‍💻 Author

**Aksha Thurimella**

B.Tech – Computer Science Engineering (AI & ML)

### Skills

- Python
- SQL
- Machine Learning
- Data Analysis
- Pandas
- NumPy
- Scikit-learn
- Power BI
- Microsoft Excel

---

## ⭐ If you found this project useful, please consider giving it a Star!
