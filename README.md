Global Energy Transition: SQL & Tableau Insights

Project Overview
This project analyzes global electricity generation trends (2017–2023) to evaluate the shift from fossil fuels to renewable energy. By combining SQL data transformation with Tableau visualization, I’ve identified key market leaders, technology efficiency gaps, and geographic investment risks.

Key Business Insights
-Market share analysis reveals a "two-speed" global transition. While Northern Europe and Brazil lead in green capacity, Asia remains heavily reliant on fossil fuels, highlighting a massive opportunity for future infrastructure investment.
- Solar energy shows the highest growth rate but the lowest efficiency ratio, while Bioenergy remains a critical "baseload" partner due to its high reliability.
- Brazil is currently the global "Proof of Concept" for aggressive fossil fuel reduction, outfacing all other nations in absolute generation decline.

Tech Stack
Database: SQL (Data Cleaning, Aggregations, Case Logic)
Visualization: Tableau (Geographic Mapping, Scatter Plots, Interactive Dashboards)
Dataset: Global Electricity Generation & Capacity (2017-2023)

SQL Analysis Breakdown
The analysis was performed using several complex queries to extract business logic:
1. Market Share Analysis
Calculates the percentage of total generation from renewables vs. fossil fuels per country.
Logic: Used SUM(CASE WHEN...) and NULLIF to handle percentage calculations without division-by-zero errors.

2. Year-over-Year (YoY) Growth
Identifies which energy technologies are scaling fastest by comparing 2017 vs. 2023 capacity.
3. Capacity Factor (Efficiency Ratio)
Compares Installed Capacity (MW) to Actual Generation (GWh) to determine which technologies provide the most reliable output.

Tableau Visualizations
The dashboard translates raw data into three strategic views:
Energy Mix Map: A risk/opportunity heatmap for energy investors.
Fossil Fuel Phase-Out Leaderboard: Benchmarking tool for policy effectiveness.
Growth vs. Efficiency Scatter Plot: A portfolio strategy tool to categorize "High-Growth" (Solar) vs. "High-Stability" (Bioenergy) assets.


How to Use

SQL Queries:https://github.com/nazrin06/Global-Energy-Transition-SQL-Tableau/blob/d51895b17b530eba5902a401da539708afcd34ce/sql_queries/Scripts%20and%20comments. 
These can be run on any standard SQL environment.

Tableau Dashboard: [[Link to your Tableau Public profile or Workbook file].](https://github.com/nazrin06/Global-Energy-Transition-SQL-Tableau/blob/6b117536b0719690315885048ca9e2258ae8b3c6/tableau/Tableau_Dashboard.png)
