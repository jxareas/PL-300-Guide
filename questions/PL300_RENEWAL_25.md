# PL 300 Renewal Questions 2025

The following markdown file contains questions found in the Power BI PL-300 Certification Renewal Exam,
which have been obtained via web scraping and browsing exam dumps.

They're sorted in no specific order, and answered by an LLM (**THIS IS NOT AN OFFICIAL ANSWER**).

## Q1.

You preview a query from the Power Query Editor.

You notice that Column A contains blank values and null values.

You need to convert all blank values to null.

**Which option should you select from Column A?**

**Select only one answer.**

- Clean
- Fill Down
- Replace Errors
- **Replace Values**

## Q2.

You are previewing an Excel file in Power Query Editor by using Power BI Desktop. The file contains data in two columns.
One column lists categories. The other column lists subcategories in each category.

You need to transform the data to a table that has a separate column for each category and contains the count of
subcategories for each category.

**What transform should you use?**

**Select only one answer.**

- **Pivot**
- Promote headers
- Transpose
- Unpivot

## Q3.

You are previewing two queries named Query1 and Query2 in Power Query Editor. Query1 contains data about employee IDs 1
through 10. Query2 contains data about employee IDs 5 through 15.

You merge by using a left outer join from Query1 to Query2.

**Which employee IDs will be present in the merged query?**

**Select only one answer.**

- **1 through 10**
- 5 through 10
- 5 through 15
- 11 through 15

## Q4.

You need to create a relationship between two tables named `Sales` and `Sales Detail` in a Power BI data model. For
every row in the `Sales` table, there is at least one row, and possibly multiple rows, in the `Sales Detail` table.

**How should you configure the relationship?**

**Select only one answer.**

- many-to-many from Sales to Sales Detail
- many-to-one from Sales to Sales Detail
- **one-to-many from Sales to Sales Detail**
- one-to-one from Sales to Sales Detail

## Q5.

You preview a single table in the Power Query Editor in Power BI Desktop. The table contains the following columns:
`LocationName`, `LocationID`, `Temperature`, and `DateTime`.

You need to convert the table into a properly formed star schema.

**To which table should you add the LocationName field?**

**Select only one answer.**

- Date Dimension
- **Location Dimension**
- Location Fact
- Temperature Measurements Fact

## Q6.

You have a Microsoft Power BI semantic model that contains a dimension table named `DimCustomer` and a fact table named
`FactOrder`. `DimCustomer` contains one row per customer. `FactOrder` contains one row per order.

You need to create a relationship between `DimCustomer` and `FactOrder`.

**Which type of relationship cardinality should you choose?**

**Select only one answer.**

- many-to-many
- many-to-one
- **one-to-many**
- one-to-one

## Q7.

You have a Microsoft Power BI semantic model that contains three tables named `DimDate`, `FactSales`, and
`FactInventory`. `DimDate` is a dimension table that contains one row per date. `FactSales` is a fact table that
contains one row per item sold. `FactInventory` is a fact table that contains one row per item in the inventory per day.

`DimDate` is related to both `FactSales` and `FactInventory`.

**What type of dimension is DimDate?**

**Select only one answer.**

- degenerate dimension
- junk dimension
- outrigger dimension
- **role-playing dimension**

## Q8.

You have a Power BI model that contains a table named `Person`. The `Person` table contains a whole number column named
`Age`.

You need to write a DAX measure that finds the middle value in the range of Age values.

**What formula should you use?**

**Select only one answer.**

- `AVERAGE('Person'[Age])`
- **`MEDIAN('Person'[Age])`**
- `RANK.EQ('Person'[Age], ‘Person’[Age])`
- `STDEV.P('Person'[Age])`

## Q9.

You have a Power BI data model that contains the following three tables:

- Sales
- Date
- Product

The `Sales` table is related to the `Date` and `Product` tables by using many-to-one relationships. The `Sales` table
contains a column named `Total Sales Amount`.

You need to create a measure named `Total Sales` that can be used in visuals to aggregate `Total Sales Amounts` by
product or by date.

**What should you use?**

**Select only one answer.**

