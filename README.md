# 📊 Customer Retention & Churn Analysis  
**By: Armaan Patel**  
**Date:** October 2025  

---

## 📂 Files
| Type | File | Description |
|------|------|--------------|
| 📁 Dataset | `Telco-Customer-Churn.csv` | Customer demographics, billing, and service data |
| 💻 Notebook | `Customer Retention and Churn.ipynb` | Data cleaning, analysis, and machine learning models |
| 📊 Dashboard | `Customer Churn Analysis.pbix` | Power BI dashboards for executive and segmentation insights |

---

## 🎯 Project Goals
- Analyze historical telecom customer data to uncover churn and retention patterns.  
- Calculate and visualize **Key Performance Indicators (KPIs)**: churn %, revenue lost, avg tenure, etc.  
- Build **predictive models** (Logistic Regression & Random Forest) to classify churn risk.  
- Create **interactive Power BI dashboards** for executives and analysts.

---

## 🛠️ Tools & Libraries
**Tools:** JupyterLab, Power BI  
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

## 🧠 Project Summary

### 🔹 Objective
Understand and predict customer churn within a telecom company, identifying high-risk customer segments, and recommending data-driven retention strategies.

### 🔹 Business Value
Reducing churn directly increases recurring revenue.  
By identifying at-risk customers early, the company can target campaigns (discounted annual contracts, auto-pay incentives, loyalty programs) that improve retention and lifetime value.

---

## 📈 Insights from Analysis
| Category | Key Findings |
|-----------|---------------|
| **Churn Rate** | ~27 % of all customers churned. |
| **Contract Type** | Month-to-month contracts churn **3×** more than annual contracts. |
| **Billing Method** | Customers using **Electronic Check** show the highest churn. |
| **Tenure** | Early-tenure customers (0–12 months) are most likely to leave; churn drops sharply after 2 years. |
| **Charges** | Higher `MonthlyCharges` correlate with higher churn, especially with low tenure. |
| **Services** | Customers lacking add-ons such as **Tech Support** or **Online Security** are more likely to churn. |

---

## 🤖 Predictive Modeling Results
| Model | ROC-AUC Score | Highlights |
|--------|----------------|-------------|
| **Logistic Regression** | 0.835  | Baseline classification model with balanced precision/recall. |
| **Random Forest** | 0.831  | Captures nonlinear patterns; confirms top churn predictors. |

**Top Predictive Features:**  
`Tenure`, `Contract`, `MonthlyCharges`, `PaymentMethod`

---

## 💡 Recommendations
1. **Promote annual contracts** with targeted discounts to reduce short-term churn.  
2. **Encourage auto-pay/credit-card billing** to replace high-risk electronic check users.  
3. **Implement first-year loyalty programs** — most churn occurs in the first 6 months.  
4. **Bundle value-added services** (Tech Support, Online Security) to improve customer stickiness.

---

## 📊 Power BI Dashboard Deliverables

### **Page 1 – Executive Overview**
- KPIs: Total Customers, Churned Customers, Churn Rate %, Revenue Lost (Annualized)  
- Visuals: Churn % by Contract, Internet Service, Tenure Band, Payment Method  
- Slicers: Contract, Internet Service, Payment Method, Tenure Band  

### **Page 2 – Segmentation & Demographics**
- Churn % by Gender and Senior Status  
- Churn % by Partner and Dependents  
- Scatter: Tenure vs Monthly Charges (colored by Churn)  
- Matrix Table: Segment-level Churn Rates with Conditional Formatting  
- Slicers: Gender, Senior Label, Partner, Dependents  

<img width="1456" height="817" alt="image" src="https://github.com/user-attachments/assets/d640f84b-61d9-4694-9871-f8c14144ec70" />
<img width="1442" height="805" alt="image" src="https://github.com/user-attachments/assets/1033d5a5-5feb-4df1-96f5-6a4509b826ae" />

