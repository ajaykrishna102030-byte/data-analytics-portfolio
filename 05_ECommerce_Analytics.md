# 5. E-Commerce Analytics

### Project Overview
This project analyzes e-commerce data to optimize sales, marketing, and customer experience. It covers sales trends, customer behavior, marketing performance, and conversion funnel analysis.

---

### Objective
- Track sales & revenue
- Analyze customer behavior
- Optimize marketing performance

---

### Tools Used
- **SQL** – Order and customer data analysis
- **Excel** – Initial exploration and quick insights
- **Python** – Data cleaning, customer segmentation, and advanced analysis
- **Power BI** – Interactive E-Commerce Analytics Dashboard

---

### Key Analysis
- Sales & revenue trends
- Customer segmentation
- Marketing performance
- Funnel analysis

---

### Dataset
**Recommended Dataset Options:**

1. **Online Retail II** (UCI / Kaggle) – Very popular
2. **Brazilian E-Commerce (Olist)** – Rich multi-table dataset
3. **Any e-commerce orders dataset** with Order, Customer, Product, and Marketing data

**Ideal Columns / Tables:**
- Order ID, Order Date, Customer ID
- Product ID, Category, Price, Quantity
- Payment Method, Order Status
- Marketing Source / Campaign (if available)
- Shipping / Delivery information

---

### Project Structure
```
ECommerce_Analytics/
├── data/
│   ├── raw/
│   └── cleaned/
├── sql/
│   └── ecommerce_queries.sql
├── python/
│   └── ecommerce_eda.ipynb
├── powerbi/
│   └── ECommerce_Analytics_Dashboard.pbix
├── excel/
│   └── Ecommerce_Exploration.xlsx
├── README.md
└── insights/
    └── key_findings.md
```

---

### Suggested Analysis Steps

1. **Data Cleaning**
   - Remove cancelled / returned orders if needed
   - Handle missing customer or product information
   - Create date features (Year, Month, Day of Week)
   - Calculate Order Value and Revenue

2. **Sales & Revenue Analysis**
   - Daily / Monthly / Yearly sales trend
   - Top selling products and categories
   - Average Order Value (AOV)
   - Revenue by Customer Segment

3. **Customer Behavior**
   - New vs Returning customers
   - Customer purchase frequency
   - RFM-style segmentation (Recency, Frequency, Monetary) if data allows

4. **Marketing & Funnel (if data available)**
   - Performance by traffic source / campaign
   - Conversion rate analysis
   - Drop-off points in the funnel

5. **Power BI Dashboard**
   - KPI Cards: Total Revenue, Total Orders, AOV, Total Customers
   - Line Chart: Sales Trend over time
   - Bar Charts: Top Products & Categories
   - Customer Segment breakdown
   - Slicers: Date, Category, Region / Country

---

### Expected Insights
- What are the peak sales periods?
- Which products drive the most revenue?
- How do different customer segments behave?
- Where can marketing efforts be optimized?

---

### Skills Demonstrated
- E-commerce metrics (AOV, Conversion, Revenue)
- Customer behavior analysis
- Sales trend & product performance
- Building business-ready e-commerce dashboards
