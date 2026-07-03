# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by banks and financial institutions. Losing existing customers directly impacts business growth and profitability.

This project uses **Machine Learning** to predict whether a customer is likely to leave the bank (churn) based on customer information such as **Credit Score, Geography, Gender, Age, Tenure, Balance, Number of Products, Credit Card Status, Active Member Status, and Estimated Salary**.

The objective is to build an accurate prediction model that helps banks identify customers at risk of churning so they can take proactive retention measures.

---

## 🎯 Project Objective

The objectives of this project are:

- Predict customer churn using Machine Learning.
- Analyze customer behavior through Exploratory Data Analysis (EDA).
- Compare different Machine Learning models.
- Select the best-performing model.
- Help businesses improve customer retention.

---

## 📂 Dataset Information

**Dataset Name:** `Churn_Modelling.csv`

| Attribute | Details |
|-----------|---------|
| Total Records | 10,000 |
| Total Features | 14 |
| Target Variable | Exited |

### Target Variable

- **0** → Customer Stayed
- **1** → Customer Churned

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Project Workflow

### Step 1: Import Required Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Step 2: Load Dataset

- Read CSV file
- Display dataset

### Step 3: Data Understanding

- Head
- Shape
- Columns
- Info
- Describe

### Step 4: Data Cleaning

- Missing Values
- Duplicate Values
- Remove unnecessary columns

### Step 5: Exploratory Data Analysis (EDA)

- Churn Distribution
- Gender Analysis
- Geography Analysis
- Age Analysis
- Credit Score Analysis
- Balance Analysis
- Active Member Analysis
- Correlation Heatmap

### Step 6: Data Preprocessing

- Label Encoding
- Feature Selection
- Train-Test Split
- Feature Scaling

### Step 7: Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### Step 8: Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score
- ROC Curve

### Step 9: Feature Importance

- Random Forest Feature Importance

### Step 10: Best Model Selection

- Compare all models
- Select highest accuracy model

### Step 11: Save Model

- Save trained model using Joblib

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## 🏆 Best Model

After comparing all models, the **Random Forest Classifier** achieved the best prediction accuracy and was selected as the final model.

--

## 📌 Results

- Successfully cleaned and preprocessed the dataset.
- Performed Exploratory Data Analysis (EDA).
- Trained multiple Machine Learning models.
- Compared model performance.
- Selected Random Forest as the best model.
- Saved the trained model for future predictions.

---

## 🚀 Future Scope

- Deploy the model using Flask or Streamlit.
- Improve prediction accuracy using XGBoost.
- Develop a real-time web application.
- Integrate with banking CRM systems.
- Enable real-time customer churn prediction.

---

## 👨‍💻 Author

Name: Avinash Kumar Singh

Project Title: Customer Churn Prediction using Machine Learning
Intern ID: CITS1535
Duration: 6 weeks
Data Analytics Intern: CodTech IT Solutions

## 📄 License

This project is developed for educational and learning purposes. It can be freely used and modified with proper attribution.