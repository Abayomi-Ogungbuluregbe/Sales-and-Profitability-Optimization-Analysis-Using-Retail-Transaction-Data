# 📊 Sales and Profitability Optimization Analysis Using Retail Transaction Data

---

## 📌 Project Overview

Retail organizations generate large volumes of transactional data daily, yet many struggle to convert this data into actionable business insights.  
This project applies **exploratory data analysis, statistical testing, and predictive modeling** to retail transaction data in order to identify **sales drivers, revenue patterns, and profitability optimization opportunities**.

Using **Excel for statistical analysis** and **Power BI for visualization**, the project answers five structured business questions that progress from **descriptive insights** to **diagnostic and predictive analytics**. The goal is to support **data-driven decision-making** related to pricing, inventory planning, customer behavior, and revenue optimization.

This project is designed as a **portfolio-ready case study** suitable for:
- Data Analyst roles  
- Business Intelligence roles  
- Entry-to-mid level Analytics positions  
- Remote international opportunities  

---

## 🎯 Business Objectives

The project aims to:
- Evaluate overall sales performance across product categories  
- Understand how sales accumulate and change over time  
- Statistically test whether product categories differ in customer spending behavior  
- Identify the most significant drivers of customer purchase amount  
- Analyze monthly sales trends and seasonality patterns  

---

## 🧰 Tools & Technologies

### Data Analysis
- **Microsoft Excel**
  - Data cleaning & transformation
  - Pivot Tables
  - Data Analysis ToolPak (ANOVA & Regression)

### Visualization
- **Power BI**
  - Column Charts
  - Area Charts
  - Line Charts
  - Scatter Plots with Trendlines

### Statistical Techniques
- Exploratory Data Analysis (EDA)
- One-Way ANOVA
- Multiple Linear Regression

---

## 📂 Dataset Description

- **Total Transactions:** 1,000  
- **Time Period:** 2023 – Early 2024  
- **Key Variables:**
  - Sales Amount
  - Quantity Purchased
  - Price per Unit
  - Product Category (Electronics, Clothing, Beauty)
  - Customer Age
  - Gender Classification
  - Transaction Date

---

## 🧠 Business Questions, Methods & Tools

| BQ | Business Question | Tools / Methods |
|----|------------------|-----------------|
| **BQ1** | What is the overall sales performance by product category? | Pivot Table, Column Chart |
| **BQ2** | How does cumulative sales evolve over time? | Pivot Table, Area Chart |
| **BQ3** | Do product categories significantly differ in average purchase amount? | One-Way ANOVA |
| **BQ4** | Which factors significantly influence customer purchase amount? | Multiple Linear Regression |
| **BQ5** | What are the monthly sales trends and seasonality patterns? | Pivot Table, Line Chart |

---

## 📊 BQ1: Overall Sales Performance by Product Category

### Tools Used
- Excel Pivot Table  
- Power BI Column Chart  

### Analytical Approach
Total sales were aggregated by product category to understand revenue contribution across Electronics, Clothing, and Beauty.

### Interpretation
- Electronics, Clothing, and Beauty generate **similar levels of total revenue**.
- No single product category overwhelmingly dominates sales.

### Business Implications
- Revenue diversification reduces dependency risk.
- Management should avoid over-investing in one category while neglecting others.
- Profitability improvements should focus on **pricing, volume, and operational efficiency** rather than category expansion alone.

### Conclusion
Sales performance is **balanced across product categories**, suggesting a stable product mix.

---

## 📈 BQ2: Cumulative Sales Over Time

### Tools Used
- Excel Pivot Table  
- Power BI Area Chart  

### Analytical Approach
Sales were accumulated chronologically to visualize growth patterns and revenue momentum over time.

### Interpretation
- Sales increase steadily with periods of accelerated growth.
- Growth is not linear, indicating fluctuations driven by demand cycles.

### Business Implications
- Helps management monitor revenue momentum.
- Useful for tracking performance against targets.
- Identifies periods requiring promotional intervention.

### Conclusion
The business demonstrates **consistent revenue growth**, with identifiable fluctuations that warrant deeper seasonal analysis.

---

## 🔬 BQ3: Do Product Categories Differ in Average Purchase Amount?

