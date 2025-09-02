-Efficient-Inventory Analytics System

An end-to-end inventory analytics solution designed to optimize stock monitoring, warehouse management, and business decision-making using SQL-based data warehousing and Power BI dashboards.

-Tools & Technologies

Database: MySQL

Data Processing: SQL Scripting, ETL (Extract, Transform, Load)

Visualization: Power BI

-Features

🗄Normalized Database Schema

Designed fact & dimension tables for products, suppliers, and transactions.

- ETL Pipelines

Ingested raw CSV datasets, performed data cleaning & transformation, and loaded into staging + warehouse tables.

- Optimized SQL Scripts

Queries, views, and stored procedures to compute critical inventory KPIs:

Inventory Turnover

Stock Age

Days-on-Hand

Reorder Points

- Interactive Power BI Dashboards

Located in the dashboards/
 folder.

Visualizes stock levels, low-inventory alerts, and historical KPI trends for decision-makers.

- Outcomes

Improved inventory visibility across the supply chain.

Reduced manual reporting time by 40% through automation.

Enabled data-driven restocking strategies leading to optimized operations.

- Project Structure
Efficient-Inventory-Analytics-System/
│── sql/                # SQL scripts for schema, ETL, and queries  
│── data/               # Sample CSV datasets  
│── dashboards/         # Power BI dashboards (.pbix files)  
│── README.md           # Project documentation  

 How to Run

Clone the repository:

git clone https://github.com/your-username/Efficient-Inventory-Analytics-System.git
cd Efficient-Inventory-Analytics-System


Import the SQL scripts from sql/ into your MySQL instance.

Load sample datasets from data/ into staging tables.

Open the Power BI dashboards from dashboards/ and connect to your database.

 Dashboards Preview





Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit pull requests.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
