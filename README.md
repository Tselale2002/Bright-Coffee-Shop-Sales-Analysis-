#☕ Bright Coffee Shop Sales Analysis

##Case Study Project

**📌 Introduction**


As a Data Analyst, I was tasked with conducting a sales analysis for Bright Coffee Shop using transactional data from January to June 2023. The dataset captures daily sales activity and forms the basis of this case study. With the recent appointment of a new CEO focused on revenue growth and product performance, this data-driven analysis aims to uncover key patterns, trends, and opportunities. The objective is to extract actionable insights and deliver findings that support informed, evidence-based decision-making.

**🎯 Purpose**

This case study demonstrates how data analytics can be used to drive business growth. By reviewing historical sales data, the goal is to identify key performance factors and opportunities for improving product sales and operational strategies.

**🎯 Objective**

The primary objective is to apply analytics, SQL, and data visualization techniques to uncover meaningful insights about Bright Coffee Shop’s operations. Specifically, the analysis aims to:

-Identify top-performing products by revenue

-Determine the most profitable times of day

-Reveal sales trends across categories and time intervals

-Provide practical, data-driven recommendations to improve overall sales performance

**🛠️ Tools & Technologies Used**

**The following tools were used accordingly to achieve the goal:**

- Bright Coffee Shop Dataset – readily available transactional data served as the foundation for the analysis.
  
- Miro – used during the planning phase to create a mind map outlining the project execution steps.

- Microsoft Excel – used for data formatting, cleaning, and creating visualizations.

- Snowflake – used for transforming raw data into meaningful insights through SQL queries.

- Canva – used to design dashboards by incorporating graphs and charts exported from Excel.

- Microsoft PowerPoint – served as the final platform for compiling and presenting the project report.


**⚙️ Data Processing Workflow**

The data processing phase involved preparing and transforming the raw dataset into a structured format suitable for analysis. 

The following steps were taken:

**1. Data Formatting & Conversion**

Transaction dates reformatted from YYYY/MM/DD to YYYY-MM-DD

Saved cleaned data as a CSV file for cross-tool compatibility

**2. SQL-Based Transformation in Snowflake**

-Data Type Correction: Replaced commas in unit_price and cast to FLOAT

-Revenue Calculation: total_amount = unit_price * transaction_qty

**Aggregated Metrics: Added KPIs such as:**

-number_of_units_sold

-number_of_transactions

-number_of_stores

**Date Derivation:**

-Extracted day and month names from transaction_date

CASE statements were used to categorize the following:

**Time of Day Classification:**

- Morning (06:00–11:59)
- Afternoon (12:00–16:59)
- Evening (17:00–19:59)
- Night (20:00–05:59)

**Spending Category Classification:**

- Low Spender (≤ R15)
- Medium Spender (R16–R99)
- High Spender (R100–R700)
- Very High Spender (> R700)

**Grouping for Analysis:**

The final result set was grouped by product details, store location, day/time, and date fields to prepare for analysis and visualization.

The transformed data was then downloaded from Snowflake and saved as an Excel file.

**📊 Data Analysis**

Data analysis was conducted in Excel, where Pivot Tables were created to summarize and explore the transformed dataset. These Pivot Tables enabled dynamic grouping and aggregation of key metrics such as total revenue, number of transactions, and units sold across various dimensions like product type, time of day, and month. Based on these inforamtion, then I have created charts and graphs to visually represent trends and patterns in the data, aligned with the key objectives of the case study.

Visualizations (charts & graphs) were created based on these metrics and exported to Canva to design a presentation.

**📑 Final Report/Presentation**

The presentation, prepared in CANVA, compiles the analysis, insights, and strategic recommendations. It was submitted to the relevant official for review.

**🧾 Conclusion**

This project highlights how a structured, data-driven approach can reveal valuable insights into sales performance. The final deliverable provides clear visuals and summaries that inform strategic decisions to improve revenue and operational efficiency across Bright Coffee Shop’s branches.

Thank you for reviewing this case study. Feel free to explore the files and reach out for feedback or collaboration# Bright-Coffee-Shop-Sales-Analysis
