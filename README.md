# Coffee Performance Report

## Overview
The **Coffee Performance Report** explores sales, quantity, and profitability across coffee types and products. 
It transforms raw transactions into actionable insights through data cleaning, analysis, and visualization.

---

## Project Title
**Coffee Performance Report**

---

## Steps Taken
1. **Data Collection**
   - Gathered raw transactional data from the provided Excel file.
   - Ensured that all relevant sheets (orders, products, customers) were identified for analysis.

2. **Data Cleaning & Preparation**
   - Converted order dates to a proper datetime format for time-based analysis.
   - Standardized product categories (coffee type, roast type, size).
   - Removed duplicates and checked for missing values in key fields such as sales, product ID, and quantity.
   - Created new calculated fields such as `Year` extracted from `Order Date` to enable year-over-year comparison.

3. **Exploratory Data Analysis (EDA)**
   - Aggregated data at multiple levels (by coffee type, by product, by year, and by country).
   - Calculated total sales, units sold, and revenue contributions of different categories.
   - Identified seasonality and high-performing product groups through trend analysis.

4. **Visualization**
   - Built bar charts to compare sales across coffee types.
   - Created a time series line chart for sales trends across years.
   - Developed horizontal bar charts to highlight the top 5 performing products by revenue.
   - Ensured visuals clearly presented business insights with labels, titles, and easy-to-read scales.

5. **Reporting**
   - Summarized findings into key insights that highlight business opportunities.
   - Organized results into a performance report that can be shared with stakeholders or integrated into a BI dashboard.
   - Ensured the analysis is reproducible by providing Python code and chart outputs.


---

## Tools Used
- **Excel** – data handling and source-of-truth file
- **Python (pandas, matplotlib)** – analysis and charting
- **(Optional) Power BI / Tableau** – interactive dashboards

---

## Key Insights
- **Total Sales:** $45,134.25
- **Units Sold:** 3,551
- **Top Coffee Types by Sales:** Excelsa, Liberica, Arabica, Robusta
- **Best Year:** 2021


