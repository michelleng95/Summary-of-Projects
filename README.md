# Summary-of-Projects
Below is a summary of the projects I have done, and a brief overview of what they are.


# [SQL: Technical Assessment 1](https://github.com/michelleng95/SQL-Assessment-1)
This is a technical assessment I did for a company.
I used MySQL to create the tables as per the questions, and came up with solutions to produce the outcomes requested.

# [Tableau Visualizations](https://github.com/michelleng95/Tableau-Portfolio)
Please visit my Tableau Public (https://public.tableau.com/app/profile/michelle6685) page to look at a few of my projects.

# [R: Starbucks Survey Analysis](https://github.com/michelleng95/R-Starbucks-Survey-Analysis)
## Part 1: Data Cleaning
The tab-delimited text file “starbucks final data.txt” contains survey data on a random sample of 10,000 Starbucks Coffee customers. The survey was done in Orange County, CA,


To run the dataset, please download 'starbucks final data.txt' and change the first line of the R file to where your .txt file is located. 
For example, my file is located in my Desktop >>> setwd("C:/Users/miche/Desktop")

## Part 2: Data Visualization and Regression Analysis
The cleaned Excel file “Starbucks HW2.xlsx” contains survey data on a random sample of 6,121 Starbucks Coffee customers.
Aside from creating data visualizations to better understand the relationships of data, I have performed regression analysis to identify factors that have an impact on the dependent variable of average monthly profits.

# [Alteryx: Visit Forecast](https://github.com/michelleng95/Visit-Forecast)
## Objective:
To obtain an accurate forecast of future visits using historical data.

## Sub-objectives:
Parse data and simplify data for ease of forecasting
Determine which is more accurate for forecasting - ETS or ARIMA

## Steps:
1. Import 'visits_data.yxdb'
2. Visualize raw data
3. Parse the dates and fill in null cells (option to export as another yxdb file, which is what I did here 'Forecast_ModelInput.yxdb')
4. Filter cleaned data, using first 8 years for forecasting and last year (2015) for validation
5. Using Join and TS Compare, determine which time series forecasting tool is more accurate -> ARIMA is more accurate in this case
6. Use ARIMA on the unfiltered dataset and perform TS Forecast
7. Obtained forecast of visits for the 12 months in 2016
