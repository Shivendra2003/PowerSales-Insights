# PowerSales-Insights

# Overview
This Power BI project provides comprehensive insights into sales data, enabling stakeholders to make informed decisions based on real-time analysis. The dashboard includes key performance indicators (KPIs), sales trends, and detailed analytics to track performance and identify opportunities for growth. This project aims to provide sales insights for Nintendo Hardware using Microsoft Power BI for data cleansing and visualization. Additionally, MySQL is utilized as the database to analyze the data effectively.

# Features
**Interactive Dashboards:**  Real-time interactive dashboards with visualizations for sales data.

**Sales KPIs**: Key Performance Indicators such as Total Sales, Sales Growth, and Average Order Value.

**Trend Analysis:** Analysis of sales trends over various periods (daily, weekly, monthly).

**Product Performance:** Insights into the best and worst-performing products.

**Customer Analysis:** Data on customer segments, purchase behavior, and retention rates.

**Revenue Forecasting:** Predictive analytics for future sales based on historical data.

# Requirements
Power BI Desktop.

Access to the sales data source (e.g., SQL Server, Excel, or other database systems)

MySql

# Getting Started
**Clone the repository:**
git clone https://github.com/yourusername/sales-insight-data-analysis.git

**Open the Power BI Desktop:**
Download and install Power BI Desktop.

**Load the Power BI file:**
Open the .pbix file included in the repository with Power BI Desktop.

**Connect to your data source:**
Update the data source settings to connect to your sales data.

# Usage
**Navigate through the dashboards:**
Use the navigation pane to switch between different dashboards and reports.

**Interact with the visuals:**
Click on charts and visuals to drill down into specific data points.

**Filter data:**
Use slicers and filters to customize the view according to your needs.


# Key Metrics and Queries
Total Transaction: To find out the total transactions of the company, use the following code in Microsoft Power BI: Total Transaction = COUNTROWS('sales transactions')

Revenue: To calculate the revenue of the company, use the following code in Microsoft Power BI: Revenue = SUM('sales transactions'[sales_amount])

Revenue in SQL (2020): To see the revenue of the company in SQL for the year 2020, execute the following SQL query: SELECT SUM(sales_amount) FROM transactions AS trns INNER JOIN date AS dt ON trns.order_date = dt.date WHERE dt.year = 2020

Distinctive Years in SQL: To view the distinctive years in SQL, use the following query: SELECT DISTINCT(year) FROM date


# Additional Notes
Ensure that the appropriate data sources are connected to your Power BI and MySQL environments for accurate analysis.

Customize the queries and calculations based on specific requirements and business objectives.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Screenshots
![Screenshot (240)](https://github.com/user-attachments/assets/d4f01847-ff2e-4a3b-acb9-2f596bb1ed0c)

