# 🏦 Credit Risk Scoring System

A complete end-to-end project for predicting customer credit risk using machine learning, structured SQL data, and interactive Power BI dashboards. This project simulates a real-world lending scenario to support automated and data-driven credit approval decisions.

---

## 📊 Overview

This project classifies customers into **high** or **low risk** using supervised machine learning. It connects:
- **SQL** (for data extraction and preprocessing)
- **Python** (for model building and predictions)
- **Power BI** (for interactive reporting)

The system helps simulate and visualize credit approval workflows based on income, loan amount, late payments, and other customer behavior.

---

## 🎯 Business Objective

- Predict whether a customer is eligible for credit (high/low risk).
- Enable lenders to **auto-approve**, **reject**, or **manually review** applications.
- Provide insights into **risk patterns, income brackets, loan distributions**, and **repayment behavior**.

---

## 🛠 Tech Stack

| Layer        | Tools / Libraries                                  |
|--------------|----------------------------------------------------|
| Language     | Python (pandas, numpy, scikit-learn, matplotlib)   |
| ML Models    | Logistic Regression, Random Forest, XGBoost        |
| Data Source  | SQL (imported to Power BI using Direct Query/Import) |
| Dashboard    | Power BI (with DAX for KPIs and slicers)           |

---

## 🔁 Project Pipeline

1. **Data Collection**: Used 3 SQL tables: customer profile, financial history, and repayment.
2. **Data Cleaning**: Handled missing values, engineered features (e.g., late_payment_ratio).
3. **Modeling (Python)**:
   - Feature scaling, encoding
   - Trained and evaluated models
   - Output: Credit Risk Score (0–1)
4. **Export**: Final predictions with scores exported to SQL.
5. **Power BI Dashboard**:
   - Connected to final tables
   - Built KPIs, slicers, custom visuals across 3 dashboard pages

---

## 📌 Key Features

- ✅ Credit Risk Score (0–1) with thresholds for approval
- 🔄 Late payment ratio and its impact on risk
- 📊 Action-based decisions: Approve / Review / Reject
- 📍 Regional and employment-wise credit behavior
- 🧠 Model interpretability via feature importance

---

## 📋 Dashboard Overview (3 Pages)

### 📌 Page 1: **Credit Risk Score Summary**
- Avg Credit Risk Score, Income, and High Risk %
- Region-wise distribution
- Top 10 critical risk customers

### 📌 Page 2: **Risk Profile & Employment Insights**
- Avg loan amount & interest rate
- Scatter plot of risk vs loan amount
- Loan trends by employment type

### 📌 Page 3: **Repayment and Credit Actions**
- % Auto Approved, Late Payment Ratio
- Review decisions by region and risk category
- Customer-level risk and repayment details

---

## 🧪 Sample Results

| Customer ID | Credit Score | Action   |
|-------------|--------------|----------|
| 1888        | 0.98         | Reject   |
| 1532        | 0.72         | Review   |
| 1042        | 0.21         | Approve  |

---

## 🧰 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-score-project.git
