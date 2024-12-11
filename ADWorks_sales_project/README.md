# ADWorks Sales Analysis
ADWorks is a fictitious bicycle and spare parts retail company. For this project, I created a two-page report to visualize how sales for different products and categories vary. I used a snowflake schema to model the data.

**ADWorks.pbix:** The Power BI report

**FactInternetSale.csv:** The fact table in this model. The fact table records measurements of metrics specific to the business process. In this case, product sales.

**Remaining Dimension Tables**: All other CSV files are dimension tables. DimDate is the date table; it provides the temporal dimension for our analysis. DimSalesTerritory contains location data. The remaining tables contain product and category information.
