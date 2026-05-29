Global-Housing-Affordability

A Power BI report analyzing housing affordability trends across countries, spanning a 30 year stretch of historical data with forecasting analysis.

This report explores the relationship between house prices and disposable income across countries over time. It enables both broad overarching global comparisons and deep country specific breakdowns, with trend analysis per country.

Pages

- Main
  Landing and Navigation page of the report:
  A data table for quick and easy referencing
  Country and Year Slicers to filter the entire report
  Navigation buttons: Full (for the entire time stretch), 30Y (for the 30 year timeframe), 15Y (for the 15 year timeframe), Reset (Reseting the main page)
  Additional Navigation buttons: Change_For (Drill-through to the Country_Affordability_Change_Forecast), Breakdown (Drill-through to Country_Breakdown)
  
- Global Affordability- Last 30 Years
  A level view of affordability across all countries:
  Bar Chart: Average affordability by country over the last relevant 30 Years (2023 to 1993 for relevant data)
  Card: Average Affordability of Top N (N = 5) countries
  
- Global Timechart
  A Global dynamic scatter-plot showing how affordability has evolved for each country over-time:
  Plots; x = Average Housing Price, y =  Average Disposable Income
  Bubble size is based on the absolute value for the AVERAGE('Table'[affordability_proxy]) for a relative measure for the graph
  Play Axis is based on the year which tracks shifts over time
  
- Country Affordability
  A focused country specific analysis with forecasting of Affordability over-time:
  Line Chart shows the average affordability trend by year, with the dotted section forecasting affordability over the enxt 10 years
  KPI Cards show current affordability and price to disposable income. Also shows 15 Year and 30 Year changes in income and housing price
  
- Country Breakdown
  A country specific deep dive enabling focus on specific data/time points:
  Line Chart displays the disposable income vs housing prices over time.
  Area Chart displays the country affordability by year
  Cards show current affordability, global average affodability, % difference between global and current, and best and worst years for affodability.

Key Metrics
Affordability- Composite measure of housing cost relative to income
Price_To_Dis_Income - Ratio of house price to disposable income
CurrentAffordability - Most recent affordability reading for the selected country
Global Avg Affordability - Cross-country average used as a benchmark
Curr vs Global Avg - (%)How a country compares to the global average
House_Change_15Y / House_Change_30Y% - change in house prices over 15 and 30 years
Change_Dis_Income_15 / Change_Dis_Income_30% - change in disposable income over 15 and 30 years
Best/Worst Affordability Year - Historical peak and trough for a given country
