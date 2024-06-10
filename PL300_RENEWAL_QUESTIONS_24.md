1)  You have a Power BI data model that has the following tables: Sales, Returns, Customer, and Date. No relationships have been created.

You need to view and filter sales and returns by the same months at the same time.

What three actions should you perform? Each correct answer presents part of the solution.

Select all answers that apply.

- Create a DAX measure that combines sales and returns.
- Create a month column in both the Sales and Returns tables.
- Create a relationship between Sales and Date.
- Create a relationship between the Returns and Date.
- Select the Date table and select Mark as date table.

2. You preview a single table in Power Query Editor in Power BI Desktop. The table contains the following columns: ProductName, ProductID, SalesDate, and SalesAmount.

You need to convert the table into a properly formed star schema.

To which table should you add the SalesAmount field?

Select only one answer.

Product Dimension

Product Fact

Sales Dimension

Sales Fact

3. You need to ensure that when users use the Q&A visual in a Power BI report, the visual maps the word “Country” to the Geography[Region] field in the semantic model. The solution must NOT change any existing visuals.

What should you do?

Select only one answer.

Add a synonym to the Geography table.

Add a synonym to the Region column.

Rename the Region column to Country.

Set the row label in the Geography table to Region.

4. You preview a single table in the Power Query Editor in Power BI Desktop. The table contains the following columns: LocationName, LocationID, Temperature, and DateTime.

You need to convert the table into a properly formed star schema.

To which table should you add the LocationName field?

Select only one answer.

Date Dimension

Location Dimension

Location Fact

Temperature Measurements Fact

5. You need to write a DAX measure that returns the revenue for selected dates during the previous year.

Which two DAX functions should you include in the measure? Each correct answer presents part of the solution.

Select all answers that apply.

CALCULATE

CLOSINGBALANCEYEAR

PREVIOUSQUARTER

SAMEPERIODLASTYEAR

6. You have a Power BI model that contains a table named Person. The Person table contains a whole number column named Age.

You need to write a DAX measure that finds the middle value in the range of Age values.

What formula should you use?

Select only one answer.

AVERAGE('Person'[Age])

MEDIAN('Person'[Age])

RANK.EQ('Person'[Age], ‘Person’[Age])

STDEV.P('Person'[Age])

7. You have a Power BI data model that contains two tables: Sales and Date. The Sales table can be related to the Date table by either the Sales Date column or the Ship Date column.

You need to create a role-playing dimension using DAX. The role-playing dimension must support the ability to filter sales where Ship Date is in the current month and Sales Date is in the prior month.

Which type of DAX expression should you use?

Select only one answer.

Calculated column

Calculated table

Measure

What-If analysis

8. You have a Power BI data model that contains the following three tables:

Sales
Date
Product
The Sales table is related to the Date and Product tables by using many-to-one relationships. The Sales table contains a column named Total Sales Amount.

You need to create a measure named Total Sales that can be used in visuals to aggregate Total Sales Amounts by product or by date.

What should you use?

Select only one answer.

Total Sales = ALL(‘Sales’[Total Sales Amount])

Total Sales = CALCULATE([Total Sales])

Total Sales = MAX(‘Sales’[Total Sales Amount])

Total Sales = SUM(‘Sales’[Total Sales Amount])

9. You create a Power BI model that contains the sales for the last five years. The size of the model is 950 MB. The Sales table contains five million rows.

You need to minimize the model size and perform the following analysis:

Current and one previous year sales for all active products
Current year sales by product category
What should you do?

Select only one answer.

Remove the Product Status column.

Remove the rows that relate to inactive products.

Remove the rows that relate to sales that occurred more than two years earlier.

Remove the Sale Date column.

10. You have a Power BI model that contains sensor data from 500 sensors that return temperature readings each minute.

Your reporting requirements include the calculation and display of the average temperature from each sensor at every hour. The reports do NOT show the raw data for each minute.

You need to reduce the size of the model to improve performance.

What should you do?

Select only one answer.

And a report filter for the Hour column.

Create visuals that group the data by hour.

Remove the rows that contain readings.

Use Power Query to group the sensor data by hour.

11. You have a Power BI data model that contains a table named Contacts.

Contacts contains the following text columns:

Name
Email
Phone
Subscribed to Newsletter
All columns use the Text data type. The Phone column contains the area code, number, and country code. The Subscribed to Newsletter column contains a value of true or false.

You need to minimize the size of the data model by changing a column’s data type. The solution must prevent data loss.

What should you do?

Select only one answer.

Change Phone to a decimal data type.

Change Phone to a whole number data type.

