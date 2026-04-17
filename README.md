# uk-income-inequality-analysis_python
Python analysis of UK household income data, exploring income distribution and inequality trends using pandas and matplotlib.

# UK Household Income Analysis (Python)

## Overview

This project analyses UK household income trends using data from the Office for National Statistics (ONS). The focus is on income distribution and inequality over time.

The analysis was conducted using Python, with pandas for data manipulation and matplotlib for visualisation.

## Objectives

* Analyse income distribution across household quartiles
* Measure inequality using income gap and ratio metrics
* Explore how income inequality has changed over time

## Data Source

Office for National Statistics (ONS):
"Effects of Taxes and Benefits on Household Income"

## Process

The project involved several key steps:

* Loading data from Excel into Python
* Cleaning and standardising column names and data types
* Handling inconsistent time formats (e.g. financial years)
* Removing duplicate rows caused by non-essential variables
* Creating new variables to measure inequality:

  * Income gap (top quartile – bottom quartile)
  * Income ratio (top quartile / bottom quartile)

## Visualisations

The following visualisations were created:

* Income gap over time
* Top vs bottom quartile income trends
* Income ratio over time

These charts highlight trends in income distribution and provide insight into changes in inequality.

## Key Insights

* There is a persistent gap between higher and lower income households
* Income inequality varies over time rather than following a consistent trend
* The ratio between top and bottom quartiles highlights sustained differences in income levels

## Tools Used

* Python
* pandas
* matplotlib

## Example Output

<img width="793" height="600" alt="image" src="https://github.com/user-attachments/assets/dec4c4ee-a9d7-4069-83c1-112589dc65cf" />
<img width="781" height="603" alt="image" src="https://github.com/user-attachments/assets/d39bd00b-05d6-4f75-b91c-59f2e1466dba" />
<img width="745" height="593" alt="image" src="https://github.com/user-attachments/assets/2e06fab8-9e52-4307-a61c-2098dda8ce2b" />

## File

* `uk_income_analysis.ipynb` – full analysis notebook
