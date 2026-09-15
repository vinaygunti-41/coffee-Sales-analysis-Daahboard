# ☕ Coffee Sales Performance Dashboard | Power BI

   ### 📊 Retail Sales Analytics • Customer Behavior • Revenue Insights • Business Intelligence

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=24&duration=3500&pause=1000&color=39FF14&center=true&vCenter=true&width=800&lines=Coffee+Sales+Performance+Dashboard;Interactive+Power+BI+Business+Dashboard;Power+Query+%7C+DAX+%7C+Data+Visualization;Transforming+Coffee+Sales+into+Business+Insights"/>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Business%20Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Power%20Query-Data%20Cleaning-0B8043?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/DAX-Measures-0057B8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoftexcel"/>
</p>

### 🚀 Interactive Coffee Shop Sales Dashboard with Revenue, Orders & Peak Sales Analysis

</div>

---

## 📌 Project Overview

The **Coffee Sales Performance Dashboard** is a business intelligence project built in **Power BI** to analyze coffee shop transaction data and uncover valuable sales insights.

This dashboard enables coffee shop owners and retail managers to monitor **sales performance, customer purchasing behavior, product demand, and peak business hours** through interactive visualizations.

> 🎯 **Goal:** Convert raw transaction data into meaningful insights for smarter retail decision-making.

---

# 🎯 Business Problem

Coffee shops generate thousands of transactions every day. Without analytics, it's difficult to identify:

* Peak business hours.
* Best-selling coffee products.
* Customer purchase trends.
* Revenue growth opportunities.
* Weekday vs Weekend performance.

This dashboard solves these challenges using **Power BI, Power Query, and DAX**.

---

# 🎯 Project Objectives

* 📈 Analyze overall coffee shop sales performance.
* ☕ Identify top-selling coffee products.
* ⏰ Discover peak customer purchase hours.
* 📅 Compare weekday and weekend sales.
* 💰 Calculate revenue, orders, and average transaction value.
* 📊 Build an interactive business dashboard for decision-making.

---

# 🛠️ Tech Stack

| Technology         | Purpose                        |
| ------------------ | ------------------------------ |
| 📊 Power BI        | Dashboard Development          |
| ⚙️ Power Query     | Data Cleaning & Transformation |
| 🧮 DAX             | KPI Measures & Calculations    |
| 📗 Microsoft Excel | Data Preparation               |

---

# 📂 Dataset Information

<table>
<tr><td><strong>Dataset</strong></td><td>Coffee Shop Sales Dataset</td></tr>
<tr><td><strong>Domain</strong></td><td>Retail / Food & Beverage</td></tr>
<tr><td><strong>Records</strong></td><td>Transaction-Level Sales Data</td></tr>
<tr><td><strong>Format</strong></td><td>Excel / CSV</td></tr>
</table>

### 📋 Dataset Includes

* 📅 Order Date
* ⏰ Order Time
* ☕ Coffee Product
* 🧾 Transaction ID
* 💰 Sales Amount
* 🛍️ Product Category
* 📍 Store / Branch
* 📦 Quantity Sold

---

# 🧹 Data Preparation

The raw dataset was transformed using **Power Query** before visualization.

### ✔️ Data Cleaning Steps

* Removed duplicate transactions.
* Handled missing values.
* Converted date & time formats.
* Cleaned product names.
* Created calculated columns.
* Standardized categories.

---

# 📈 Dashboard Workflow

```text
Coffee Shop Sales Dataset
          │
          ▼
Data Cleaning (Power Query)
          │
          ▼
DAX Measures & KPIs
          │
          ▼
Interactive Power BI Dashboard
          │
          ▼
Business Insights & Decision Making
```

---

# 📊 Dashboard KPIs

| KPI                    | Value                |
| ---------------------- | -------------------- |
| 💰 Total Revenue       | ₹112K                |
| 🧾 Total Orders        | Transaction Count    |
| 💵 Average Order Value | Calculated using DAX |
| ☕ Top Selling Product  | Latte                |
| ⭐ Second Best Product  | Cappuccino           |

---

# 📌 Dashboard Features

### Executive Dashboard Includes