Change Subscribed to Newsletter to a binary data type.

Change Subscribed to Newsletter to a True/False data type.

12. You have a Power BI report that has one page.

You need to configure the report to meet the following requirements:

The page color must be gray
The color of the area around the page must be light blue
Which two tasks should you perform? Each correct answer presents part of the solution.

Select all answers that apply.

Set the canvas background color to gray.

Set the canvas background color to light blue.

Set the wallpaper color the gray.

Set the wallpaper color to light blue.

13. You are creating a visualization in a Power BI report.

You need to recommend which visualization to use in the report to perform a quick comparison of the current quarter sales by country.

Which visualization type should you recommend?

Select only one answer.

column chart

gauge chart

matrix

scatter chart

14. You plan to use Power BI report visual to display sales values that change over time.

You need to identify a visualization to use. The solution must clearly illustrate the changes of sales values over time.

Which visualization type should you identify?

Select only one answer.

Column chart

Doughnut chart

Funnel chart

Pie chart

15. You need to create a sales report in Power BI that meets the following requirements:

Must display data in tables with headers and footers
Must print all data in the report
Must allow users to select a region value in the parameters
What should you do?

Select only one answer.

Create a paginated report with a table.

Create a scorecard.

Create an interactive report with a matrix.

Create an interactive report with a table.

16. You have a report that has three overlapping visuals: a bar chart, a line chart and a card.

You need to modify the report to meet the following requirements:

the card must render above the line chart
the line chart must render above the bar chart.
What setting should you modify?

Select only one answer.

Aspect ratio

Layer order

Tab order

Vertical alignment

17. You have a Power BI report that contains a clustered column chart visual. The visual shows the revenue on the y-axis and the month on the x-axis.

You need to ensure that users can drill down from month to week to day.

To what should you add the Week and Day fields?

Select only one answer.

Legend

Small Multiples

X-axis

Y-axis

18. You plan to analyze sales data in Power BI by using the following fields:

Sales amount
Order Quantity
Product
You need to use clustering to identify groups of similar data points in a subset of your data.

What visualization type should you use?

Select only one answer.

Line chart

Scatter chart

Tree map

Waterfall chart

19. You plan to use Power BI to analyze taxi cab rides in New York City. You need to review the total distance of rides by date.

You need to visually indicate anomalies in the values as well as the expected range of distance values for the date.

What visual should you use?

Select only one answer.

Line chart

Pie chart

Scatterplot

Tree map

20. You have a workspace that contains two semantic models and five reports.

You need to grant all department users read access to only one of the semantic models and three of the reports. Access should be automatically removed for users who leave the department.

Which two actions should you perform? Each correct answer presents part of the solution.

Select all answers that apply.

Add the security group containing the users to the Viewer role on the workspace.

Grant app access to the security group containing the users and publish the app.

Set Include in App to Yes for all semantic models and reports.

Set Include in App to Yes for the one semantic model and the three reports.

Share the one semantic model and the three reports with each user in the department.

21. You have a workspace that contains two semantic models and five reports.

You need to grant all department users read access to only one of the semantic models and three of the reports. Access should be automatically removed for users who leave the department.

Which two actions should you perform? Each correct answer presents part of the solution.

Select all answers that apply.

Add the security group containing the users to the Viewer role on the workspace.

Grant app access to the security group containing the users and publish the app.

Set Include in App to Yes for all semantic models and reports.

Set Include in App to Yes for the one semantic model and the three reports.

Share the one semantic model and the three reports with each user in the department.

22. You have a workspace named workspace1 in the Power BI service. Content is shared to users by using a Power BI app.

You have made updates to a report in the workspace, and you need to distribute the updated report.

What should you do?

Select only one answer.

Add the appropriate users to the Viewer role in the workspace.

Save a copy of the report to a different workspace.

Share the updated report with the appropriate security group.

Update the Power BI app.

23. You have published an imported semantic model to a workspace. The workspace is in the shared capacity of the Power BI service. The source data changes every 5 minutes.

You need to keep the data in the Power BI semantic model as current as possible without upgrading Power BI licenses or changing the workspace.

What should you do?

Select only one answer.

Configure a scheduled refresh 8 times a day.

Configure a scheduled refresh every 15 minutes.

Configure a scheduled refresh every hour of each day.

Perform an on-demand refresh once a day.

24. You have a Power BI workspace that contains a semantic model named ModelA. You have a Microsoft Entra group named GroupA. GroupA is currently not assigned to a workspace role.

You need to ensure that GroupA can use Analyze in Excel with ModelA.

What permissions should you grant?

Select only one answer.

Build

Read

Reshare

Write