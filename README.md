# SQL Sales Analysis – AdventureWorks 2017

## Project Overview
This project consists of a **sales analysis using SQL** on the **AdventureWorks 2017** database, a well-known Microsoft sample dataset that represents a fictional global bicycle manufacturing and retail company.

The project was developed as part of a **Data Analyst training program** and focuses on answering **business-driven questions** related to sales performance, profitability, customer acquisition, and product mix using SQL queries.

---

## Business Objectives
- Analyze **sales and profit trends** over time  
- Identify **seasonality and growth patterns**  
- Evaluate **customer acquisition** over time  
- Assess **geographical performance** by country and region  
- Identify the **most profitable product categories and subcategories**

---

## Dataset
- **Source:** AdventureWorks 2017 Sample Database (Microsoft)
- **Business domain:** Sales, customers, products, geography
- **Time period analyzed:** 2011–2014
- **Data type:** Relational database (fact and dimension tables)

---

## SQL Techniques Used
- `INNER JOIN` and `LEFT JOIN`
- Aggregations with `GROUP BY`
- Time-based analysis (monthly and yearly)
- Calculated fields for **revenue, profit, and margins**
- Subqueries
- Creation of a **data panel** to centralize key metrics

---

## Methodology
- Business understanding and definition of analytical goals  
- Creation of a **main data panel query (`datapanel.sql`)** to consolidate sales metrics  
- Data validation and consistency checks  
- Exploratory and analytical SQL queries to answer business questions  
- Interpretation of results and formulation of conclusions and recommendations  

---

## Key Insights
- Revenue and profit show a **clear upward trend**, despite some volatility  
- Two significant revenue drops were identified (Q3 2012–Q1 2013 and Q1 2014–Q2 2014)  
- **Australia** is the market with the highest contribution to total profit  
- The **United States** generates high revenue but shows lower profit margins  
- Sales expansion into new regions reduced dependency on volatile markets  
- **Bikes** account for approximately **85% of total profit**, indicating a strong product concentration  

---

## Project Deliverables
- [Presentation (PDF)](presentation/Análise_Vendas_AdventureWorks2017_PPT.pdf)
- [SQL Documentation (PDF)](report/Documentacao_SQL.pdf)

---

## Repository Structure
├── data/

│ └── README.md

├── sql/

│ ├── datapanel.sql

│ └── queries.sql

├── presentation/

│ └── Analise_Vendas_AdventureWorks2017_Presentation.pdf

├── report/

│ └── AdventureWorks_SQL_Documentation.pdf

└── README.md

---

## What I Learned
- Translating **business questions into SQL queries**  
- Structuring complex queries for analytical purposes  
- Performing time-series and geographical analysis using SQL  
- Communicating analytical results through reports and presentations  

---

## Author
**Luís Machado**  
Junior Data Analyst  

**Tools:** SQL | Excel | Power BI | Python  

