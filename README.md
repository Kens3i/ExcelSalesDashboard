# INTERACTIVE FASHION SALES DASHBOARD

## MS Excel Dashboard Output

![](https://media.giphy.com/media/p6o1KQMYfLlupbZwBQ/giphy.gif)

## Table of Contents

1.  [Overview](https://github.com/Kens3i/ExcelSalesDashboard#Overview)
2.  [Motivation](https://github.com/Kens3i/ExcelSalesDashboard#Motivation)
3.  [Workbook-Layout](https://github.com/Kens3i/ExcelSalesDashboard#Workbook-Layout)
4.  [Workflow](https://github.com/Kens3i/ExcelSalesDashboard#Workflow)
5.  [Challenges I Faced](https://github.com/Kens3i/ExcelSalesDashboard#Challenges-I-Faced)
6.  [FAQs](https://github.com/Kens3i/ExcelSalesDashboard#FAQs)


## Overview
Developed and designed an **interactive sales dashboard** by using data which has **72000+ columns and 11 Rows** using **MS Excel 2016**. The data is about 2 fashion stores named “Fashion Direct” and “Next Look” based in Australia. The data spans from January 2016 to July 2017. **Any relevant data added will be updated in the dashboard automatically upon refresh**.

## Motivation

This project helped me develop my **Data Dashboarding and Ms Excel Skills**. I also got to know how different graphs work and how **KPIs** are set in a dashboard.

## Workbook-Layout

- Raw Data Sheet.

- Augmented Data Sheet.

- One Sheet for each Pivot Table.

- Dashboard Sheet.


## Workflow

- I have used **Excel Tables, Pivot Tables Pivot Charts**.

- Formatted data in data sheet as table.

- Named the table.

- **Augmented Data Sheet**:

  - Additional Data To add for testing out if the Dashboard gets updated automatically or not.

- **Line Pivot Sheet**:
	- Added Pivot Table in a new sheet and named the pivot table and the sheet.

	- Formatted the grand total by removing the decimal places.

	- Added a line chart **keeping the two companies in y axis and kept the months in x axis**.

- **Category Pivot Sheet**:

	- Added Pivot Table in a new sheet and named the pivot table and the sheet

	- Inserted a bar chart(really good when we have long data labels and horizontally formatted so we don’t have to rotate our head) which has the two companies as two bars, **in y axis there are categories like women, men, kids, etc. and in x axis there is the total sales data**.

	- Sorted the chart from largest to smallest wrt x axis.

- **Manager Pivot Sheet**:

	- Added Pivot Table in a new sheet and named the pivot table and the sheet.

	- Added a horizontal bar chart, the **name of the managers in y axis and total sales in x axis**.

	- Sorted from highest sales to smallest and grouped the data by their states.

- **Pie Pivot Sheet**:

	- Added Pivot Table in a new sheet and named the pivot table and the sheet.

	- We could use any other charts here but to make the dashboard visually pleasing we using pie chart.

	- This pie chart is showing the **sum of sales in % of the two companies**.

- **Sparklines Pivot Sheet**:

	- Added 3 Pivot Table in a new sheet and named all the pivot table and the sheet.

	- Sorted the states.
	
	- This shows the **total sales trend of the two companies and the two companies combined with respect to states**.

- **Map Pivot Sheet**:

	- Added Pivot Table in a new sheet and named the pivot table and the sheet.

	- Added a **line chart with states as x axis and sales as in y axis**.

- **Dashboard Sheet**:

	- Moved all the pivot charts in the dashboard.

	- Formatted the sales and total trend by state.

	- Added if statements(IF) so if there are no values for a particular state then the table will show blank.

	- Added **error handling statements** (IFERROR) i.e if error occurs of any type blank will be shown.

	- Added **SparkLines**.

	- Added **Slicers**:Category,State,Financial Year.

	- **Added Dynamic Labels** in the pie chart, Just concatenating text with ‘&’, I concatenated the store name and the total sum of sales.

	- **Added Connections with slicers** so that if we select slicers then all the graphs gets changed dynamically.




## Challenges-I-Faced

- This was my 1st full fleged data dashboarding project so I had to lookup for the documentaiton of using MS Excel and learn the tool thoroughly.

- Some of the features were locked as per my version of Excel so had to think about implementing the ideas in a different manner.


## FAQs
### Dashboard Vs Reports ?
An Excel dashboard is one-pager (mostly, but not always necessary) that helps managers and business leaders in tracking key KPIs or metrics and take a decision based on it. It contains charts/tables/views that are backed by data.

A dashboard is often called a report, however, not all reports are dashboards.

Here is the difference:

-   A report would only collect and show data in a single place. For example, if a manager wants to know how the sales have grown over the last period and which region were the most profitable, a report would not be able to answer it. It would simply report all the relevant sales data. These reports are then used to create dashboards (in Excel or PowerPoint) that will aid in decision making.
-   A dashboard, on the other hand, would instantly answer important questions such which regions are performing better and which products should the management focus on. These dashboards could be static or interactive (where the user can make selections and change views and the data would dynamically update).

### What is PivotTable ?
A PivotTable is an interactive way to quickly summarize large amounts of data. You can use a PivotTable to analyze numerical data in detail, and answer unanticipated questions about your data. A PivotTable is especially designed for:

-   Querying large amounts of data in many user-friendly ways.
    
-   Subtotaling and aggregating numeric data, summarizing data by categories and subcategories, and creating custom calculations and formulas.
    
-   Expanding and collapsing levels of data to focus your results, and drilling down to details from the summary data for areas of interest to you.
    
-   Moving rows to columns or columns to rows (or "pivoting") to see different summaries of the source data.
    
-   Filtering, sorting, grouping, and conditionally formatting the most useful and interesting subset of data enabling you to focus on just the information you want.
    
-   Presenting concise, attractive, and annotated online or printed reports.

### What is PivotChart?
You can use a PivotTable to summarize, analyze, explore, and present summary data. PivotCharts complement PivotTables by adding visualizations to the summary data in a PivotTable, and allow you to easily see comparisons, patterns, and trends. Both PivotTables and PivotCharts enable you to make informed decisions about critical data in your enterprise.

### Why Excel ?
Yes, there are more specialized tools available that do a better job at what they are made to do, and you should probably use them where available and affordable. And there are some jobs that really require more specialized tools, and although you may be able to blunder through those jobs with hammer, screwdriver, and wrenches, you really shouldn’t because you can’t do that job as well with those generalized tools.

But anyone who said that hammers, screwdrivers, and wrenches are no longer relevant because we have more specialized tools would be laughed of the room. There will ALWAYS be a need for simple, generalized tools. And for the same reason, there will always be a need for a good spreadsheet. And Excel is the best and most versatile spreadsheet.

### What Are Key Performance Indicator(KPI)?
Key Performance Indicators (KPIs) are the critical (key) indicators of progress toward an intended result. KPIs provides a focus for strategic and operational improvement, create an analytical basis for decision making and help focus attention on what matters most.

### Thankyou For Spending Your Precious Time Going Through This Project!
### If You Find Any Value In This Project Or Gained Something New Please Do Give A ⭐.
