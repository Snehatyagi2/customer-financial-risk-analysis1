# 📊 Customer Financial Risk Analysis

## 🚀 Project Overview

This project analyzes customer financial behavior to understand whether income is a reliable indicator of financial discipline.

The goal was to move beyond basic data analysis and build a **behavior-driven financial risk profiling system** that can help businesses make smarter decisions related to customer targeting, credit risk, and spending behavior.

---

## 🎯 Objectives

- Analyze relationship between income and spending behavior  
- Identify financially risky vs stable customers  
- Build behavior-based customer segmentation  
- Develop a simple financial **Risk Scoring Model**  
- Extract actionable business insights  

---

## 📁 Dataset

- Source: Kaggle – Customer Personality Analysis Dataset  
- Type: Customer demographics + spending data  

---

## 🧠 Feature Engineering

The following features were created to enhance analysis:

- **Total_Spending** → Sum of all spending categories  
- **Spending_to_Income Ratio** → Measures financial discipline  
- **Income_Group** → Low / Middle / High segmentation  
- **Spender_Class** → Saver / Balanced / Overspender  
- **Customer_Type** → Combined persona classification  

---

## ⚠️ Risk Scoring Model

A custom **Risk Score** was developed to quantify financial risk:

- Based on:
  - Spending-to-Income ratio (behavioral risk)
  - Normalized total spending (absolute risk)

### Risk Formula:

Risk Score = (0.7 × Spending_to_Income) + (0.3 × Normalized Spending)

---

## 🔴 Risk Categories

- **High Risk** → Overspending relative to income  
- **Medium Risk** → Moderate financial behavior  
- **Low Risk** → Financially stable customers  

---

## 📊 Key Analysis Performed

- Income vs Spending behavior  
- Risk distribution across income groups  
- Spender class impact on financial risk  
- Customer persona-based segmentation  
- Identification of extreme spenders and savers  

---

## 🧠 Key Insights

- Income is NOT a reliable indicator of financial discipline  
- Overspending behavior exists across all income groups  
- Some high-income customers are financially risky  
- Middle-income customers show relatively balanced behavior  
- Behavioral segmentation is more powerful than income-based segmentation  

---

## 📉 Most Interesting Finding

High income does not guarantee financial stability.  
Several high-income users exhibited high risk due to aggressive spending behavior, while some low-income users maintained disciplined financial habits.

---

## 💼 Business Applications

This project can be used for:

- Credit risk assessment  
- Customer targeting strategies  
- Financial behavior monitoring  
- Marketing segmentation  
- Personalized financial product recommendations  

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)  
- Data Cleaning & Feature Engineering  
- Exploratory Data Analysis (EDA)  
- Basic Risk Modeling  

---

## 📊 Project Structure

```
customer-financial-risk-analysis/
│
├── data/
│   └── customer_risk_dataset.csv
│
├── notebooks/
│   └── customer_risk_analysis.ipynb
│
├── outputs/
│   └── charts/ (optional screenshots)
│
└── README.md
```
---

## 💡 Conclusion

Financial behavior is not purely driven by income.  
It is strongly influenced by spending habits and behavioral patterns.

This project demonstrates the importance of shifting from **income-based analysis to behavior-based intelligence systems** in financial decision-making.

---

## 🚀 Future Improvements

- Build machine learning model for risk prediction  
- Develop interactive dashboard (Power BI / Tableau)  
- Add time-based spending trends  
- Integrate real-world financial datasets  

---

## 📌 Author

Sneha Tyagi  
Aspiring Data Analyst | AI & Financial Analytics Enthusiast  

---

## 🔗 Connect with me

(You can add your LinkedIn link here)
