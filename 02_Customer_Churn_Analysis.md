# 2. Customer Churn Analysis

### Project Overview
This project analyzes customer behavior to identify churn patterns and key retention drivers. The goal is to help the business reduce customer attrition by understanding why customers leave and recommending effective retention strategies.

---

### Objective
- Identify churn customers
- Find key churn drivers
- Recommend retention strategies

---

### Tools Used
- **SQL** – Data extraction, customer filtering, and aggregation
- **Excel** – Initial exploration and summary tables
- **Python** – Data cleaning, exploratory analysis, and basic modeling (Pandas, Seaborn, Scikit-learn)
- **Power BI** – Interactive churn dashboard and insights visualization

---

### Key Analysis
- Churn rate calculation
- Customer segmentation
- Churn drivers analysis
- Retention insights

---

### Dataset
**Recommended Dataset:** Telco Customer Churn Dataset (very popular and clean)

- Source: Kaggle – “Telco Customer Churn”
- Contains customer demographic, account, and service information along with churn flag.

**Key Columns usually include:**
- CustomerID
- Gender, SeniorCitizen, Partner, Dependents
- Tenure (months)
- PhoneService, InternetService, Contract, PaymentMethod
- MonthlyCharges, TotalCharges
- Churn (Yes/No)

---

### Project Structure
```
Customer_Churn_Analysis/
├── data/
│   ├── raw/
│   └── cleaned/
├── sql/
│   └── churn_analysis_queries.sql
├── python/
│   └── churn_eda_and_insights.ipynb
├── powerbi/
│   └── Customer_Churn_Dashboard.pbix
├── excel/
│   └── Churn_Exploration.xlsx
├── README.md
└── insights/
    └── key_findings.md
```

---

### Suggested Analysis Steps

1. **Data Cleaning**
   - Handle missing TotalCharges
   - Convert data types
   - Create tenure groups (0-12, 13-24, 25-48, 49+ months)

2. **Churn Rate Analysis**
   - Overall churn rate
   - Churn rate by Contract type
   - Churn rate by Internet Service
   - Churn rate by Payment Method
   - Churn rate by Tenure group

3. **Driver Analysis**
   - Which factors are most associated with churn?
   - Impact of Monthly Charges on churn
   - Effect of having Partner / Dependents
   - Senior citizens vs non-senior churn

4. **Power BI Dashboard**
   - KPI Cards: Total Customers, Churned Customers, Churn Rate %
   - Donut / Pie: Churn vs Active
   - Bar Charts: Churn by Contract, Internet Service, Payment Method
   - Tenure distribution of churned customers
   - Slicers for filtering

---

### Expected Insights
- Customers on Month-to-Month contracts have significantly higher churn
- Higher monthly charges are linked to higher churn
- Longer tenure customers are more loyal
- Specific service combinations increase churn risk

---

### Skills Demonstrated
- Customer analytics
- Churn rate calculation & segmentation
- Identifying business drivers
- Building actionable retention insights
- Dashboard storytelling