- Total Sales = ALL(‘Sales’[Total Sales Amount])
- Total Sales = CALCULATE([Total Sales])
- Total Sales = MAX(‘Sales’[

## Q10.

You have a Microsoft Power BI semantic model that contains a table named `Table1`. `Table1` contains five columns named
`Sales Date`, `Product ID`, `Quantity`, `Item Price`, and `Region`.

You need to create a measure named `Avg Price - All Regions` that calculates the average item price for items sold
across all regions.

**Which expression should you use in the measure?**

**Select only one answer.**

- **CALCULATE( AVERAGE( Table1[Item Price] ), REMOVEFILTERS( Table1[Region] ) )**
- CALCULATETABLE( AVERAGEX( Table1[Item Price] ), REMOVEFILTERS( Table1[Region] ) )
- CALCULATE( MEDIAN( Table1[Item Price] ), ALL( Table1[Region] ) )
- SUMMARIZE( Table1[Item Price])

## Q11.

You have a Microsoft Power BI semantic model that contains two tables named `FactInventory` and `DimDate`. `FactInventory` is a fact table that contains one row per product per weekday. Inventory balances are NOT recorded on weekends. `DimDate` is the date table in the model.

You need to create a measure that shows the last available inventory balance for a selected period.

**Which DAX function should you include in the solution?**

**Select only one answer.**

- EOMONTH  
- FIRSTNONBLANK  
- **LASTNONBLANK**  
- NETWORKDAYS  

## Q12.

You create a Power BI model that contains the sales for the last five years. The size of the model is 950 MB. The `Sales` table contains five million rows.

You need to minimize the model size and perform the following analysis:

- Current and one previous year sales for all active products  
- Current year sales by product category  

**What should you do?**

**Select only one answer.**

- Remove the Product Status column.  
- **Remove the rows that relate to inactive products.**  
- Remove the rows that relate to sales that occurred more than two years earlier.  
- Remove the Sale Date column.  

## Q13.

You open a report in Microsoft Power BI Desktop and run Performance Analyzer.

The results show a high number of visual displays.

**What is a possible cause of the performance issues?**

**Select only one answer.**

- misconfigured relationships  
- too many columns in the underlying tables  
- **too many fields used in visuals**  
- unoptimized measures  

## Q14.

You have a Power BI model that contains sensor data from 500 sensors that return temperature readings each minute.

Your reporting requirements include the calculation and display of the average temperature from each sensor at every hour. The reports do NOT show the raw data for each minute.

You need to reduce the size of the model to improve performance.

**What should you do?**

**Select only one answer.**

- Add a report filter for the Hour column.  
- Create visuals that group the data by hour.  
- Remove the rows that contain readings.  
- **Use Power Query to group the sensor data by hour.**  

## Q15.

You plan to use a Power BI report visual to display sales values that change over time.

You need to identify a visualization to use. The solution must clearly illustrate the changes of sales values over time.

**Which visualization type should you identify?**

**Select only one answer.**

- **Column chart**  
- Doughnut chart  
- Funnel chart  
- Pie chart  

## Q16.

You are creating a visualization in a Power BI report.

You need to recommend which visualization to use in the report to perform a quick comparison of the current quarter sales by country.

**Which visualization type should you recommend?**

**Select only one answer.**

- **column chart**  
- gauge chart  
- matrix  
- scatter chart  

## Q17.

You have a Microsoft Power BI report that contains two pages. The first page contains a clustered bar chart.

You plan to configure the clustered bar chart to use the second page as a tooltip report.

**What should be done on the second page?**

**Select only one answer.**

- The Allow Q&A setting must be enabled.  
- **The Allow use as tooltip setting must be enabled.**  
- The canvas background transparency must be set to 100%.  
- The Canvas setting must be set to Tooltip.  

## Q18.

You create a Microsoft Power BI report that will be accessed by hundreds of users on their laptops. The report contains one page. The page size is set to the custom dimensions of 2500 x 3500.

You set Page view to Actual size and publish the report to the Power BI service.

**What is the resulting user experience?**

**Select only one answer.**

- a page background image with a misconfigured aspect ratio  
- **a page that requires users to interact with scrollbars to view the entire page**  
- a page that requires users to zoom out to read the visuals  
- a page with a large area of wallpaper shown at the bottom of the page  

## Q19.

You have a Microsoft Power BI report that contains a single page. The page contains six visuals and a button.

You need to create a solution that enables users to replace two visuals with two other visuals by selecting the button.

**What should you do in the selection pane first?**

**Select only one answer.**

- **Group the two visuals that will be replaced when selecting the button.**  
- Group visuals that will not be affected by selecting the button.  
- In the tab order, hide the two visuals that will be replaced.  
- In the layer order, move the two visuals that will be replaced to the bottom.  

## Q20.

You have a report that contains a bar chart and a pie chart. The interactions use the default settings.

You need to ensure that when you select a bar, the pie chart redraws showing only the data related to the bar.

You enable Edit Interactions.

**What should you do next?**

**Select only one answer.**

- Select the pie chart and set the bar chart interaction to Filter.  
- Select the pie chart and set the bar chart interaction to None.  
- **Select the bar chart and set the pie chart interaction to Filter.**  
- Select the bar chart and set the pie chart interaction to None.


