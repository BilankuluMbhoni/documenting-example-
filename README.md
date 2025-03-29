# E-Commerce Sales Analysis

## Table of contents 

- [Project-Overview](#Project-Overview)
- [Data-Source](#Data-Source)
- [Tools](#Tools).
- [Data-Cleaning-Preparation](#Data-Cleaning-Preparation)
- [Exploratory-Data-Analysis](#Exploratory-Data-Analysis)
-  [ Data-Analysis](#Data-Analysis)
- [Results/findings ](#Results/findings)
- [Recommendations](#Recommendations)
-  [limitations](#limitations)

## Project Overview 
This Data Analysis project Aims to provide insights into the sales performance of an e-commerce company over the past year. By analyxing various aspects of the sales data, we seek to identify trends , make data-driven  recomendation, and gain a deeper understanding of the company's performance 

## Data Source
Sales Data: The primary dataset used for this analysis is the "sales_data.csv" file, containing detailed information about each sale by the company 

## Tools 
  - Excel - Data Cleaning 
  - SQL Server - Data Analysis
  - PowerBi - Creating Report
    
## Data Cleaning/Preparation 

In the Initial data preparation Phase, We performed the following task: 
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and Formating.

## Exploratory Data Analysis 

1. What is overall sales trend?
2. which products are top sellers?
3. what are the peak sales period?

   ## Data Analysis 

include some  interesting code

``` sql
Select * FROM table1
WHERE COND = 2;
```
## Results/findings 

The analysis results are summarised as follows :
- The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
- product Catergory a is the  best-performing catergory in terms of sales and revenue.
- customer segments with high lifetime  value (LTV) should be targeted for markrting efforts .

## Recommendations 
  Based on the analysis, we recommend the following actions:
    - Invest in marketing and promotions During peak seasons to maximize revenue.
    - focus on expanding and promoting products in Catergory 4 
    - implement a customer segmentation strategy to target high-ltv customers effectively 

 ## limitations
I Had to remove all zero values from budget and revenue columns because they would have effected the accurancy of my conclusions from the analysis. there are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue 

