
# Mobile Manufacturer Transactional Data Analysis- SQL Project




## 📌 Project Overview
This SQL project analyzes a mobile manufacturing company's transactional system. The goal is to extract actionable business insights about sales, customers, models, and manufacturers by leveraging structured SQL queries. It demonstrates proficiency in advanced SQL concepts including joins, aggregations, filtering, date-based analysis, and data modeling.
## 📂 Dataset Description
The dataset follows a classic **star schema** design, consisting of multiple dimension tables and a central fact table:

### 📊 Fact Table:
- **FACT_TRANSACTIONS**
  : Stores all transactional data including sales quantity, total value, transaction date, customer ID, model ID, and location ID.

### 📋 Dimension Tables:
- **DIM_LOCATION**
  : Contains details about store locations, including city and country.

- **DIM_CUSTOMER**: Contains customer demographics such as gender, date of birth, and city.

- **DIM_DATE**
  : Date dimension providing detailed breakdowns for reporting — day, month, quarter, year.

- **DIM_MANUFACTURER**
  : Contains details about mobile manufacturers.

- **DIM_MODEL**: Contains mobile model details, including model name, manufacturer ID, and category.
## 🎯 Project Objectives
- Analyze total and average sales revenue by mobile model and manufacturer.
- Identify top-performing locations based on sales value.
- Evaluate store-wise and manufacturer-wise sales distribution.
- Perform customer segmentation based on transaction behavior.
- Identify seasonal sales patterns using date functions.
- Track loyal customer trends and high-value transactions.
- Use aggregate and analytical functions to derive business KPIs.
## 🛠️ Tools & Technologies
- SQL Server Management Studio (SSMS)
- SQL concepts (joins, aggregations, filtering, window functions, sub-queries)
## 📈 Key Analysis Performed
- Total revenue and quantity sold by manufacturer and model.
- Year-wise and month-wise sales trend reporting.
- Top locations by revenue.
- Customer demographics analysis by gender and city.
- Manufacturer-wise sales distribution.
- Highest-selling mobile models and their contributing revenue percentages.
- Loyalty analysis: identifying repeat high-value customers.
- Date range reporting for transaction history.
## 📊 Key Business Insights
- Specific manufacturers dominated sales revenue across multiple years.
- Certain mobile models consistently ranked highest in both units sold and revenue.
- Seasonal trends and year-on-year growth patterns were identified.
- High-value customers exhibited repeat purchase patterns worth targeting via loyalty programs.
- Sales were concentrated in select high-performing cities.
## 📌 Skills Demonstrated
- Advanced SQL Querying
- Data Aggregation & Filtering
- Star Schema Data Modeling
- KPI Calculation and Trend Analysis
- Joins, Subqueries, Window Functions
- Business Intelligence Reporting
## ▶️ How to Run the Project
1. Open SQL Server Management Studio (SSMS).
2. Ensure the DIM_LOCATION, DIM_CUSTOMER, DIM_DATE, DIM_MANUFACTURER, DIM_MODEL, and FACT_TRANSACTIONS tables are created and populated.
3. Copy the queries from the provided sql file.
4. Execute queries sequentially to reproduce the analysis and derive business insights.

## 📄 License
This project is created for academic and portfolio demonstration purposes.
## 📞 Contact
- Name: Abhinay Kumar
- LinkedIn: https://www.linkedin.com/in/abhinay-kumar-49b346200
- Email: abhinaykumar2118@gmail.com
- Phone: +91-7733086996