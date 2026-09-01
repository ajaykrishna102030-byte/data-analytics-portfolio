# 4. HR Analytics Dashboard

### Project Overview
This project analyzes HR data to understand employee trends and improve workforce planning. The focus is on attrition, employee performance, demographics, and departmental insights to support better HR decisions.

---

### Objective
- Analyze employee metrics
- Identify attrition trends
- Improve workforce planning

---

### Tools Used
- **SQL** – Data extraction and employee-level analysis
- **Excel** – Initial exploration and summary reports
- **Python** – Data cleaning, statistical analysis, and visualization
- **Power BI** – Interactive HR Analytics Dashboard

---

### Key Analysis
- Attrition analysis
- Department & role insights
- Diversity & demographics
- Performance trends

---

### Dataset
**Recommended Dataset:** IBM HR Analytics Employee Attrition & Performance Dataset

- Source: Kaggle – “IBM HR Analytics Employee Attrition & Performance”
- Very widely used for HR analytics projects.

**Key Columns include:**
- Age, Gender, MaritalStatus, Education
- Department, JobRole, JobLevel
- MonthlyIncome, YearsAtCompany, YearsInCurrentRole
- Attrition (Yes/No)
- JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance
- PerformanceRating, OverTime

---

### Project Structure
```
HR_Analytics_Dashboard/
├── data/
│   ├── raw/
│   └── cleaned/
├── sql/
│   └── hr_analysis_queries.sql
├── python/
│   └── hr_eda.ipynb
├── powerbi/
│   └── HR_Analytics_Dashboard.pbix
├── excel/
│   └── HR_Exploration.xlsx
├── README.md
└── insights/
    └── key_findings.md
```

---

### Suggested Analysis Steps

1. **Data Cleaning**
   - Check for missing values
   - Create age groups and tenure groups
   - Convert categorical variables properly

2. **Attrition Analysis**
   - Overall attrition rate
   - Attrition by Department
   - Attrition by Job Role
   - Attrition by OverTime (Yes/No)
   - Attrition by Age Group and Gender

3. **Workforce Insights**
   - Department-wise employee distribution
   - Average Monthly Income by Department / Job Role
   - Performance Rating distribution
   - Work-Life Balance and Satisfaction analysis

4. **Power BI Dashboard**
   - KPI Cards: Total Employees, Attrition Rate %, Average Tenure, Average Income
   - Bar Charts: Attrition by Department & Job Role
   - Demographics breakdown (Gender, Age Group, Education)
   - Satisfaction & Performance visuals
   - Slicers: Department, Gender, Job Level

---

### Expected Insights
- Which departments have the highest attrition?
- Does OverTime significantly increase attrition risk?
- How does income and tenure relate to leaving the company?
- Are there diversity gaps across departments?

---

### Skills Demonstrated
- HR metrics and attrition analysis
- Workforce planning insights
- Demographic & diversity analysis
- Building people analytics dashboards
