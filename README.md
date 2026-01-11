# Adventure-Works-Excel-Dashboard-Project

## 📌 Project Overview

This project showcases an **end-to-end data analytics solution built entirely using Microsoft Excel**, based on the **Adventure Works dataset**.
The objective was to transform **raw transactional sales data** into **interactive, enterprise-style dashboards** using **Excel-based ETL, fact–dimension data modeling, and Pivot-driven analytics**, without relying on BI tools such as Power BI or Tableau.

The project closely follows **real-world BI principles**, including star schema modeling, KPI-driven reporting, and business storytelling.

---

## 🎯 Business Objectives

* Analyze overall **sales and profit performance**
* Identify **top-performing products and categories**
* Understand **customer demographics and regional trends**
* Enable **dynamic, filter-driven decision-making** using Excel dashboards

---

## 🗂️ Dataset Description

### Fact Tables

* **FactInternetSales**
* **Fact_Internet_Sales_New**

These tables contain transactional-level data such as:

* Sales Amount
* Order Quantity
* Product Key
* Customer Key
* Order Date
* Cost and Revenue details

### Dimension Tables

* **DimCustomer** – customer demographics (occupation, education, region)
* **DimProduct** – product-level attributes
* **DimProductCategory**
* **DimProductSubCategory**
* **DimDate** – calendar hierarchy (Year, Quarter, Month)
* **DimSalesTerritory** – regional mapping

---

## 🔄 ETL PROCESS (Extract – Transform – Load) IN EXCEL

### 1️⃣ Extract

* Imported multiple **fact and dimension Excel files**
* Maintained raw data separately to preserve source integrity

### 2️⃣ Transform

Performed all transformations using **Excel-native tools and formulas**:

* **Union of fact tables**

  * Combined `FactInternetSales` and `Fact_Internet_Sales_New` into a single consolidated sales table
* **Data Cleaning**

  * Removed duplicate records
  * Handled missing or inconsistent values
  * Standardized numeric and date formats
* **Derived Columns**

  * Year, Quarter, Month (from Date)
  * Profit = Sales – Cost
  * Profit Margin = Profit / Sales
* **Key Standardization**

  * Ensured consistency of ProductKey, CustomerKey, DateKey across tables

### 3️⃣ Load

* Prepared clean, structured datasets for modeling and reporting
* Loaded transformed data into PivotTables for dashboard creation

---

## 🧩 DATA MODELING APPROACH (FACT–DIMENSION DESIGN)

Although Excel does not enforce physical relationships like BI tools, a **logical star schema** was implemented.

### Star Schema Design

* **Central Fact Table:** Internet Sales
* **Connected Dimensions:**

  * Date
  * Product
  * Product Category & Subcategory
  * Customer
  * Sales Territory

### Modeling Techniques Used

* Lookup functions:

  * `VLOOKUP`
* Mapped descriptive attributes (product name, category, customer info) into the fact table
* Maintained **one-to-many logical relationships**

### Benefits of This Approach

* Accurate aggregations
* Reliable slicer filtering
* Scalable structure for additional dimensions or KPIs

---

## 📈 DASHBOARD 1: SALES OVERVIEW

### Objective

Provide a **high-level executive view** of overall business performance.

### KPIs

* Total Sales
* Total Profit
* Customer Count
* Profit Margin %

### Visuals

* **Year vs Total Sales** – trend analysis over time
* **Quarter vs Sales** – seasonality insights
* **Month vs Sales** – monthly demand patterns
* **Sales vs Profit** – revenue vs profitability alignment

### Business Value

Helps stakeholders quickly assess growth patterns and performance health.

---

## 🛒 DASHBOARD 2: PRODUCT PERFORMANCE

### Objective

Analyze product-level contribution and profitability.

### Visuals

* Top 10 Sub-Categories by Sales
* Category-wise Sales Distribution
* Top 10 Products by Revenue
* Sub-Category Sales vs Profit comparison

### Key Insights

* Road Bikes are the highest revenue and profit contributors
* Some products generate high sales but lower margins
* Enables identification of pricing and cost-optimization opportunities

---

## 🌍 DASHBOARD 3: CUSTOMER & REGION ANALYSIS

### Objective

Understand customer behavior and regional sales patterns.

### Visuals

* Region-wise Sales
* Occupation-wise Sales
* Education-wise Sales
* Top 15 Customers by Sales

### Key Insights

* Certain regions significantly outperform others
* Professional and skilled manual occupations contribute the most revenue
* Education level influences purchasing behavior
* Identifies high-value customers for retention strategies

---

## 🎛️ INTERACTIVITY & DASHBOARD FEATURES

* Excel **Slicers** for:

  * Year
  * Month
  * Region
* Dynamic KPI cards
* Cross-filtering across all charts
* Clean, executive-friendly dashboard layout

All dashboards are built using:

* PivotTables
* PivotCharts
* Slicers & Timelines

---

## 🧠 KEY LEARNINGS

* Practical Excel-based ETL workflows
* Real-world application of fact–dimension modeling concepts
* Advanced PivotTable analytics
* Translating data into actionable business insights
* Designing dashboards for executive decision-making

---

## 🛠️ TOOLS & TECHNOLOGIES USED

* Microsoft Excel
* PivotTables & PivotCharts
* Slicers & Timelines
* Excel formulas:

  * VLOOKUP
  * IF
  * SUMIFS

---

# Screenshots / Demos

![Dashboard View](https://github.com/Keerthana-duraipandian/Adventure-Works-Excel-Dashboard-Project/blob/main/Sales.jpeg)

![Dashboard View](https://github.com/Keerthana-duraipandian/Adventure-Works-Excel-Dashboard-Project/blob/main/Product.jpeg)

![Dashboard View](https://github.com/Keerthana-duraipandian/Adventure-Works-Excel-Dashboard-Project/blob/main/Customer.jpeg)

---

## 🚀 Conclusion

This project demonstrates how **Excel alone can be used to build enterprise-style BI dashboards**, following industry-standard data modeling and analytical practices.

It highlights my ability to:

* Handle structured datasets
* Design scalable analytics solutions
* Communicate insights effectively through dashboards

---

## 📬 Feedback & Opportunities

Feedback is welcome.
Open to **Data Analyst / MIS / Business Intelligence roles**.

---
