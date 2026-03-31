# 📊 Retail Sales Intelligence Dashboard (Power BI)

## 📌 Project Overview

This project presents a comprehensive **Retail Sales Intelligence Dashboard** built using Power BI. The objective is to transform raw retail data into meaningful insights that support strategic business decisions.

The dashboard enables stakeholders to monitor performance, identify trends, and uncover areas of improvement across products, regions, and customers.

---

## 🎯 Key Objectives

* Analyze **sales, profit, and order trends**
* Identify **top-performing products and categories**
* Detect **loss-making sub-categories**
* Understand **regional performance**
* Evaluate **customer-level contribution**

---

## 📊 Dashboard Features

### 🟦 Executive Overview

* Total Revenue, Profit, Orders, Profit Margin, YoY Growth
* Average Order Value & Total Customers
* Monthly Revenue Trend
* Revenue by Region & Category

### 🟩 Product & Category Analysis

* Top 10 Products by Revenue
* Profit by Sub-Category
* Category-wise Revenue vs Profit
* Loss-making Sub-Category identification

### 🟨 Customer & Regional Insights

* State-wise Sales Map
* Top Customers by Revenue
* Customer-level Profit Analysis

---

## 🧠 Key Insights

* The technology category generates the highest revenue but does not always yield the highest profit margins.
* Certain sub-categories (e.g., Tables, Bookcases) show consistent losses despite strong sales.
* The West region contributes the highest revenue, indicating a strong market presence.
* Sales trends indicate seasonal fluctuations useful for demand forecasting.

---

## 🛠️ Tools & Technologies

* **Power BI** (Data Visualization)
* **DAX** (Data Analysis Expressions)
* **Data Modeling**
* **Data Cleaning & Transformation**

---

## 📐 Key DAX Measures

``` DAX
Total_Revenue = SUM(Sales[Sales])

Total_Profit = SUM(Sales[Profit])

Total_Orders = DISTINCTCOUNT(Sales[Order ID])

Total_Customers = DISTINCTCOUNT(Sales[Customer ID])

Profit_Margin = DIVIDE([Total_Profit], [Total_Revenue])

Avg_Order_Value = DIVIDE([Total_Revenue], [Total_Orders])
```

---

## 🎨 Theme & Design

A custom Power BI theme was applied to ensure consistency and professional aesthetics.
The design focuses on clarity, readability, and business storytelling.

---

## 📁 Project Files

* 📊 Power BI Dashboard (.pbix)
* 📄 Dataset (Superstore)
* 🎨 Custom Theme (.json)
* 📜 DAX Measures


---

## 💬 Conclusion

This dashboard demonstrates how data visualization can go beyond reporting to deliver actionable insights. It highlights not only performance metrics but also business-critical issues such as loss-making segments and regional trends.

---

## 🤝 Connect With Me

If you found this project useful or have feedback, feel free to connect with me on LinkedIn.

Let’s build data-driven solutions together 🚀
