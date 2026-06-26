# 🛒 Retail Sales Performance Dashboard | Power BI

## 📌 Project Overview

The **Retail Sales Performance Dashboard** is an interactive Power BI solution designed to provide comprehensive insights into retail business performance across products, regions, cities, store types, and customer segments.

This dashboard enables business leaders, sales managers, and analysts to monitor sales growth, profitability, customer behavior, and geographical performance, helping organizations make informed strategic decisions and improve overall business outcomes.

---

## 🎯 Business Objective

The objective of this dashboard is to:

* Track overall sales and profitability performance.
* Analyze sales trends across multiple years.
* Identify top-performing products and regions.
* Monitor store-wise sales contribution.
* Evaluate geographical sales distribution.
* Compare current sales against previous year performance.
* Support strategic planning and revenue optimization.

---

## 📊 Executive KPI Summary

The dashboard provides a high-level view of critical retail metrics:

| KPI                 | Value           |
| ------------------- | --------------- |
| Total Sales         | ₹4.72 Billion   |
| Total Quantity Sold | 316K Units      |
| Total Profit        | ₹873.55 Million |
| Profit Margin       | 5.41%           |

These KPIs offer a quick snapshot of business performance and profitability.

---

## 📈 Key Dashboard Insights

### 1. Product Performance Analysis

The dashboard highlights the Top 10 selling products based on revenue contribution.

#### Top Performing Products

* Desk
* Washing Machine
* Bookshelf
* Office Chair
* Headphones
* Microwave
* Marker
* Smartphone
* Pen
* Tablet

### Key Insight

* Furniture and consumer electronics dominate overall sales.
* High-performing products contribute significantly to total revenue.

---

### 2. Sales Distribution by Store Type

Sales contribution across different retail channels.

| Store Type | Sales Contribution |
| ---------- | ------------------ |
| Online     | 37.89%             |
| Offline    | 31.66%             |
| Franchise  | 30.44%             |

### Key Insight

* Online channels generate the highest share of sales.
* Digital commerce continues to be a major revenue driver.

---

### 3. Regional Sales Analysis

Sales performance across geographical regions.

| Region | Contribution |
| ------ | ------------ |
| West   | 32.59%       |
| North  | 31.78%       |
| South  | 31.71%       |
| East   | 3.92%        |

### Key Insight

* Western and Northern regions contribute the largest share of revenue.
* Eastern region presents growth opportunities.

---

### 4. State-Wise Sales Distribution

The dashboard visualizes sales performance across major Indian states.

### States Covered

* Maharashtra
* Gujarat
* Rajasthan
* Delhi
* Uttar Pradesh
* Telangana
* Karnataka
* Tamil Nadu
* West Bengal

### Key Insight

* Maharashtra and major metropolitan regions contribute significantly to total sales.
* Geographic visualization helps identify high-performing markets.

---

### 5. Sales vs Previous Year Sales

Monthly comparison between current sales and previous year performance.

### Business Benefits

* Measure year-over-year growth.
* Identify seasonal trends.
* Monitor business expansion.
* Evaluate performance against targets.

### Key Insight

* Current year sales consistently outperform previous year sales across most months.
* Indicates healthy business growth and market expansion.

---

### 6. Top Performing Cities

The dashboard identifies cities contributing the highest revenue and profit.

| City      | Sales | Profit   | Quantity |
| --------- | ----- | -------- | -------- |
| Pune      | ₹768M | ₹141.76M | 51K      |
| Jaipur    | ₹580M | ₹107.13M | 38K      |
| Chennai   | ₹559M | ₹102.34M | 38K      |
| Bengaluru | ₹472M | ₹89.54M  | 32K      |
| Ahmedabad | ₹483M | ₹89.34M  | 32K      |

### Key Insight

* Pune is the highest revenue-generating city.
* Jaipur and Chennai are strong contributors to profitability.

---

## 👥 Customer Segmentation Analysis

The dashboard allows analysis by customer segments, enabling businesses to:

* Understand customer purchasing behavior.
* Evaluate segment-wise profitability.
* Develop targeted marketing campaigns.
* Improve customer retention strategies.

