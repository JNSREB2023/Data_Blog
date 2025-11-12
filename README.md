# Data Acquisition Blog
Repository for blog project assignment. Studying 1000 colleges in America and influences on graduation rates.

## Data File

The data file includes four different .csv files:

1. cleaned_popdata.csv : This data set is the cleaned version of the xslm file downloaded from the U.S. Department of Commerce. This file has four columns States, State_Abbrev, April_Estimate_2020, July_Estimate_2024 explaining population estimates for each state. 

2. college_scorecard_subset.csv : This is an uncleaned version of the data aquired from the College Scorecard API. This includes 1,000 observations of college data.

3. college_state_pop.csv : This the final merged data including data from the college_scorecard_subset.csv and cleaned_popdata.csv, this is the file that will be used in the analysis.

4. NST-EST2024-HU-CUMCHG.csv : This is the raw file converted from an excel file to csv format from the United States Census Bureau about population data. 

## Jupyter Notebook Information

- dataset_code.ipynb : This file is the code for aquiring the data from the API and code to clean the data sets, merge, and add additional columns for analysis purposes.
- EDA.ipynb : This is the exploratory data analysis for the data that uses the college_state_pop.csv.



### Data Sources: 
U.S. Department of Education, College Scorecard Data via the College Scorecard API (https://collegescorecard.ed.gov/data/)

U.S. Department of Commerce, United States Census Bureau (https://www.census.gov/data/tables/time-series/demo/popest/2020s-total-housing-units.html)


## Disclaimers:

This analysis uses the Census Bureau Data API but is not endorsed or certified by the Census Bureau.

This analysis uses the U.S. Department of Commerce data but is not endorsed or certified by the Census Bureau.

