# Super-Store-Sales-Power BI Dashboard

## Problem Statement

This dashboard helps the Super Store to understand their customers better. It helps the store know about their sales by different parameter. Through different parameter, they get to know their improvement area & thus they can improve their sales by identifying these areas. It also lets them know the sales by category and sub category, thus since by using this dashboard they have identified their sales related problem, they can further work on factors responsible for low sales.

Since, the sales by different parameters are given, so they take decision in order to improve their sales. 

Also, forecast of next 15 days are presented in the dashboard, so accordingly they all work on the future order requirements.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column order ID", "column ship date" & "column region" etc options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Delete the two extra column from the dataset. 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various subcategory, thus in order to represent sales, a new visual was added using the charts and Bar in the visualizations pane in report view.
- Step 8 : Visual filters (Slicers) were added for four fields named "Region".
- Step 9 : Four card visuals were added to the canvas, representing Sales, Orders, Profit & Ship Date.
- Step 10 : Donut charts were also added to the report design area representing the sales by payment mode, region, segment. 
- Step 11 : Two stacked area charts were added to represent the sales and profit year by year.

- Step 12 : In the report view, one map chart added to represent the sum of sales and sum of profit by state.
- Step 13 : In the report view second page added to represent forecast of 15 days and sales by state. 
- Step 14 : Sales by state is also represented through the clustered bar chart in million unit.

- Step 15 : Forecast of sales is a calculated column which is present in the table view that is “Total sales with Order Date”.
