# Boston Housing Data Analysis

## Overview
This repository contains a detailed data analysis of the Boston Housing dataset. The analysis focuses on understanding the relationships between different features and the median value of owner-occupied homes (MEDV). The dataset provides information about housing values in the suburbs of Boston.

## Data Source
The Boston Housing dataset used in this analysis can be found at the following URL:  
[https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ST0151EN-SkillsNetwork/labs/boston_housing.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ST0151EN-SkillsNetwork/labs/boston_housing.csv)

## Description of the Dataset
The Boston Housing dataset is a renowned dataset in machine learning and statistics, consisting of various features, including:

- `CRIM`: Per capita crime rate by town
- `ZN`: Proportion of residential land zoned for lots over 25,000 sq.ft.
- `INDUS`: Proportion of non-retail business acres per town
- `CHAS`: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- `NOX`: Nitric oxides concentration (parts per 10 million)
- `RM`: Average number of rooms per dwelling
- `AGE`: Proportion of owner-occupied units built prior to 1940
- `DIS`: Weighted distances to five Boston employment centres
- `RAD`: Index of accessibility to radial highways
- `TAX`: Full-value property-tax rate per $10,000
- `PTRATIO`: Pupil-teacher ratio by town
- `LSTAT`: Percentage of lower status of the population
- `MEDV`: Median value of owner-occupied homes in $1000s

## Analysis Performed

### 1. T-Test for Independent Samples
We investigated the median value differences of houses bounded by the Charles River compared to those not bounded. Our analysis found a statistically significant difference in MEDV between these two groups.

### 2. ANOVA
We examined differences in MEDV across different age groups of houses. The ANOVA test indicated significant differences in median values among these age groups.

### 3. Pearson Correlation
We analyzed the relationship between nitric oxide concentrations (NOX) and the proportion of non-retail business acres per town (INDUS). A significant correlation was found between these variables.

### 4. Regression Analysis
We assessed the impact of weighted distance to the five Boston employment centres on MEDV. The regression analysis revealed a significant relationship, suggesting that distance from employment centres influences the median value of homes.

## Conclusion
Our in-depth analysis of the Boston Housing dataset provides valuable insights into the factors influencing housing prices in Boston's suburbs, including environmental considerations, location, and historical aspects.

