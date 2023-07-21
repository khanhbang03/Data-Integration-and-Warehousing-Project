# Data-Integration-and-Warehousing-Project
Steps of the project:
1.	Create two databases, “GroupOP” and “GroupDW”
2.	Import data from the excel file “global_superstore.xls” to the table “Orders” in database “GroupOP”
3.	Create data warehouse tables as per the excel file “DW Design” in database “GroupDW”
4.	Create staging tables/tables as per your design in database “GroupDW”
5.	Populate table “DIM_Calendar” for 5 years, from 1-Jan-2011 to 3-Dec-2015.
6.	Write ETL scripts to transfer data from the staging table to the data warehouse tables.
7. Perform 5 cycles of ETL (Extract, Transform, Load), with each cycle taking a specific time period based on the "Shipping Date":
  a. Cycle 1: "Shipping Date" from 1-Jan-2011 to 31-Dec-2011
  b. Cycle 2: "Shipping Date" from 1-Jan-2012 to 31-Dec-2012
  c. Cycle 3: "Shipping Date" from 1-Jan-2013 to 31-Dec-2013
  d. Cycle 4: "Shipping Date" from 1-Jan-2014 to 31-Dec-2014
  e. Cycle 5: "Shipping Date" from 1-Jan-2015 to 31-Dec-2015
8. Create pivot table from the DW data
9. From pivot table, find out year-wise average “Response” for each country.
