# PowerBIDashboard

Summary of the project


Get data: 
Contoso BI Demo Dataset for Retail Industry, downloaded from: https://www.microsoft.com/en-US/download/details.aspx?id=18279, to SQL Server backup folder and restored in Microsoft SQL Server Management Studio, providing access to Contoso database. 

Import data to Power BI: 
Importing Contoso database from SQL Server and choosing tables of interest, precisely:  FactSales, DimChannel, DimCurrency, DimDate, DimEmployee, DimGeography, DimProduct, DimSalesTerritory, DimStore. 

Modeling data: 
In Power Pivot data has been modeled around measurement table FactSales, according to star schema. 

Dax Measures: 
New table by the name Calculations was created and all new measures created with Dax were placed inside of the table. Those measures are: Total Revenue, Gross Profit, COGS, Gross Profit Margin, Total Transactions, Transactions per Day, Average Profit per Transaction, Days Selling, Profit per day, Promo Sales Revenue, Nonpromo Sales Revenue, Last Year Promo Sales Revenue, Last Year Nonpromo Sales Revenue, Number of stores, Same Period Last Year Total Revenue, Ranking. Functions that were used are: SUM, CALCULATE, DISTINCTCOUNT, COUNTROWS, SAMEPERIODLASTYEAR, RANKX. 

Visualization: 
Creation of report pages. Charts used: Card, Multi-row Card, Clustered Bar Chart, Line Chart, Treemap, Donut Chart, Map, Table, Matrix, ArcGis Map, Slicer. Additional features that were used are: Filters, Drill down, Drill through, Tooltips.
