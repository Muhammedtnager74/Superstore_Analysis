# Sales & Profit Analysis Dashboard – Power BI

## Project Overview

This project analyzes retail sales performance using Power BI to uncover business insights related to profitability, discount strategies, regional performance, and product efficiency.

The goal is to move beyond reporting numbers and focus on **business decision-making insights**.

---

## Business Objectives

* Identify loss-driving products and categories
* Analyze the impact of discounts on profitability
* Detect high-sales but low-profit segments
* Evaluate regional business performance
* Measure operational efficiency using Profit Margin

---

## Key Business Questions

* Which categories generate losses?
* Do higher discounts increase or destroy profit?
* Are high sales always profitable?
* Which regions need pricing optimization?
* What products should the business scale or reconsider?

---

## Dataset

* Superstore Sales Dataset
* 9,994 transactions
* Multiple dimensions:

  * Customer
  * Product
  * Region
  * Shipping
  * Sales & Profit Metrics

---

## Tools & Technologies

* Power BI
* Power Query (Data Cleaning)
* DAX Measures
* Data Modeling
* Business KPI Design

---

## Data Preparation

* Converted Postal Code → Text datatype
* Handled missing values
* Created calculated measures
* Built Profitability metrics

---

## Key Metrics (DAX)

**Total Sales**

```
Total Sales = SUM(Sales[Sales])
```

**Total Profit**

```
Total Profit = SUM(Sales[Profit])
```

**Profit Margin**

```
Profit Margin = DIVIDE([Total Profit],[Total Sales])
```

---

## Dashboard Visualizations

* KPI Cards (Sales, Profit, Profit Margin)
* Sales Trend Analysis
* Regional Performance Map
* Category Profitability Analysis
* Discount vs Profit Analysis
* Scatter Plot (Sales vs Profit vs Quantity)

---

## Key Insights

* High discounts (>30%) consistently lead to losses
* Some categories generate strong sales but poor margins
* Profitability varies significantly across regions
* Sales growth does not always mean business growth

---

## Business Recommendations

* Reduce aggressive discounting strategies
* Focus on high-margin product categories
* Reevaluate loss-generating segments
* Optimize pricing strategy by region

---

## Project Outcome

This dashboard transforms raw transactional data into actionable business intelligence supporting strategic decision-making.

---

## Author

**Mohamed Sameh Tnager**
Aspiring Data Analyst | Power BI | SQL | Python | Data Visualization
