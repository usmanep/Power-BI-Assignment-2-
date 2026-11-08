# Power-BI-Assignment-2-
DAX &amp; Data Visualization
Created New Colunm & merged the Category & Sub Category
Calculated revenue per Order as add new column by giving equation Amount * Quantity
Categorise the sales by using function "IF" 100 below is "below average" above that is " Above average"
New measure created to count the total number of rows in the order details table using formula "DISTINCTCOUNT('Order Details')
Find average Profit in Delhi by using formula "CALCULATE(AVERAGE('Order Details'[Profit]),'List of Orders'[City] = "Delhi")
 Find YTD sales by creating first a date table by using formula = ADDCOLUMNS(CALENDAR(DATE(2018,01,01),DATE(2019,12,31)),"Year", YEAR([Date]),"Month NUmber",MONTH([Date]),"Month Name",FORMAT([Date],"MMMM"),"Quarter", "Q" & QUARTER([Date]),"Day",DAY([Date]),"Day Name",FORMAT([Date],"DDDD")) before this i find the Min date and Max date by using Function "Min' & "Max"
Created the relationship between the tables
Then Created 9 visuals for the report purpose.
