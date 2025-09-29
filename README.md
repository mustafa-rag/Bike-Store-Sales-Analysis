# Bike Store Sales Analysis
## Project Background
The bike store operates in a competitive retail environment in six different countries where customer preferences, seasonal demand, and product profitability directly affect business performance. With a wide range of products — including bicycles, accessories, Clothing and maintenance items — the management team needed a clearer understanding of:

- Which products and categories drive the most sales and profit.  
- How customer demographics influence purchasing behavior.  
- Which geographic markets are most profitable.  
- How seasonality impacts demand and revenue.

Excel file (dataset, cleaning process, pivot tables) available here.

Interactive PowerBI dashboard available here.
## Data Structure
The dataset contained one table with 113,036 records of customer orders, including:

- Order details (date, product name, quantity, unit price, unit cost).  
- Financial metrics (revenue, cost, profit, profit margin, markup).  
- Customer demographics (age, age group, gender).  
- Geographic data (country, state).  
- Product attributes (product category, product sub-category).
## Methodology
#### Data Cleaning (Excel):
- Removed duplicates and standardized formats and column names.
- Created calculated fields: Profit Margin %, Markup %.
- Grouped customers into new age brackets: G1 (<25), G2 (25–34), G3 (35–50), G4 (50+).

#### Exploratory Analysis (Excel PivotTables):
- Initial pivot tables to understand sales by category, region, and demographics.
- Charts to identify seasonal and geographic trends.

#### Interactive Dashboard (Power BI):
- KPIs: Total Revenue, Total Profit, Profit Margin %, Orders Count, Average Order Value, Unit Sold.
- Visuals: sales trends, top products, demographic and geographic insights.
- Slicers for dynamic filtering by date, country, gender, age group, and products.
## Executive Summary
## Key Findings
#### Sales & Revenue Trends:
- Total **Revenue: $84.8M**, Total **Profit: $32.0M**.
- Sales show strong seasonality, peaking in December.
#### Product Performance:
- Top Categories by Revenue: Bikes (72.4%), Accessories (17.7%), Clothing (9.9%).
- Top Categories by Profit Margin: Accessories (58.6%), Clothing (33.9%), Bikes (33.2%).
#### Customer Demographics:
- G2 (25–34) and G3 (35–50) age groups contribute 75.8% of revenue and have the highest average order value.
- G4 (50+) age group has lowest revenue, but highest profit margin (40.2%).
#### Geographic Insights:
- Top Countries by Revenue: United States (32.8%) and Australia (25.0%).
- Top Countries by Profit Margin: Canada (46.8%) and United Kingdom (41.5%).
- Australia generates high sales but suffers from lower margins (31.8%) due to higher costs or high competition.
#### Profitability Analysis:
- Accessories are the highest-margin category, ideal for upselling.
- Some high-volume products underperform in margins may be this is pricing issue.
## Recommendations
- **Seasonality:** Increase inventory and targeted marketing before December to maximize sales.
- **Product Bundling:** Upsell high-margin accessories (58.6% margin) with bike sales.
- **Pricing Strategy:** Re-evaluate pricing/supplier contracts for low-margin but high-sales products.
- **Customer Targeting:** Focus digital campaigns on 25–50 age group with premium offerings.
- **Geographic Optimization:**
  - Invest in high-margin markets (Canada, UK).
  - Address cost challenges in Australia to lift margins.
