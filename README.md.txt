# Global Sales & Profitability Analysis — Power BI

## 📊 Project Overview

This project focuses on analyzing global sales data for 2013–2014 using Microsoft Power BI. The objective was to transform raw sales data into an interactive business intelligence dashboard covering sales performance, profitability, customer segments, product performance, country-wise sales, and discount patterns.

The dataset contains 700 records and 16 fields, including sales, profit, cost, units sold, product, country, segment, discount band, and date-related information.

## 🎯 Project Objectives

- Analyze overall sales and profitability
- Compare sales performance between 2013 and 2014
- Analyze country-wise sales performance
- Understand customer segment performance
- Identify top and low-performing products
- Analyze the relationship between sales and profit
- Examine sales and profit across discount bands
- Build an interactive Power BI dashboard

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Microsoft Excel

## 🧹 Data Preparation

Power Query was used to prepare the raw dataset before dashboard development.

Key steps included:

- Cleaning and standardizing column names
- Checking and correcting data types
- Handling missing values in the Discount Band field
- Replacing missing discount categories with "No Discount"
- Checking data quality
- Creating a dedicated Date table
- Establishing a relationship between the Date table and Sales Data table

## 📐 Data Model

A dedicated Date table was created using DAX to support time-based analysis.

The Date table contains:

- Date
- Year
- Month Number
- Month
- Month Short
- Quarter

The Date table was connected to the Sales Data table using the Date field with a one-to-many relationship.

## 📌 Key DAX Measures

The project includes DAX measures for:

- Total Sales
- Total Profit
- Total COGS
- Total Units Sold
- Profit Margin %
- Average Sale Price
- Total Discount
- Total Gross Sales
- Sales LY
- Sales Growth %
- Profit LY
- Profit Growth %
- YTD Sales
- YTD Profit

## 📊 Dashboard Pages

### 1. Introduction

Provides an overview of the project, objectives, dataset, tools, and areas of analysis.

### 2. Executive Overview

Provides a high-level view of business performance, including:

- Total Sales
- Total Profit
- Total Units Sold
- Profit Margin
- Monthly Sales Trend
- Sales by Country
- Sales by Segment
- Profit by Segment
- Interactive Year, Country, and Segment filters

### 3. Product Performance

Focuses on product-level and discount analysis, including:

- Top 10 Products by Sales
- Top 10 Products by Profit
- Bottom 3 Products by Profit
- Sales vs Profit by Product
- Sales by Discount Band
- Profit by Discount Band
- Interactive Year and Discount Band filters

### 4. Conclusion

Summarizes the analysis and the practical business value of the dashboard.

## 📈 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Sales | 118.73M |
| Total Profit | 16.89M |
| Profit Margin | 14.23% |
| Analysis Period | 2013–2014 |
| Records | 700 |

## 🔍 Analysis Areas

The dashboard enables users to explore:

- Sales trends over time
- Country-wise sales performance
- Customer segment performance
- Product sales and profitability
- Discount performance
- Sales versus profit
- Year-over-year sales performance

## 💡 Business Use

The dashboard can help users identify:

- High-performing countries and customer segments
- Products generating higher sales and profit
- Products with comparatively lower profitability
- Changes in performance between years
- Sales and profit patterns across discount bands
- Relationships between sales volume and profitability

## 📂 Project Structure

```text
Global-Sales-Profitability-PowerBI/
│
├── README.md
├── Global_Sales_Profitability_Analysis.pbix
│
├── Dataset/
│   └── Superstore.xlsx
│
├── Screenshots/
│   ├── Introduction.png
│   ├── Executive_Overview.png
│   ├── Product_Performance.png
│   └── Conclusion.png
│
└── DAX/
    └── Measures.md
```

## 👨‍💻 Skills Demonstrated

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization
- KPI Development
- Business Analysis
- Interactive Dashboard Design

## 📝 Conclusion

This project demonstrates how Power BI can transform raw sales data into an interactive business intelligence solution.

It showcases practical experience in data cleaning, transformation, data modeling, DAX calculations, dashboard development, visualization, KPI analysis, and business-oriented reporting.
