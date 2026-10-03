Tata Motors Vehicle Sales and Profitability Analysis Dashboard Using Tableau

Project Overview

This project focuses on analysing Tata Motors vehicle sales data using Tableau. An interactive dashboard is developed to understand revenue, estimated profit, vehicle-type performance, regional sales and monthly sales trends.

Objectives

* Analyse overall vehicle sales and revenue performance.
* Understand estimated profit and profit ratio.
* Compare revenue across different vehicle types and regions.
* Identify the top 10 vehicle models based on revenue.
* Explore sales patterns using interactive visualizations, segmentation and clustering.

 Dataset Details
Dataset Name: Tata Vehicle Sales Dataset
Source: [GitHub Dataset Repository](https://github.com/Abhishek6290/Tata-Vehicle-Sales-Dashboard)
Records: Approximately 800
Format: CSV

Important Fields

 Vehicle Model
 Vehicle Type
 Region
 Sales Date
 Sales Quantity
 Revenue
 Profit Margin (%)
 Production Quantity
 Inventory Levels


 Tools and Technologies

Tableau Desktop
CSV Dataset
Data Visualization
Interactive Dashboarding

Dashboard Features

* KPI Cards – Total Revenue, Estimated Profit, Total Units Sold and Profit Ratio.
* Monthly Sales Trend – Displays revenue trends over time.
* Sales by Vehicle Type – Compares revenue across vehicle types.
* Sales Performance by Region – Shows regional revenue comparisons.
* Top 10 Vehicle Models – Displays the highest-revenue vehicle models.
* Vehicle Model Revenue Segmentation – Highlights revenue across vehicle types and models.
* Vehicle Clustering – Groups vehicle models based on revenue and profit margin.
* Interactive Filters – Year, Vehicle Type and Region.

Calculated Fields

**Total Revenue**

```text
SUM([Revenue])
```

**Estimated Profit**

```text
SUM([Revenue] * [Profit Margin (%)] / 100)
```

**Profit Ratio**

```text
SUM([Revenue] * [Profit Margin (%)] / 100) / SUM([Revenue])
```

**Average Sales**

```text
AVG([Revenue])
```

## Key Insights

1. The dashboard displays total revenue of ₹172,660,277,052.
2. SUV is the highest-revenue vehicle type, contributing approximately ₹109.17 billion.
3. North India recorded the highest regional revenue of ₹59,581,968,515.
4. Tata Safari generated the highest revenue among the displayed vehicle models, with ₹35,797,484,757.
5. The estimated profit is ₹23,942,013,815.70, with an overall profit ratio of 13.87%.

## Project Files

The repository contains:

* Tableau Workbook (.twbx)
* Dataset (.csv)
* Dashboard Screenshot
* README.md

## Conclusion

This project demonstrates how Tableau can transform raw vehicle sales data into meaningful visual insights. The interactive dashboard helps users explore revenue, estimated profitability, vehicle-type performance, regional sales and vehicle model trends.

**Developed by:** Prerna Yesudas Rakte
**Class:** TY BSc IT – Semester V
**Academic Year:** 2026–2027
**Subject:** Data Visualization with Power BI and Tableau
