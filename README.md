# 🚀 Customer Churn Prediction & Analysis (ML + Power BI)

## 📌 Project Overview

This project focuses on predicting customer churn using Machine Learning and delivering business insights through an interactive Power BI dashboard.

The solution identifies high-risk customers and helps businesses take proactive actions to improve customer retention.

---

## 🎯 Objectives

* Analyze customer behavior and churn patterns
* Build a predictive model for churn probability
* Segment customers into Low, Medium, and High Risk
* Create an interactive dashboard for decision-making

---

## 🛠 Tech Stack

* **Python**: Pandas, NumPy, Matplotlib
* **Machine Learning**: Scikit-learn, XGBoost
* **Visualization**: Power BI

---

## 📊 Key Results

* Total Customers: **7032**
* Churned Customers: **1869**
* Churn Rate: **27%**
* High Risk Customers: **243**

---

## 📈 Model Performance

* Model Used: **XGBoost Classifier**
* Accuracy: ~**80–85%**
* Output: Churn Probability (0–1)

---

## 🧠 Risk Segmentation

Customers are classified into risk categories using percentile-based segmentation on predicted churn probability:

* 🟢 Low Risk
* 🟠 Medium Risk
* 🔴 High Risk

This approach ensures balanced and meaningful classification of customers.

---

## 📊 Dashboard Preview

### 🔹 Main Dashboard

<img width="1217" height="707" alt="Dashboard" src="https://github.com/user-attachments/assets/9fe5a66a-ae9c-4e53-991c-49d6bb925a1f" />


---

### 🔹 Customer Risk Distribution

<img width="807" height="662" alt="Customer risk distribution" src="https://github.com/user-attachments/assets/4b44841b-85f9-44ee-9705-5d0b6b6b7756" />


---

### 🔹 Churn Rate by Risk Level

<img width="805" height="662" alt="churn rate by risk level" src="https://github.com/user-attachments/assets/566cf34a-28d6-4ecc-a13e-de8243ef3052" />


---

### 🔹 Contract vs Churn

<img width="758" height="555" alt="Contract Vs Churn" src="https://github.com/user-attachments/assets/52788ae5-a920-4367-aead-51bf282df8d8" />


---

### 🔹 Monthly Charges vs Churn

<img width="788" height="558" alt="Monthly Charges Vs Churn" src="https://github.com/user-attachments/assets/7ef736c9-f362-4dd7-8b7a-1488871b90fd" />


---

### 🔹 Tenure vs Churn

<img width="822" height="558" alt="Tenure Vs Churn" src="https://github.com/user-attachments/assets/5a6d77cc-2bbc-46f2-ac04-29d2d10bd147" />


---

### 🔹 Payment Method vs Churn

<img width="808" height="631" alt="Payment Vs Churn" src="https://github.com/user-attachments/assets/f67a298e-1d8e-4885-9d25-3df33b25367c" />


---

### 🔹 Feature Importance

<img width="1086" height="546" alt="Features Influencing Churn" src="https://github.com/user-attachments/assets/cc999a0d-b6d1-41a7-869e-f56cdc32c811" />


---

### 🔹 Confusion Matrix

<img width="747" height="557" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/62c7947a-aa2d-4ccb-a721-ce449b6f65f6" />


---

## 📌 Key Insights

* Month-to-month customers churn ~2.5x more than long-term contracts
* Customers with low tenure are more likely to churn
* High-risk customers show significantly higher churn probability
* Monthly charges influence customer churn behavior

---

## 📌 Important Features

Top factors influencing churn:

* Tenure
* Monthly Charges
* Contract Type

---

## 💡 Business Recommendations

* Target high-risk customers with retention strategies
* Offer discounts for month-to-month customers
* Encourage long-term contracts
* Focus on early-stage customers (low tenure)

---

## ⚙️ Project Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Building (XGBoost)
5. Churn Probability Prediction
6. Risk Segmentation
7. Power BI Dashboard Creation

---

## 📁 Project Structure

```
Customer-Churn-Analysis/
│── data/
│    └── cleaned_data.csv
│── notebooks/
│    └── eda.ipynb
│── models/
│    └── churn_model.pkl
│── dashboard/
│    └── dashboard.png
│── requirements.txt
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook
4. Run `eda.ipynb`
5. Train model and generate predictions
6. Open Power BI dashboard

---

## 👩‍💻 Author

**Sahana D**
Aspiring Data Scientist

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

