CleanedCustomer Behavior Analytics: End-to-End BI Pipeline
This project demonstrates a complete professional data lifecycle, transforming fragmented consumer shopping data into a centralized, interactive Business Intelligence solution. By integrating Python for ETL, SQL Server for relational storage, and Power BI for advanced modeling, I have built a system that identifies high-value customer segments and optimizes retail decision-making.

The Technical Architecture
1. Data Engineering & ETL (Python)
Objective: Cleanse and structure raw data for high-integrity database ingestion.

Process: Used Pandas to handle missing values, validate data types, and perform exploratory data analysis (EDA).

Automation: Developed a script using SQLAlchemy to automate the migration of processed data directly into a production-ready SQL environment.

2. Relational Database Modeling (SQL)
Objective: Establish a robust "Source of Truth" for complex business queries.

Advanced Querying: Authored scripts to calculate multi-dimensional metrics, including revenue by gender, shipping efficiency, and subscription-based spend analysis.

Business Logic: Implemented SQL CASE statements to dynamically segment customers into "New," "Returning," or "Loyal" based on historical purchase frequency.

3. Business Intelligence & Visualization (Power BI)
Objective: Visualize KPIs to drive executive action.

DAX Engineering: Created sophisticated measures for unique customer counts, average review ratings, and total revenue.

Demographic Bining: Engineered an Age Group dimension (Young Adult, Middle-Aged, Senior) using Power Query to identify which generation drives the highest ROI.

UX/UI Design: Built a responsive dashboard featuring synchronized slicers for Category, Location, and Shipping Type to allow for real-time data drilling.

Key Business Insights Delivered
Revenue Drivers: Identified specific product categories (e.g., Clothing, Accessories) that maintain the highest average purchase values.

Customer Loyalty: Quantified the impact of loyalty programs, revealing that repeat buyers (5+ purchases) are significantly more likely to maintain active subscriptions.

Demographic Spending: Discovered that specific age brackets contribute disproportionately to total revenue, providing a roadmap for targeted marketing spend.

Project Files
dataanalyst.ipynb: Python ETL and Data Migration script.

dataanalystproject.sql: SQL Server scripts for relational analysis.

DATAANALYST Dashboard.pbix: Interactive Power BI Dashboard.

customer_shopping_behavior.csv: Raw source dataset.

Technologies Used
Languages: Python (Pandas, SQLAlchemy, Jupyter).

Database: Microsoft SQL Server (SSMS).

Visualization: Power BI (DAX, Power Query). raw data in Python, migrated to SQL Server, and built a Power BI dashboard. Features DAX-driven age groups and interactive KPIs to track revenue and customer behavior.
