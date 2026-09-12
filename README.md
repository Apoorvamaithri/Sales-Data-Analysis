# Sales Dashboard

An interactive Power BI dashboard for tracking global sales performance, profitability, and customer purchasing behavior across countries, store locations, product categories, and payment methods.

## Overview

This dashboard provides a 360° view of sales operations, enabling stakeholders to monitor key performance metrics, identify seasonal trends, and analyze the relationship between discounts and profitability.

## Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Sales | 4.14M |
| Total Profit | 959.35K |
| Total Orders | 3K |
| Total Discount | 76.69K |
| Average Orders | 1.38K |

## Filters / Slicers

- **Country** — Canada, China, India, Nigeria, UK, US
- **Store Location**
- **Category**
- **Payment Method** — Mobile Payment, Credit Card, Cash
- **Date Range** — 1/1/2025 to 12/31/2025

## Visualizations

1. **Total Sales by Month Name** — Line chart tracking monthly sales trends, highlighting peak (December, 524K) and low (June, 241K) periods across the year.
2. **Discounts Given vs Profit** — Scatter plot comparing total discounts against total profit, segmented by country, to assess whether discounting strategies are eroding profitability.
3. **Total Sales by Day** — Bar chart showing sales distribution across days of the week, identifying strongest (Sunday, Monday) and weakest (Tuesday) sales days.
4. **Count of Payment Method** — Pie chart showing an even split of transactions across Mobile Payment (34.28%), Cash (32.88%), and Credit Card (32.84%).
5. **Total Sales by Category** — Horizontal bar chart ranking product categories (Home & Kitchen, Clothing, Electronics, Sports, Beauty, Toys) by sales contribution.

## Data Preparation & Modeling

- **Cleaned and prepared data** using Excel and SQL — identifying and removing duplicate records, handling null values, and engineering calculated columns to ensure data accuracy for downstream analysis.
- **Designed DAX measures** in Power BI for core KPIs (Total Sales, Total Orders, Total Profit, Total Discounts, Average Order Value), enabling real-time performance tracking across the dashboard.

## Key Insights

- **Seasonality**: Sales peak in December and dip mid-year (April–June), suggesting strong seasonal/holiday-driven demand.
- **Balanced payment adoption**: No single payment method dominates — usage is nearly evenly split across Mobile Payment, Cash, and Credit Card.
- **Category performance**: Home & Kitchen leads sales, but the gap between the top 6 categories is narrow, indicating a diversified product mix rather than reliance on one category.
- **Discount efficiency**: The discount-vs-profit scatter plot helps flag countries where higher discounting isn't translating into proportionally higher profit.

## Tools Used

- **Power BI** — Data modeling, DAX measures, and dashboard visualization
- **SQL**  — Cleaned and prepared data using Excel and SQL — identifying and removing duplicate records, handling null                    values, and engineering calculated columns to ensure data accuracy for downstream analysis.

## How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the slicers at the top (Country, Store Location, Category, Payment Method, Date) to filter the dashboard to a specific segment or time period.
3. Hover over any chart for detailed tooltips.

## File Structure

```
├──README.md                # Project documentation
├── SQL queries for sales data analysis.docx #sql queries
├──Sales_Analysis _Dashboard.png    #power BI report screenshot
├──sales Analysis PowerBI report.pbix    # Power BI dashboard file
├── sales_Canada.csv
├──sales_China.csv
├──sales_India.csv
├──sales_Nigeria.csv
├──sales_UK.csv
├──sales_US.csv                   # Source data
└──
```
