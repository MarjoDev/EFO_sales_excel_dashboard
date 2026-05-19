# 📊 Electronics / Furniture / Office Supplies Sales Dashboard

![Dashboard Preview](screenshots/efo_dashboard_preview.jpg)

## 🎯 Objective

This project was developed to analyze sales and profit performance across different product categories, states and payment methods through an interactive Excel dashboard.

The dashboard allows dynamic filtering using slicers and highlights important KPIs such as total profit, most used payment method and least used payment method using INDEX + MATCH formulas.

---

## 🛠 Skills Demonstrated

* Interactive Dashboard Design
* KPI Development
* INDEX + MATCH Functions
* Pivot Tables
* Pivot Charts
* Data Visualization
* Conditional Formatting
* Slicers & Dynamic Filters
* Business Analysis
* Data Aggregation
* Excel Formula Optimization

---

## 📈 Dashboard Features

### 🔹 KPIs

* Total Profit
* Most Used Payment Method
* Least Used Payment Method

### 🔹 Interactive Filters

* State slicer
* Category slicer

### 🔹 Visualizations

* Profit by Sub-Category
* Monthly Profit Distribution
* Dynamic category filtering

---

## 🧠 Formula Logic Used

The dashboard uses dynamic formulas with `INDEX` and `MATCH` to retrieve KPI information based on filtered Pivot Table results.

Example applications:

* Finding the most used payment method
* Finding the least used payment method
* Dynamic lookup of KPI values
* Conditional metric retrieval

Example formula structure:

```excel
=INDEX(return_range,MATCH(lookup_value,lookup_range,0))
```

---

## ⚙️ Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Slicers
* INDEX + MATCH
* Conditional Formatting

---

## 📂 Dataset

The dataset contains fictional retail sales information including:

* Order ID
* Value
* Cost
* Quantity
* Customer Name
* Order Date
* Product categories
* Sub-categories
* Profit
* Payment methods
* Year Month
* State
* City

---

## 📌 Key Insights

* Debit Card was the most used payment method.
* COD presented the lowest usage frequency.
* Markers generated the highest profit among sub-categories.
* Profit distribution remained relatively stable across months.

---

## 🚀 Future Improvements

Possible future improvements for this dashboard:

* Add Power Query automation
* Add Power Pivot relationships
* Create YoY growth analysis
* Add dynamic ranking system
* Include advanced KPI cards
