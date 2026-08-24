# Sales Performance Analytics Dashboard | Excel

## Project Overview

This project presents an end-to-end **sales performance analysis built in Microsoft Excel** using a dataset containing **3,000 sales transactions**.

The objective was to transform transactional sales data into an interactive management dashboard that provides visibility into revenue, profitability, product performance, geographic performance and sales trends.

The project demonstrates my ability to move from **raw data → data cleaning → analysis → KPI development → visualization → business insights** using Excel.

---

## Business Objective

Management needs a clear view of overall sales performance and wants to understand:

* How much revenue and profit is the business generating?
* What is the overall profit margin?
* Which product categories contribute the most revenue and profit?
* Which countries and markets perform best?
* Which products generate the strongest results?
* How is performance changing over time?
* Which areas may require management attention?

The final dashboard was designed to make these questions easier to answer from a single reporting view.

---

## Key Performance Indicators

The analysis tracks several core commercial KPIs:

| KPI                 | Result |
| ------------------- | -----: |
| Total Revenue       | 224.2M |
| Total Profit        |  40.5M |
| Profit Margin       |  18.1% |
| Total Orders        |  3,000 |
| Units Sold          | 13,459 |
| Average Order Value |  74.7K |

> Values are based on the synthetic portfolio dataset included in the project.

---

## Excel Skills Demonstrated

This project demonstrates practical Excel skills including:

* Data cleaning and preparation
* Excel Tables
* `SUMIF` / `SUMIFS`
* `COUNTIF` / `COUNTIFS`
* `AVERAGE` / `AVERAGEIFS`
* `IF` and `IFERROR`
* Lookup and reference techniques
* Date-based analysis
* KPI calculations
* Profit and margin calculations
* Category and geographic analysis
* Product performance analysis
* Salesperson performance analysis
* Conditional formatting
* Charts and data visualization
* Dashboard design
* Data-quality validation

---

## Workbook Structure

The workbook is organized into dedicated layers to keep the analysis transparent and easy to follow.

| Section          | Purpose                                                    |
| ---------------- | ---------------------------------------------------------- |
| Project Overview | Introduces the project and analytical objectives           |
| Raw Data         | Original transaction-level dataset                         |
| Clean Data       | Standardized dataset used for analysis                     |
| Calculations     | Core KPI and supporting calculations                       |
| Analysis         | Category, country, product, salesperson and trend analysis |
| Dashboard        | Executive-level visual summary                             |
| Insights         | Key observations and recommendations                       |


This structure separates the source data, analytical logic, and final presentation.

---

## Data Cleaning

Before conducting the analysis, the dataset was checked for common data-quality problems.

Cleaning activities included:

* Standardizing category names
* Removing unnecessary spaces
* Checking missing values
* Reviewing transaction identifiers
* Validating numeric fields
* Checking date consistency
* Verifying calculated sales and profit values
* Reviewing category and geographic consistency

---

## Analysis Performed

### Product & Category Analysis

Revenue and profit were compared across product categories to determine which areas contribute most strongly to overall business performance.

The analysis also examines individual products to identify high-performing and potentially lower-margin items.

### Geographic Analysis

Sales and profitability were analyzed across markets including:

* Kenya
* Uganda
* Tanzania
* Rwanda

This provides management with a clearer picture of where revenue and profit are being generated geographically.

### Sales Performance

Salesperson performance was evaluated to identify differences in revenue and profit contribution across the sales team.

### Time-Series Analysis

Transaction dates were used to evaluate performance over time and identify changes in sales and profitability.

---

## Key Insights

Several observations emerge from the analysis:

**1. Electronics dominates revenue**

Electronics generates approximately **141.1M in revenue**, making it the largest category by a significant margin.

**2. Revenue leadership does not necessarily mean margin leadership**

Electronics produces substantial absolute profit but has a margin of approximately **13.4%**, below several other categories.

**3. Office Supplies achieves a stronger margin**

Although Office Supplies represents a relatively small share of total revenue, its margin is approximately **33.3%**, highlighting the importance of evaluating profitability alongside sales volume.

**4. Kenya is the largest market**

Kenya generates approximately **91.4M in revenue** and **17.0M in profit**, making it the strongest geographic market in the dataset.

**5. Overall profitability remains positive**

The business generates approximately **40.5M in profit** from **224.2M in revenue**, producing an overall profit margin of approximately **18.1%**.

---

## Business Recommendations

Based on the analysis, management could:

* Investigate opportunities to improve margins within the Electronics category.
* Protect and potentially expand high-margin product lines.
* Study the drivers behind Kenya's stronger market performance and determine whether they can be replicated elsewhere.
* Monitor discounting to understand its impact on profitability.
* Evaluate individual products using both revenue and margin rather than revenue alone.
* Continue tracking monthly performance to identify emerging growth or decline earlier.

---

## Dashboard

The final Excel dashboard provides an executive view of:

* Revenue
* Profit
* Profit margin
* Number of orders
* Units sold
* Average order value
* Category performance
* Geographic performance
* Sales trends
* Product and salesperson performance

### Dashboard Preview

![Sales Performance Dashboard](screenshots/dashboard.png)

---

## 📂 Repository Structure

```text
excel-sales-performance-dashboard/
│
├── README.md
│
├── Excel_Sales_Analytics_Portfolio_Complete.xlsx
│
├── data/
│   └── sales_data.csv
│
└── screenshots/
    └── dashboard.png
```

---

## Dataset

The project uses a **synthetic sales dataset created for portfolio and analytical practice purposes**.

The dataset contains 3,000 transaction records covering customers, locations, products, quantities, prices, discounts, revenue, costs, profit, payment methods, and customer segments.

Using synthetic data allows the project to demonstrate realistic business analysis without exposing confidential company or customer information.

---

## 🚀 Future Improvements

Potential future enhancements include:

* Power Query-based automated data preparation
* Power Pivot data modeling
* DAX measures
* Year-over-year performance analysis
* Customer segmentation
* Discount sensitivity analysis
* Automated refresh workflows
* Integration with Power BI

---

## About This Project

This project forms part of my **data analytics portfolio** and demonstrates how I use Excel to transform transactional data into structured analysis, dashboards, and actionable business insights.

**Tools:** Microsoft Excel
**Focus:** Data Cleaning | Data Analysis | KPI Reporting | Dashboard Design | Business Insights
