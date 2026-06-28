Sales Performance Executive Dashboard

## Business Problem Summary

The objective of this project is to develop an interactive Tableau dashboard that enables business leaders to monitor sales performance, profitability, customer behaviour, product performance, regional sales, discounts, and returns. The dashboard supports data-driven decision-making by presenting key business metrics in a clear and interactive format.

## Dataset Description

The dataset contains approximately 4,200 sales transactions with the following information:

- Order ID
- Order Date
- Ship Date
- Customer ID
- Customer Segment
- Region
- State
- City
- Category
- Sub-Category
- Product Name
- Ship Mode
- Sales
- Quantity
- Discount
- Profit
- Return Flag
- Delivery Days
- Customer Rating
- Campaign Channel

## Tableau Workbook Description

The Tableau workbook (`tableau/executive_dashboard.twbx`) contains an executive dashboard with KPI cards, interactive charts, filters, and dashboard actions for business analysis.

## Calculated Fields Created
- Profit Margin = Profit / Sales
- Cost = Sales − Profit
- Average Order Value = Sales / Distinct Orders
- Return Rate = Returned Orders / Total Orders
- Shipping Delay Bucket = Delivery Days categorized into Fast, Normal, and Delayed

## Dashboard Components
- KPI Cards
  - Total Sales
  - Total Profit
  - Profit Margin
  - Total Cost

- Charts
  - Sales Trend
  - Regional Performance
  - Category Profitability
  - Customer Segment
  - Discount vs Profit
  - Return Analysis

## Filters and Dashboard Interactions
Interactive Filters:
- Region
- Category
- Customer Segment
- Ship Mode
- Campaign Channel
- Order Date

Dashboard Action:
- Selecting a region filters all visualizations.

## Key Business Insights
- Total Sales: 217.0M
- Total Profit: 33.3M
- Profit Margin: 15.35%
- South region generated the highest sales.
- Technology is the highest-profit category.
- Home Office customers contribute the highest sales.
- Furniture has the highest return rate.
- High discounts do not consistently improve profitability.

## Dashboard Story Summary
The dashboard shows stable sales performance throughout the year, identifies Technology as the primary profit driver, highlights the South region as the strongest market, and identifies Furniture returns and discount management as major improvement opportunities.

## Assumptions and Limitations

### Assumptions
- Return Flag values of 1 indicate returned orders.
- Delivery Days accurately represent shipping duration.
- Sales and Profit values are correctly recorded.

### Limitations
- Historical dataset only.
- No forecasting included.
- External market conditions are excluded.
- Customer demographics are limited.

## Screenshots Included
- full_dashboard.png
- sales_trend_view.png
- regional_performance_view.png
- category_profitability_view.png
- filter_interaction_view.png