### Statistical Method
- **One-Way ANOVA (Single Factor)**

### Step-by-Step ANOVA Procedure
1. Group transaction-level sales by product category.
2. Calculate group means and variances.
3. Compute:
   - Between-group variability
   - Within-group variability
4. Compare F-statistic and p-value at α = 0.05.

---

### ANOVA Summary Statistics

| Category | Count | Average ($) | Variance |
|--------|------:|------------:|---------:|
| Electronics | 342 | 458.79 | 322,101.82 |
| Clothing | 351 | 443.25 | 303,265.99 |
| Beauty | 307 | 467.48 | 317,659.37 |

---

### ANOVA Table

| Source | SS | df | MS | F | P-value |
|------|-----------:|----:|-----------:|--------:|---------:|
| Between Groups | 100,162.58 | 2 | 50,081.29 | 0.1594 | **0.8527** |
| Within Groups | 313,183,587.40 | 997 | 314,125.97 | | |
| Total | 313,283,750.00 | 999 | | | |

---

### Interpretation
- **P-value = 0.8527 > 0.05**
- No statistically significant difference exists between category means.

### Business Implications
- Customers spend similar amounts regardless of product category.
- Category-based pricing or promotion strategies alone are unlikely to increase transaction value.

### Conclusion
Product category **does not significantly influence average purchase amount**.

---

## 📉 BQ4: Which Factors Significantly Influence Customer Purchase Amount?

### Statistical Method
- **Multiple Linear Regression**

### Step-by-Step Regression Procedure
1. Define dependent variable: **Sales Amount**
2. Select predictors:
   - Quantity
   - Price per Unit
   - Age
   - Gender Classification
3. Run regression using Excel ToolPak.
4. Evaluate:
   - R² and Adjusted R²
   - Overall model significance
   - Individual predictor significance

---

### Regression Statistics

| Metric | Value |
|------|------:|
| R Square | **0.855** |
| Adjusted R Square | **0.854** |
| Observations | 1,000 |

---

### Regression Coefficients & Significance

| Variable | Coefficient | P-value | Significance |
|--------|------------:|--------:|-------------|
| Quantity | 177.35 | 2.84E-139 | ✅ Significant |
| Price per Unit | 2.49 | 0.0000 | ✅ Significant |
| Age | -0.80 | 0.1048 | ❌ Not Significant |
| Gender | 11.10 | 0.4118 | ❌ Not Significant |

---

### Interpretation
- The model explains **85.5% of sales variation**, indicating excellent predictive power.
- Quantity and Price per Unit are the **primary drivers of revenue**.
- Demographic variables have minimal impact.

### Business Implications
- Revenue growth strategies should prioritize:
  - Upselling quantities
  - Optimizing pricing
- Customer demographics should not be heavily relied upon for sales forecasting.

### Conclusion
Sales are **transaction-driven rather than demographic-driven**.

---

## 📅 BQ5: Monthly Sales Trends & Seasonality

### Tools Used
- Excel Pivot Table  
- Power BI Line Chart  

### Interpretation
- Monthly sales fluctuate with identifiable peaks and dips.
- Certain months consistently outperform others.

### Business Implications
- Enables better inventory planning.
- Supports targeted seasonal promotions.
- Improves staffing and cash-flow forecasting.

### Conclusion
Sales exhibit **clear seasonal patterns** that can be leveraged for profitability optimization.

---

## 🧾 Overall Key Insights
- Product categories contribute evenly to revenue.
- Sales growth is steady but seasonally influenced.
- Quantity and pricing are the strongest revenue drivers.
- Demographics play a minimal role in purchase amount.

---

## ⚠️ Limitations
- Single-year dataset
- No discount or promotion variables
- No customer lifetime value tracking

---

## 🚀 Future Enhancements
- Customer segmentation
- Predictive demand modelling
- Promotion effectiveness analysis
- Automated Power BI dashboards

---

📢 I am actively seeking **remote data analyst and business intelligence opportunities** where I can apply statistical analysis, business reasoning, and data storytelling to solve real-world problems.

📩 **Let’s connect and collaborate via abayomiogungbuluregbe@gmail.com**
