# 📊 AdventureWorks Sales Analytics Dashboard  
### 🟨 Power BI | Power Query | DAX

## 📌 Project Overview  
This project presents a complete **Business Intelligence solution** built entirely in **Power BI** using the AdventureWorks dataset.  
All data cleaning, transformation, and modeling were performed using **Power Query**, followed by KPI calculations and interactive dashboard creation using **DAX**.  
The report provides insights into **sales performance**, **customer behavior**, **product profitability**, and **regional revenue trends** to support data-driven business decisions.

## 🚀 Key Objectives  
- Clean and transform AdventureWorks tables using **Power Query**  
- Build a structured **Star Schema data model** inside Power BI  
- Create DAX-based KPIs such as Total Sales, Profit, Orders, and AOV  
- Design a fully interactive Power BI dashboard for stakeholders  
- Identify trends, product performance, and customer insights.

## 🧼 Data Cleaning (Power Query)  
- Removed null and duplicate values  
- Standardized column names and data types  
- Added calculated columns (Year, Month, Profit, Margin%)  
- Merged and transformed tables where required  
- Filtered unnecessary fields to optimize the model  

## 🧩 Data Model  
A **Star Schema** was created in Power BI containing:

- **Fact Table:** FactInternetSales  
- **Dimension Tables:** DimProduct, DimCustomer, DimDate, DimGeography  

Proper one-to-many relationships were created between fact and dimension tables to support accurate reporting.  



