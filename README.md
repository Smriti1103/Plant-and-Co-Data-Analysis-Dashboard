# Plant-and-Co-Data-Analysis-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/462028da-0313-46cb-979c-191750c42162/ReportSection?experience=power-bi

## Problem Statement

Plant and Co, a plant distribution company, required a comprehensive analysis of their sales, product quantity, and gross profit across two years (2023 and 2024). The challenge was to clean, organize, and present the data in a way that enables stakeholders to easily compare year-over-year performance, analyze key metrics, and gain insights into regional performance.

### Snapshot of Dashboard
![image](https://github.com/user-attachments/assets/ac5692e1-3744-4574-b5fc-7551574e92c9)


### Steps followed 

- Data Preparation:

    Divided the dataset into three primary tables: plant data, account data, and the relationship between which accounts purchase which plants.
    Cleaned the data by removing duplicates and correcting data types to ensure consistency across the tables.
- Measure Creation:

    Created new measures for key business metrics, including:

    Sales,
    Quantity,
    Cost of Goods (COG),
    Gross Profit (calculated as Sales - COG),
    Further calculated Year-to-Date (YTD) and Previous Year-to-Date (PYTD) metrics for sales, quantity, and gross profit to allow comparative analysis.
- Visualization Design:

    Created a Treemap to visualize the country-wise distribution of sales and quantity across the different plants and accounts.
    Added slicers to filter data for
    Year selection (2023 or 2024).
- Metric selection 

    (Sales, Gross Profit, and Quantity) for focused analysis.
    Designed a Waterfall Chart to compare the monthly product quantities for the two years, making it easier to visualize fluctuations in quantity between 2023 and 2024.
- Data Comparison:

    Incorporated dynamic slicers for users to switch between YTD and PYTD metrics, providing stakeholders with the ability to track performance changes across time periods.
# Insights

- Regional Performance: The treemap visualization allowed clear insights into country-wise performance, highlighting which regions were driving the most sales and gross profit.

- Yearly Comparison: The YTD and PYTD calculations enabled direct comparison between the two years (2023 vs 2024), showing significant growth trends or declines across key metrics.

- Product Quantity Trends: The waterfall chart provided a clear month-wise breakdown of product quantities for the two years, revealing patterns in product demand fluctuations over time.

- Flexible Filtering: The slicers allowed stakeholders to quickly shift focus between sales, quantity, and gross profit, helping them understand specific areas of performance without having to reconfigure the entire dashboard.
