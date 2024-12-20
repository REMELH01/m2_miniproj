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

Finding mean, median, and mode of the numerical columns. I will be excluding the year column from this, as it is all from the same year.

Also finding the countries with the top 10 and bottom 10 life expectancies.

## Visualization

Made 2 line plots for top 10 and bottom 10 countries life expectancies.



# 5. Analysis and Insights

## Findings

Counties with high life expectancy tend to have low infant mortality rates and low adult mortality rates. Meanwhile, the countries with the lowest life expectancy generally exhibit the opposite: high infant mortality rates and high adult mortality rates. Given this, the top 10 countries for life expectancy are Japan, Switzerland, Iceland, Italy, Australia, Spain, Sweden, France, Israel, and Canada.

## Supporting Data:

2 tables in .ipynb file to support.



# 6. Conclusion and Recommendations

## Summarize

In general, countries that have low infant and adult mortality rates have the best life expectancy. 

## Recommendations:

To find more data relating to life expectancy, continue to analyze additional columns of the .csv file. For example, by comparing countries with high vs. low BMI for life expectancy;  GDP per capita to see if countries with higher GDP have better life expectancy; and examine which countries may perform better in healthcare by analyzing data from the polio, diphtheria, or HIV columns. From there, suggestions could be made for increasing life expectancy globally.