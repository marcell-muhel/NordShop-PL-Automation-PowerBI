# 📊 NordShop Kft. - Power BI P&L & Financial Reporting Automation

**Author:** Marcell Muhel | Business Controller & Data Analyst
**Tools Used:** Power BI, Power Query (M), DAX, Excel, Data Modeling (Star Schema)

## 📌 Executive Summary
This project demonstrates an end-to-end automated Business Intelligence solution built for a fictional FMCG retail network (NordShop Kft.). The objective was to replace a slow, manual, Excel-based monthly closing process with a dynamic, real-time Profit & Loss (P&L) tracking system.

## 🚨 The Business Pain
The company operates a complex network of 12 retail stores, 3 depots, a wholesale division, and a central office (approx. 300 employees). Previously, the monthly controlling and P&L closing was a manual, multi-day process. 
Sales data, costs, headcount, and budget plans existed in isolated, multi-thousand-row Excel files, preventing management from having real-time visibility into the profitability of individual units.

## ⚙️ The Architecture & Solution
I engineered a fully automated BI architecture from the ground up:
* **ETL Processes (Power Query):** Automated the extraction, transformation, and loading (ETL) of raw CSV/Excel data. Transformed wide tables into Long Format for database efficiency.
* **Data Modeling (Star Schema):** Built a robust relational database where transactions flow into a central Fact Table (`_00_ADATBAZIS`), connected to dimension tables (Date, Location, Cost Types).
* **Advanced DAX Logic:** Programmed complex DAX measures for dynamic cost planning (e.g., automated calculation of upcoming budgets applying macroeconomic multipliers like 9% wage growth, 5% rent increase) and variance (Plan vs. Actual) analysis.

## 📈 The Business Value (ROI)
* **Real-time Transparency:** Management now views Plan / Actual / Variance metrics per store on a single, interactive Power BI dashboard.
* **Time Efficiency:** The time required for the monthly closing and P&L report generation was reduced from days to minutes.
* **Cost Control:** Dynamic margin and cost analysis allows for the immediate identification of loss-making operations and rapid intervention.

## 📂 Repository Contents
* `NordShop_Demo_Power_BI.pbix`: The complete Power BI project file (Data model + Visuals).
* `NordShop_Demo_PL_Documentation.pdf`: Detailed structural documentation of the P&L logic.
* `NordShop_Dashboard_Preview.pdf`: High-resolution visual export of the management dashboard.

---
*If you are interested in how this approach can scale and automate your company's financial reporting, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/marcell-muhel).*
