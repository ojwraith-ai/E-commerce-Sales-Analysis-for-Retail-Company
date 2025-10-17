# E-commerce-Sales-Analysis-for-Retail-Company
Extracting and reporting stakeholder satisfactory insight from dataset containing details of product sales in the US from the years 2011 through 2014.

### Project Overview
This data analysis project look to provide insights on e-commerce company's sale from 2011 through 2014. It aims to notice trends and visualize data insights from sales' performance.

#### Key Performance Indicators
1. What were the Overall Sales & Profit through the years?
2. Where the Top 5 selling products for the company?
3. What products yield the most profit? Did any product result in losses?
4. What single product sold the most quantity?
5. What is the trend of sales across the years?
6. What client made the most purchase? 

### Data Sources
The primary dataset for this analysis is from 'Ecommerce Sales Analysis.xlsx', download [here](https://docs.google.com/spreadsheets/d/1L6aBX0uNlzKiJb7JHdkNUile18s9CI4r/edit?gid=1589100670#gid=1589100670), contains detailed information on company sales between 2011 & 2014.

### Tools
- Ms Excel  (Data Cleaning & Analysis)
- Ms Powerpoint  (Data Presentation)

### Data Cleaning/Preparation
Pre-analysis stage of data readiness included;
1. Downloading the data
2. Proper inspection
3. Using filters across individual columns to remove any (blank) cells
4. Making sure there were no error cell, no missing values too

### Data Analysis
Highlighting the entire worksheet to create a new Pivot Table in a new worksheet for data manipulation

#### KPI 1
- What were the Overall Sales & Profit through the years?
  
The 'Sales' column is added to the value field area of the Pivot Table, this culminates in the entiriety of Sales for all transactions within the dataset 

In a new Pivot Table option (copy and paste the previous Pivot Table), add the 'Profit' column to the value field areato create a 'Sum of Profit' table

#### KPI 2
- Where the Top 5 selling products for the company?
  
Creating a new Pivot Table with the 'Subcategory' column in the row field area and the 'Sales' column in the value field area, this tallies individual products against their total sales

Right click the new column containing the list of products to sort them in order of 'largest to smallest' based on 'sum of sales' value

Select the 'Filter' option upon right clicking the product column, this provides a 'Top  10' value option that is predicated on the the 'Sum of Sales' values  

Adjust the suggested Top 10 to a Top 5, this returns the expected result to satisfy the KPI

#### KPI 3
- What products yield the most profit? Did any product result in losses?

In a new Pivot Table option, elect the 'Subcategory' column to satisfy the row field area, and then the 'Profit' column to be the value field.

This results in a new table that sums up the profit/loss for each product

#### KPI 4
-What single product sold the most quantity?

A pivot table with the product in rows (Subcategory) and the quantity column a a value field will yield appropriate results for this KPI

The products can be arranged from 'largest to smallest' quantity by right clicking and seelecting the option to 'Sort' based on that

The product with the highest quantity purchase top the list now

#### KPI 5
- What is the trend of sales across the years?

This would include total sales sums for the individual years

Using a new pivot table, putting up the 'Subcategory' in the row column and then the 'Sum of Sales' in the value column, a twist for this is to include the 'Year' column a a filter for this data

For a first table, set this filter to the year 2011. Set up subsequent individual tables for the years 2012, 2013, and 2014

This pulls up data for how each products' sales adjusts through the years

Next step is to set up a table that retrieves the data for individual products across every year of data
This table, has the Products in the first column and then the individual years 2011, 2012, 2013, & 2014 for the remaining columns
To fill up the roster for the values here, we would use the XLOOKUP function 