---

## 🎛️ Interactive Dashboard Features

### Dynamic Filters

Users can analyze data using:

#### Year Selection

* 2019
* 2020
* 2021
* 2022
* 2023
* 2024

#### Customer Segment Filter

* Consumer
* Corporate
* Home Office
* Other Segments

This enables detailed exploration of sales performance across multiple dimensions.

---

## 🛠️ Tools & Technologies Used

| Technology            | Purpose                    |
| --------------------- | -------------------------- |
| Power BI Desktop      | Dashboard Development      |
| Power Query           | Data Transformation        |
| DAX                   | KPI & Measure Creation     |
| Excel / CSV Dataset   | Data Source                |
| Bing Maps             | Geographical Visualization |
| Business Intelligence | Data Analysis              |

---

## 📂 Dataset Overview

The dataset includes:

* Order ID
* Order Date
* Product Name
* Product Category
* Customer Segment
* Store Type
* City
* State
* Region
* Quantity Sold
* Sales Amount
* Profit
* Profit Margin

---

## 📐 DAX Measures Used

### Total Sales

```DAX
Total Sales =
SUM(Sales[Sales Amount])
```

### Total Profit

```DAX
Total Profit =
SUM(Sales[Profit])
```

### Total Quantity

```DAX
Total Quantity =
SUM(Sales[Quantity])
```

### Profit Margin %

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
) * 100
```

### Previous Year Sales

```DAX
Previous Year Sales =
CALCULATE(
    [Total Sales],
    SAMEPERIODLASTYEAR(Calendar[Date])
)
```

---

## 📷 Dashboard Preview

![Retail Sales Dashboard](Images/Retail_Sales_Performance_Dashboard.png)

---

## 🔍 Business Findings

### Revenue Drivers

* Online sales channels generate the highest revenue.
* Furniture and electronics categories lead sales performance.

### Regional Performance

* West, North, and South regions contribute nearly equal revenue shares.
* East region has potential for market expansion.

### City Performance

* Pune is the strongest market by revenue and profit.
* Major metropolitan cities consistently drive sales growth.

### Profitability

* Profit margin remains positive and stable.
* Sales growth is accompanied by healthy profit generation.

---

## 💡 Recommendations

### Sales Growth

* Expand marketing initiatives in high-performing regions.
* Strengthen online sales channels.

### Market Expansion

* Focus on increasing market penetration in Eastern India.
* Develop localized campaigns for emerging cities.

### Product Strategy

* Maintain inventory availability for top-selling products.
* Bundle complementary products to increase average order value.

### Customer Retention

* Implement loyalty programs for high-value customer segments.
* Personalize offers based on customer purchase history.

---

## 🚀 Future Enhancements

* Sales Forecasting using Machine Learning.
* Customer Lifetime Value (CLV) Analysis.
* Product Recommendation Engine.
* Inventory Optimization Dashboard.
* Real-Time Sales Monitoring.
* Customer Churn Prediction.

---

## 📁 Repository Structure

```text
Retail-Sales-Performance-Dashboard/
│
├── Dataset/
│   └── Retail_Sales_Data.xlsx
│
├── Dashboard/
│   └── Retail_Sales_Performance.pbix
│
├── Images/
│   └── Dashboard_Screenshot.png
│
├── README.md
│
└── LICENSE
```

---

## 👨‍💻 Author

**Shivam Kr. Rajput**

Data Analyst | Power BI Developer | SQL | Python | Excel | Business Intelligence

### Skills

* Power BI
* SQL
* Python
* Excel
* Data Visualization
* Business Analytics
* Dashboard Development

### Connect With Me

* LinkedIn: [www.linkedin.com/in/shivamkrrajput](http://www.linkedin.com/in/shivamkrrajput)
* GitHub: github.com/rajputshivam011

---

## ⭐ Project Impact

This dashboard demonstrates how Power BI can transform retail sales data into actionable business insights. By analyzing sales performance, profitability, regional trends, and customer behavior, organizations can make data-driven decisions that improve revenue, optimize operations, and strengthen competitive advantage.

**If you found this project useful, please give it a ⭐ Star on GitHub!**
