# Data-Analysis-Portfolio
Sameer Raghavendra - Data Analyst Portfolio


I am an Associate Software Engineer with 2 years of experience in software development and optimization, driven by a passion for delivering high-performance applications. My experience includes optimizing data retrieval processes to improve efficiency by up to 40%, reducing bug backlogs for enhanced software stability, and contributing to timely project delivery in Agile environments.

Throughout my career, I’ve worked on real-time data-driven solutions, including monitoring usage statistics from vending machines and supporting backend systems for European banking clients. My toolkit includes Python, SQL, Power BI, and Excel — enabling me to clean, analyze, and visualize data effectively to generate actionable insights.

I thrive in collaborative environments, actively participate in sprint meetings, and contribute to the full development lifecycle — from requirement analysis to production support. My commitment to quality is reflected in consistently achieving a 95% code quality score and improving server response times.

Here is my Resume https://github.com/sameerRaghava/Data-Analysis-Portfolio/blob/main/SameerRaghavendraResume.pdf

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

These are Portfolio Projects

1. Project Name: Vending Machine Usage Analytics

Code : https://github.com/sameerRaghava/My-First-Project

Summary: This project focuses on analyzing product usage data collected from a network of smart vending machines. Using Python and SQL, I developed a solution to monitor inventory levels and usage trends in real time. By identifying high-demand items and restocking inefficiencies, the model enhanced operational efficiency and contributed to a 40% improvement in data retrieval speed. Visualizations were created in Power BI to help stakeholders make informed decisions regarding stock routing and supply chain optimizations.

# 🧮 Customer Purchase Trends Analysis

## Overview
This project analyzes customer transaction data to discover patterns and insights that businesses can leverage for decision-making. Techniques like data preprocessing, EDA, and visualization are used to understand how customers interact with different product categories and what timeframes drive the most sales.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Insights
- Identified peak sales periods and seasonal trends
- Visualized category-wise customer engagement
- Provided actionable insights to improve stock planning

## Folder Structure
- `data/` – Contains the raw and cleaned datasets
- `notebooks/` – Jupyter notebooks with code and analysis
- `output/` – Visualizations and summary CSVs



2. Project Name: Customer Purchase Trends Analysis

code: https://github.com/sameerRaghava/My-Second-Project

Summary: In this project, I used Microsoft Excel to perform end-to-end data analysis on a sales dataset. The workflow included data cleaning, formula-driven transformations, pivot table creation, and dashboard visualizations. The final outcome is an interactive and insightful Excel dashboard that highlights sales performance by region, product category, and customer type. This project demonstrates strong analytical thinking and proficiency in Excel’s data tools, valuable for quick insights in business contexts.

# 📊 Sales Insights Dashboard using Excel

## 📝 Project Overview
This project showcases how Excel can be effectively used for data analysis and business intelligence. The dataset includes customer purchases across multiple regions. Using Excel’s built-in features, I created dynamic summaries and visual dashboards that help in understanding product performance and customer behavior.

## 🛠 Tools & Features Used
- Excel Pivot Tables
- Excel Formulas (VLOOKUP, IF, SUMIFS)
- Conditional Formatting
- Pivot Charts
- Slicers & Filters

## 📈 Key Highlights
- Region-wise and product-category sales summary
- Interactive dashboard for quick insights
- Top customers and best-selling products identification
- Monthly and quarterly trends visualization

## 📁 Files Included
- `sales_data.xlsx`: Cleaned dataset
- `sales_dashboard.xlsx`: Final Excel dashboard
- `README.md`: Project overview and insights

## 📌 Skills Demonstrated
- Data Cleaning in Excel
- Business Analysis
- Dashboard Design
- Reporting and Storytelling through data



3.Project Name: Sales Insights Dashboard using Excel

code: https://github.com/sameerRaghava/My-Third-Project

Summary: In this project, I used Microsoft Excel to perform end-to-end data analysis on a sales dataset. The workflow included data cleaning, formula-driven transformations, pivot table creation, and dashboard visualizations. The final outcome is an interactive and insightful Excel dashboard that highlights sales performance by region, product category, and customer type. This project demonstrates strong analytical thinking and proficiency in Excel’s data tools, valuable for quick insights in business contexts.

Overview
This project demonstrates the power of data visualization and business intelligence using Microsoft Power BI. It focuses on analyzing employee performance, departmental distribution, and productivity metrics to assist in strategic HR decision-making.

## 🧰 Tools & Techniques
- Power BI Desktop
- Power Query (for data transformation)
- DAX (Data Analysis Expressions)
- Interactive visualizations: Cards, Bar Charts, Pie Charts, Line Charts
- Filters, Slicers, Drill-throughs

## 🎯 Key Insights
- Department-wise distribution of employees
- Monthly performance tracking across teams
- Headcount trends and turnover rate (if applicable)
- Top-performing employees and teams
- Dynamic filters for real-time analysis

## 📁 Project Files
- `HR_Performance.pbix`: Power BI report file
- `data/employee_data.xlsx`: Raw dataset used for analysis
- `README.md`: Documentation and summary

## 📌 Skills Demonstrated
- Data modeling and transformation in Power BI
- Creating dashboards and visual storytelling
- Advanced DAX measures for custom KPIs
- Building reports for non-technical business users

  4.  Project Name: Sales and Customer Analytics using SQL
 
  code : https://github.com/sameerRaghava/My-Fourth-Project
  
  Summary: This project showcases how SQL can be used to extract meaningful insights from a structured relational database. By writing optimized queries, I analyzed customer purchasing behavior, revenue trends, and product popularity. Key operations involved data filtering, joining multiple tables, aggregation, and using window functions. The project highlights strong foundational skills in SQL for data analysis and reporting.

  # 🗃️ Sales and Customer Analytics using SQL

## 🔍 Project Overview
This project focuses on exploring a sales database using SQL. It includes writing queries to analyze product performance, customer demographics, and revenue generation. The results help in understanding sales drivers and optimizing marketing strategies.

## 🛠 Tools & Environment
- MySQL / PostgreSQL / SQL Server (adjust based on what you used)
- SQL Workbench / pgAdmin / Azure Data Studio
- Sample Database (e.g., AdventureWorks, or a custom dataset)

## 💡 Key Queries & Use Cases
- Top 10 best-selling products by revenue
- Monthly sales trends
- Customer segmentation based on purchase frequency
- Join operations to combine product, order, and customer info
- Window functions to rank customer spending behavior

## 📁 Project Files
- `queries/`: SQL query scripts (.sql or .txt)
- `results/`: Screenshots or CSVs of query outputs (optional)
- `README.md`: This documentation

## ✅ Skills Demonstrated
- Data extraction using SELECT, JOIN, GROUP BY, ORDER BY
- Aggregate functions (SUM, COUNT, AVG)
- Subqueries and nested filters
- Window functions (ROW_NUMBER, RANK, etc.)
- Translating business questions into SQL queries

## 📌 Sample Query

```sql
-- Top 5 revenue-generating products
SELECT product_name, SUM(total_amount) AS revenue
FROM sales
GROUP BY product_name
ORDER BY revenue DESC
LIMIT 5;



