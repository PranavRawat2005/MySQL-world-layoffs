# World Layoffs (2020 - 2023)

• Processed and cleaned a global layoffs dataset using CTEs for clarity, and applied advanced query techniques like temporary tables, JOIN, and subqueries for comprehensive analysis.

• Identified layoff trends and patterns using aggregate functions, HAVING filters, and conditional logic.

• Built an interactive, real-time dashboard in Power BI with DAX functions and filters for dynamic insights.

# Project Objective
To analyze global layoff trends and patterns by cleaning and processing raw data, performing exploratory data analysis, and presenting actionable insights through an interactive Power BI dashboard.

# Tools Used
* Power BI
* MySql

# Steps
   - Imported the global layoffs dataset from a csv file to MySQL server
   - Made a MySql database called layoffs
   - Made a staging table - layoffs_staging
     
 ### Data Cleaning
   - Removed the duplicates.
   - Standardized the dataset by rectifying the date format and removing inconsistencies
   - Removed the rows in which total_laid_off and percentage_laid_off were null or blank
   - Removed rows and columns which were unnecessary for our dataset.

### Exploratory Data Analysis
   - Used the aggregating functions to derive key insights.
   - Used CTEs and Temp Tables.
   - Used JOIN and WHERE functions.
     
### Dashboard
   - Connected MySQL database to Power BI desktop.
   - Performed DAX queries for manipulating the dataset.
   - Used bar charts, column charts, line chart, map graph for the visualization of dataset.
   - Inserted slicers for Date,industry,country & location,stage.
   - Inserted 2 KPI cards - Total Layoffs and Funds raised.
  

    
  
# Insights

Project Insights as of March 2023

## Year
* Layoffs were the lowest during 2021 where a total of 5,843 layoffs were registered worldwide.
* Layoffs peaked during 2022 where a staggering 92,877 layoffs were seen worldwide.
* During the 3 years, January registered the most layoffs (56,613) whereas September accumulated the least amount of layoffs (5,028).
* **Covid-19 is the most probable reason for the rise in layoffs worldwide.**


## Company
* Google had the most layoffs in this time period with a total of 12,000 employees expelled from the company.
* Meta registered the 2nd highest layoffs with a total of 11,000 employees expelled from the company.
* Amazon,Microsoft,Ericsson were 3rd,4th,5th with 10,000 , 10,000 , 8500 employees laid off respectively.
* In **India** Byju's registered the most layoffs with a total of 2,500 total layoffs.

## 
  

     