| Feature                     | Description                           |
| --------------------------- | ------------------------------------- |
| 💰 Revenue KPI Cards        | Total Revenue, Orders & Average Sales |
| ⏰ Hourly Sales Trend        | Peak Sales by Hour                    |
| 📅 Daily Sales Analysis     | Weekday vs Weekend                    |
| ☕ Product Category Analysis | Coffee Category Comparison            |
| 📈 Revenue Trend            | Sales Over Time                       |
| 🎛️ Interactive Filters     | Date, Product & Category Slicers      |

---

# 📊 Key Business Insights

### 💰 Revenue Performance

* Total Revenue reached **₹112,000**.
* Morning hours generated the highest revenue.

### ⏰ Peak Customer Hours

* **10 AM** recorded the maximum customer activity.
* Morning coffee demand significantly outperformed afternoon sales.

### 📅 Sales Comparison

* Weekday sales exceeded weekend sales.
* Weekends showed lower customer traffic.

### ☕ Product Performance

| Product       | Performance          |
| ------------- | -------------------- |
| ☕ Latte       | Highest Sales        |
| 🥛 Cappuccino | Second Highest Sales |
| 🍫 Mocha      | Strong Demand        |
| 🍵 Espresso   | Moderate Sales       |

---

# 📈 DAX Measures Used

```DAX
Total Revenue =
SUM(Sales[Sales Amount])

Total Orders =
DISTINCTCOUNT(Sales[Transaction ID])

Average Order Value =
DIVIDE([Total Revenue],[Total Orders])
```

Additional DAX calculations include:

* Daily Revenue
* Hourly Revenue
* Weekday Sales
* Weekend Sales
* Product Ranking

---

# 📊 Dashboard Visualizations

### Included Visuals

* 📊 KPI Cards
* 📈 Line Chart (Hourly Sales Trend)
* 📅 Column Chart (Daily Revenue)
* ☕ Bar Chart (Top Products)
* 🥧 Product Category Distribution
* 📍 Interactive Slicers
* 📉 Revenue Trend Analysis

---

# 🚀 Repository Structure

```bash
Coffee-Sales-Performance-Dashboard/
│
├── Coffee Sales Dashboard.pbix
├── Coffee Shop Sales Dataset.xlsx
├── README.md
├── Dashboard Preview.png
└── Assets/
      ├── Icons
      ├── Images
      └── Backgrounds
```

---

# 📷 Dashboard Preview

<img width="1595" height="909" alt="Screenshot 2026-03-05 173222" src="https://github.com/user-attachments/assets/7cd04061-4911-48bc-87b4-dd66408bb872" />


<p align="center">
<img width="900" src="images/coffee-sales-dashboard.png">
</p>

---

# 📌 Business Impact

This dashboard helps coffee shop owners:

* 📦 Optimize inventory for high-demand products.
* 👨‍💼 Schedule staff during peak morning hours.
* 🎯 Plan pricing and promotional campaigns.
* 📈 Improve operational efficiency using sales analytics.
* 💰 Increase profitability through data-driven decisions.

---

# 🌟 Future Improvements

* ✅ Regional Store Performance Analysis.
* ✅ Customer Segmentation Dashboard.
* ✅ Profit & Cost Analysis.
* ✅ Forecast Coffee Sales using Machine Learning.
* ✅ SQL + Power BI Live Dashboard.

---

# 📚 Skills Demonstrated

* Power BI Dashboard Design
* Power Query Data Transformation
* DAX Measures & KPIs
* Sales Performance Analysis
* Retail Business Intelligence
* Interactive Data Visualization

---

# 👨‍💻 Author

<div align="center">

## Gunti Vinay

### 💚 Aspiring Data Analyst | • SQL • Power BI 

<p align="center">
  <a href="https://github.com/vinaygunti-41">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
  </a>

  <a href="https://linkedin.com/in/vinaygunti-dataanalyst">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/>
  </a>

  <a href="https://devoted-jade-0of9azstaa.edgeone.app/">
    <img src="https://img.shields.io/badge/Portfolio-39FF14?style=for-the-badge&logo=google-chrome&logoColor=black"/>
  </a>
</p>

**📊 Transforming Retail Data into Business Insights**

</div>

---

<div align="center">

## ⭐ If you found this project helpful, please Star ⭐ this repository!

### ☕ Built with Power BI • Data Analytics • Business Intelligence

**Made with ❤️ by Gunti Vinay**

</div>
