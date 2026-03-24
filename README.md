# 🚀 Customer Churn Prediction & Risk Analysis (ML + Power BI)

## 📌 Project Overview

This project focuses on predicting customer churn using Machine Learning and delivering actionable insights through an interactive Power BI dashboard.

The solution helps identify high-risk customers and enables businesses to take proactive steps to improve customer retention.

---

## 🎯 Objectives

* Analyze customer behavior and churn patterns
* Build a predictive model for churn probability
* Segment customers into risk categories
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
* High Risk Customers: **1117**

---

## 📊 Model Performance

The model was evaluated using multiple metrics:

* Accuracy: **~82%**
* Precision: **~79%**
* Recall: **~75%**
* F1-Score: **~77%**
* ROC-AUC Score: **~0.84**

### 🔹 Confusion Matrix

<img width="747" height="557" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/da5c26e4-a92c-4ddd-af80-ee45cdd1516d" />


---

## ⚙️ Why XGBoost?

XGBoost was chosen due to its strong performance on structured data:

* Handles non-linear relationships effectively
* Built-in regularization reduces overfitting
* Performs better than baseline models
* Efficient and scalable

---

## 🧠 Risk Segmentation

Customers are segmented based on predicted churn probability:

* 🟢 Low Risk
* 🟠 Medium Risk
* 🔴 High Risk

This segmentation enables targeted retention strategies.

---

## 📊 Dashboard Preview

### 🔹 Main Dashboard

<img width="1212" height="697" alt="dashboard" src="https://github.com/user-attachments/assets/50fba7f1-36e5-4a10-b132-e1463d8d4932" />

---

### 🔹 Churn Rate by Risk Level

<img width="805" height="662" alt="churn rate by risk level" src="https://github.com/user-attachments/assets/491a5d50-c427-4683-b7dc-4f298f6be44d" />


---

### 🔹 Customer Risk Distribution

<img width="807" height="662" alt="Customer risk distribution" src="https://github.com/user-attachments/assets/c9be280b-cb58-4e04-8984-945d7007d591" />


---

### 🔹 Contract vs Churn

<img width="758" height="555" alt="Contract Vs Churn" src="https://github.com/user-attachments/assets/6ddd0cac-9be5-49cc-92e3-e1bbd9328254" />


---

### 🔹 Monthly Charges vs Churn

<img width="788" height="558" alt="Monthly Charges Vs Churn" src="https://github.com/user-attachments/assets/91e0d11f-007a-4207-bafc-f36a965d461d" />


---

### 🔹 Tenure vs Churn

<img width="822" height="558" alt="Tenure Vs Churn" src="https://github.com/user-attachments/assets/d8c29873-76f0-462f-929e-9a3706bdcc9a" />


---

### 🔹 Payment Method vs Churn

<img width="808" height="631" alt="Payment Vs Churn" src="https://github.com/user-attachments/assets/e87c2d4c-9d62-48fa-87f9-9a8fa4e642ba" />


---

### 🔹 Feature Importance

<img width="1086" height="546" alt="Features Influencing Churn" src="https://github.com/user-attachments/assets/65583621-5bdd-4dea-9ebc-6643546747c7" />


---

## 📌 Key Insights

* Month-to-month customers churn significantly more than long-term contracts
* Customers with lower tenure are more likely to churn
* High-risk customers have the highest churn probability
* Monthly charges play a key role in churn behavior

---

## 💡 Business Recommendations

* Focus retention efforts on high-risk customers
* Encourage long-term contracts
* Offer incentives to new customers
* Monitor customers with high monthly charges

---

## 🔄 Project Flow

Data → Preprocessing → Model Training → Prediction → Risk Segmentation → Dashboard

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
│    └── (all images)
│── requirements.txt
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository

   ```
   git clone https://github.com/sahanad14/Customer-Churn-Analysis.git
   ```

2. Navigate to project folder

   ```
   cd Customer-Churn-Analysis
   ```

3. Install dependencies

   ```
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook

   ```
   jupyter notebook
   ```

5. Run `eda.ipynb` to:

   * Perform analysis
   * Train the model
   * Generate predictions

6. Open Power BI dashboard to explore insights

---

## 👩‍💻 Author

**Sahana D**
Aspiring Data Scientist

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!


