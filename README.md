# Bright-Coffee-Shop-Sales-Analysis
# Case Study Project

**Introduction**

As a Data Analyst, I have been requested to conduct a study on Bright Coffee Shop Sales, using their transactional data from January 2023 to June 2023. The dataset captures daily sales activity from a local coffee shop and serves as the basis for this case study. The business recently appointed a new CEO, whose strategic objective is to grow revenue and improve product performance. To support this initiative, a data-driven analysis is essential to reveal key patterns, trends, and opportunities within the sales data. My role is to extract actionable insights and present meaningful findings that will assist the CEO in making informed, evidence-based decisions.

**Purpose**

This case study shows how one can use data analytics to drive company growth. The goal of reviewing historical sales data is to identify important performance factors and possibilities for improvement in product sales and operational methods.

**Objective**

The goal of this case study is to use analytics, SQL, and data visualization tools to help Bright Coffee Shop collect significant insights into its operations. The analysis’s specific goal is to identify which products generate the most revenue, determine the most profitable times of day, reveal sales trends across various product categories and time intervals, perform other analyses that would support the practical, and data-driven recommendations to improve overall sales performance.

**Tools used**

**The following tools were used accordingly to achieve the goal:**

- Bright Coffee Shop Dataset – readily available transactional data served as the foundation for the analysis.

- Miro – used during the planning phase to create a mind map outlining the project execution steps.

- Microsoft Excel – used for data formatting, cleaning, and creating visualizations.

- Snowflake – used for transforming raw data into meaningful insights through SQL queries.

- Canva – used to design dashboards by incorporating graphs and charts exported from Excel.

- Microsoft PowerPoint – served as the final platform for compiling and presenting the project report.

**Data processing**

The data processing phase involved preparing and transforming the raw dataset into a structured format suitable for analysis. 

The following steps were taken:

**Date Formatting & File Conversion**

- The original dataset from Bright Coffee Shop was cleaned by changing the transaction_date format from YYYY/MM/DD to YYYY-MM-DD. 

- The dataset was then saved as a CSV file for ease of use across data tools.

**SQL-Based Data Transformation**

Using SQL in Snowflake, the following data transformations were applied:

***Data Type Correction:***

The unit_price values, initially stored with commas instead of decimal points, were corrected using the REPLACE() function and cast to FLOAT for numerical calculations.

***Revenue Calculation:***

The total amount spent per transaction was calculated by multiplying the cleaned unit_price with the transaction_qty, and then summed to compute total_amount.

***Aggregated Metrics:***

The dataset was enriched with key performance indicators such as:

- number_of_units_sold (sum of transaction quantities)
- number_of_transactions (count of transaction IDs)
- number_of_stores (count of distinct store IDs)
  
***Date Derivation:***

Functions were used to extract the day name and month name from transaction_date for time-based analysis.

***Time of Day Classification:***

A CASE statement was used to categorize transactions into time segments:

- Morning (06:00–11:59)
- Afternoon (12:00–16:59)
- Evening (17:00–19:59)
- Night (20:00–05:59)
  
***Spending Category Classification:***

Another CASE statement grouped customers into spending types based on their total spend:

- Low Spender (≤ R15)
- Medium Spender (R16–R99)
- High Spender (R100–R700)
- Very High Spender (> R700)
  
***Grouping for Aggregation:***

The final result set was grouped by product details, store location, day/time, and date fields to prepare for analysis and visualization.

The transformed data was then downloaded from Snowflake and saved as an Excel file.

**Data Analysis**

Data analysis was conducted in Excel, where Pivot Tables were created to summarize and explore the transformed dataset. These Pivot Tables enabled dynamic grouping and aggregation of key metrics such as total revenue, number of transactions, and units sold across various dimensions like product type, time of day, and month. Based on these inforamtion, then I have created charts and graphs to visually represent trends and patterns in the data, aligned with the key objectives of the case study. 

Graphs were then exported to CANVA to create dashboards which will be used in the final presentation document.

**Report or Presentation**

Presentation was prepared using MicroSoft Power Point and submitted to the relevant official.

**Conclusion**

The detailed analysis and findings of the study are highlighted in the presentation, showcasing key insights on the sales for different months across the three stores. Each section is supported by visualizations and data summaries to provide a clear understanding of the business’s current performance and to guide strategic recommendations aimed at improving revenue and operational efficiency.

***Thank you***
