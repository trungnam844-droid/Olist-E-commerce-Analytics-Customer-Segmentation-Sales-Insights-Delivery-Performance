# 📊 Olist E-commerce Data Analysis | Python & Power BI
**Project Type:** End-to-End Data Analytics | E-commerce | Customer Segmentation

> End-to-end data analysis project using Python and Power BI to uncover key drivers of revenue, customer behavior, and delivery performance in an e-commerce business.

---

## 📌 Project Overview
This project analyzes the **Olist Brazilian E-commerce dataset** to uncover insights into sales performance, customer behavior, product performance, and delivery efficiency.

The objective is to transform raw data into **actionable business insights** and build an interactive dashboard to support decision-making.

---

## 🎯 Business Objectives
- Analyze revenue trends and key drivers  
- Segment customers using RFM analysis  
- Evaluate delivery performance and its impact on customer satisfaction  
- Identify top-performing product categories  
- Provide data-driven business recommendations  

---

## 📊 Dashboard Preview

### 🔹 Executive Overview
![Executive Overview](images/overview.png)

### 🔹 Customer Analysis
![Customer Analysis](images/customer.png)

### 🔹 Product Performance
![Product Performance](images/product.png)

### 🔹 Delivery Performance
![Delivery Performance](images/delivery.png)

---

## 📂 Dataset Overview
The dataset includes multiple relational tables:

- Customers  
- Orders  
- Order Items  
- Payments  
- Reviews  
- Products  
- Sellers  
- Geolocation  

These datasets provide a **complete view of the customer journey**, from purchase to delivery and customer feedback.

---

## 🧹 Data Cleaning & Feature Engineering (Python)

### Tools:
- Pandas  
- NumPy  

### Key Steps:
- Handled missing values and inconsistent data  
- Converted datetime fields for time-series analysis  
- Merged multiple datasets into a unified model  
- Created key business metrics:
  - Delivery delay (days)  
  - Average Order Value (AOV)  
  - RFM segmentation (Recency, Frequency, Monetary)  

---

## 🔍 Exploratory Data Analysis (EDA)

### 📈 Sales Overview
- **Total Revenue:** 13.2M  
- **Total Orders:** 96K  
- **AOV:** 137  

👉 Revenue shows a **steady growth trend with noticeable seasonal fluctuations**, indicating demand variability across time.

---

### 👥 Customer Segmentation (RFM)

Customers were segmented into:
- Champions  
- Loyal Customers  
- At Risk  
- Churned  
- New Customers  

**Key Insights:**
- At Risk customers contribute the **largest share of revenue (~35%)**  
- More than **60% of customers fall into At Risk and Churned segments**

👉 The business is **heavily dependent on declining customer segments**, creating a high risk of future revenue loss.

---

### 📦 Product Performance
Top-performing categories:
- Health & Beauty  
- Watches & Gifts  
- Bed, Bath & Table  

👉 Revenue follows a **Pareto distribution**, where a small number of categories generate the majority of sales.

---

### 🚚 Delivery Performance
- Avg Delivery Time: ~12 days  
- On-time Rate: 93.2%  
- Delay Rate: ~6.8%  

👉 Orders with delays show **significantly lower review scores**, indicating a direct impact on customer satisfaction.

---

## 💡 Key Business Insights

### 1. Revenue is highly dependent on At Risk customers ⚠️
At Risk customers contribute ~35% of total revenue despite declining engagement.

👉 This creates a **significant risk of revenue drop** if retention strategies are not implemented.

---

### 2. Customer retention is weak despite strong acquisition
Over 60% of customers are either At Risk or Churned.

👉 The business is **acquisition-driven but lacks retention mechanisms**.

---

### 3. Revenue is concentrated in a few product categories
Top categories dominate overall sales.

👉 This presents both:
- ✔ Strength (clear revenue drivers)  
- ⚠ Risk (lack of diversification)

---

### 4. Delivery performance directly impacts customer satisfaction
Delayed orders correlate with lower review scores.

👉 Logistics is a **critical driver of customer experience and retention**.

---

### 5. Sales are concentrated in key regions
Certain states dominate revenue contribution.

👉 Opportunity to **expand into underpenetrated markets**.

---

## 📊 Power BI Dashboard

### 🔹 Executive Overview
- Revenue, Orders, AOV, Review Score KPIs  
- Revenue trend over time  
- Revenue distribution by state  

---

### 🔹 Customer Analysis
- RFM segmentation  
- Revenue contribution by segment  
- Customer distribution  

---

### 🔹 Product Performance
- Top categories analysis  
- Pareto chart  
- Revenue vs Freight cost  

---

### 🔹 Delivery Performance
- Delivery time distribution  
- Delay % KPI  
- Impact of delays on customer reviews  

---

## 🛠️ Tech Stack

### Python
- Pandas  
- NumPy  

### Power BI
- Power Query  
- Data Modeling  
- DAX  
- Data Visualization  

---

## 🚀 Business Recommendations

- 🎯 **Target At Risk customers** with personalized campaigns to prevent churn and stabilize revenue  

- 🚚 **Optimize logistics operations** in high-delay regions to improve delivery time and customer satisfaction  

- 📦 **Focus on top-performing product categories** to maximize revenue efficiency and inventory planning  

- 💡 **Implement loyalty programs** to increase customer lifetime value (CLV) and improve retention  

---
  
## 📎 Project Structure

```
olist-ecommerce-analysis/
│
├── data/                  # Raw dataset (optional / sample)
│
├── notebooks/             # Python EDA & analysis
│   └── olist_analysis.ipynb
│
├── dashboard/             # Power BI dashboard file
│   └── olist_dashboard.pbix
│
├── images/                # Dashboard screenshots used in README
│   ├── overview.png
│   ├── customer.png
│   ├── product.png
│   └── delivery.png
│
└── README.md              # Project documentation
```

---

## 👤 Author
**Nam Tran**  
Aspiring Data Analyst | Financial Data Analyst
