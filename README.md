# Walmart-Sales-Analysis
A business intelligence project focused on analyzing Walmart's weekly sales performance across multiple stores, evaluating the impact of holidays and external economic factors, and uncovering trends that support strategic business decisions.
Project Goal

The primary objective of this project was to analyze Walmart's historical weekly sales data to identify the key drivers behind sales performance, measure the influence of holidays, and evaluate whether external economic indicators such as fuel prices, unemployment, and CPI significantly affect revenue.

The project aims to help business stakeholders optimize promotional planning, inventory management, and seasonal strategies through interactive Power BI dashboards.
Data Cleaning & Preparation

The dataset contained historical weekly sales records from multiple Walmart stores, along with holiday indicators and economic variables.

Step-by-step:
Initial Data Exploration
Performed descriptive statistical analysis.
Examined data distributions and trends.
Verified data types and business logic.
Checked for duplicate records and inconsistent values.
Data Validation
Ensured each weekly sales record belonged to the correct store and date.
Validated holiday flags against calendar periods.
Verified external economic variables (Fuel Price, CPI, Unemployment).
Handling Missing Values
Inspected missing values across all variables.
Missing records were minimal and handled appropriately depending on the business context.
Numerical values were validated before analysis to avoid misleading KPIs.
Data Transformation
Created Date hierarchy (Year, Quarter, Month).
Classified Holiday vs Non-Holiday periods.
Built calculated columns for time intelligence.
Standardized numeric formats for financial reporting.
Result

A clean analytical dataset was prepared for Power BI modeling with reliable historical sales records suitable for business analysis.

Data Modeling

A Star Schema was implemented to improve performance and simplify analysis.

Fact Table
Weekly Sales
Dimension Tables
Date
Store
Holiday
Economic Indicators

Relationships were established between fact and dimension tables to enable efficient filtering and time-based analysis.

DAX Measures

Several business KPIs were developed using DAX, including:

Total Revenue
Average Weekly Sales
Holiday Contribution %
Holiday Impact %
Weekly Sales Trend
Average Fuel Price
Correlation Analysis
Store Performance Metrics
Tools Used
Power BI — Data Modeling, DAX, Dashboard Development
Excel — Data Cleaning & Initial Exploration
Power BI Dashboards & Key Findings

The project includes one comprehensive executive dashboard containing multiple analytical views.

Executive Dashboard

Provides an overview of Walmart's overall sales performance through:

Executive KPI Cards
Time-Series Sales Analysis
Holiday Performance Analysis
Store Comparison
External Factors Analysis
Interactive Filters
Dynamic Drill-down by:
Year
Quarter
Holiday Type
Key Insights Uncovered
Holiday Performance
Holiday weeks generated approximately 7.5% of total revenue, despite representing a relatively small portion of the calendar.
Average weekly sales during holiday periods were noticeably higher than during regular weeks.
Holidays consistently drive significant sales spikes, confirming the effectiveness of seasonal shopping behavior.
Store Performance
Holiday impact varies considerably across stores.
Some stores experience substantially stronger holiday sales increases than others.
This indicates differences in customer demographics, regional demand, and local shopping behavior.
Sales Trend Analysis
Weekly sales remain relatively stable throughout the year but experience significant spikes during major holiday events.
These peaks repeat consistently, highlighting predictable seasonal demand patterns.
External Economic Factors

Correlation analysis revealed that external economic indicators have very limited influence on Walmart's weekly sales.

Factor	Correlation
Fuel Price	0.01
CPI	-0.07
Unemployment	-0.11

These results indicate:

Fuel prices have almost no measurable effect on weekly sales.
CPI shows a very weak negative relationship.
Unemployment has only a slight negative correlation.

Overall, Walmart's weekly revenue appears to be driven far more by seasonal demand and holidays than by short-term economic fluctuations.

Holiday vs Non-Holiday Comparison
Holiday weeks generate significantly higher average weekly sales.
Although holiday weeks account for a much smaller number of weeks, they contribute disproportionately to total revenue.
This highlights the importance of promotional planning during key shopping periods.

 Business Recommendations
 
Based on the analysis, the following strategic actions are recommended:

Marketing
Increase promotional campaigns before major holidays.
Focus advertising budgets around seasonal shopping events.
Inventory Planning
Allocate additional inventory to stores with historically high holiday performance.
Use historical holiday demand patterns to improve stock forecasting.
Store Management
Identify top-performing stores during holidays and replicate successful strategies across other locations.
Financial Planning
Prioritize seasonal sales forecasting over short-term economic indicators when planning revenue targets.

Conclusion

This project demonstrates that seasonality and holidays are the primary drivers of Walmart's weekly sales performance, while external economic factors such as fuel prices, CPI, and unemployment have only a minimal impact.

Through Power BI dashboards, interactive filtering, and KPI-driven analysis, the project provides business stakeholders with actionable insights to improve marketing strategies, inventory allocation, and operational planning.

The dashboard enables decision-makers to quickly identify high-performing periods, evaluate store-level performance, and make data-driven decisions that maximize revenue during critical sales seasons.

🔗 Live Demo

Explore the interactive Power BI dashboard here:

View Interactive Dashboard
