This is a mini project for utilizing Pandas and Matplotlib for Data Analysis. 

Part of completing Data Analytics course for Code:You.

# 1. Project Overview 

Objective: Analyze which countries have the best life expectancy.

Data source: Data comes from https://www.kaggle.com/datasets/shreyasg23/life-expectancy-averaged-dataset and has several different datapoints from 179 unique values.

# 2. Data Collection and Loading

In .ipynb file as shown.

# 3. Data Cleaning and Preparation 

## Handle missing files: 

I will be marking any empty numbers as 'Unknown' instead of dropping them because of the other data present in the table.

## Data Type Adjustments: 

Adjusting columns that have decimals to only having 2 decimal places, converting the column 'Year' to an int, and converting the columns 'Country' and 'Region" as categories.

## Feature Engineering: 

I will make a category that will tell if a country has high, medium, or low life expectancy. 

### Defining these:
High: Life expectancy > 70 years. 
Medium: Life expectancy is between 50 and 70 years. 
Low: Life expectancy is < 50 years. 

# 4. Exploratory Data Analysis (EDA)

## Descriptive Statistics