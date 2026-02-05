[# 📊 Contoso Retail BI Capstone Project]([url](https://island-minnow-898.notion.site/Capstone-2fd7c3dcaf718051afe0eeee62fe4ed0))

## Overview
This project delivers an end-to-end **Business Intelligence solution** for Contoso, a multi-channel retail company. Using SQL Server and Power BI, the project transforms large-scale transactional and dimensional data into an executive-ready dashboard that supports performance monitoring, profitability analysis, and strategic decision-making.

The dashboard provides both **high-level KPIs** and **deep analytical views**, allowing users to move seamlessly from summary metrics to detailed insights across products, stores, geography, and time.

---

## Business Problem and Opportunity
Contoso operates across multiple sales channels (Store, Online, Catalog, Reseller) with a complex product hierarchy and geographically distributed stores. The core challenge is converting high-volume, fragmented data into **accurate, comparable, and actionable KPIs**.

This project demonstrates how a properly designed data model and robust DAX measures can:
- Align actual performance with historical benchmarks
- Track operational scale and efficiency
- Identify profitability drivers and risk areas
- Enable consistent analysis across dimensions without double counting. 

---

## Key Insights
- Revenue is highly concentrated within a small subset of products and channels
- Online and Catalog channels drive significant volume but differ in margin behavior
- Store footprint growth does not always translate into proportional profit growth
- Discounts can inflate sales volume while eroding gross margin

---

## Key Findings
- A classic **80/20 pattern** exists across products and customers
- Gross Margin trends differ materially from Net Sales trends
- Organic growth must be separated from promotion-driven growth
- Operational metrics (stores, employees, area) require controlled filter propagation to avoid inflation

---

## Business Dimensions
The analytical model is built around the following core dimensions:

- **Date**: Calendar Year, Quarter, Month (time intelligence backbone)
- **Product**: Category → Subcategory → SKU
- **Geography**: Continent, Country/Region, City
- **Store**: Store Type, Store Size, Employees
- **Channel**: Store, Online, Catalog, Reseller
- **Scenario & Strategy Plan**: Actual vs Budget

A star-schema design ensures reliable filtering, scalable calculations, and predictable DAX behavior.

---

## Recommendations
- Focus on high-margin product segments rather than volume-only growth
- Use Pareto analysis to prioritize customer and product investments
- Monitor discount impact separately from organic growth
- Standardize KPI definitions across the organization to avoid misinterpretation

---

## Workflow Summary
1. Restored and validated Contoso data from SQL Server
2. Designed and validated dimensional relationships
3. Built reusable base measures (Net Sales, Cost, Quantity, Profit)
4. Implemented time intelligence (LY, YoY %, Running Totals)
5. Created advanced analytical logic (Ranking, Pareto, Quadrant Analysis)
6. Designed an interactive Power BI report with bookmarks and parameters
7. Validated results against business logic and edge cases

---

## Tools & Technologies
- **SQL Server / SSMS** – Data storage and validation  
- **Power BI** – Data modeling, DAX, visualization  
- **DAX** – Time intelligence, ranking, running totals, Pareto logic  
- **Power Query** – Data cleansing and transformation  


---

## Conclusions
This project demonstrates how Business Intelligence is not just about building visuals, but about **controlling data behavior** through proper modeling and DAX design. Accurate KPIs require deliberate relationship management, clear measure definitions, and awareness of aggregation pitfalls.

The resulting dashboard functions as a **decision-support system**, not just a reporting tool.


---

## What This Project Demonstrates
- Strong understanding of dimensional modeling
- Advanced DAX and time intelligence skills
- Ability to translate business questions into analytical solutions
- Experience handling large, real-world retail datasets

