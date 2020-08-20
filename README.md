# World Literacy Rates By Sex 

MAT 502 Statistical Methods

Last Modified 07/6/2020

# Problem Statement 

Which Sex, Male or Female has the highest Literacy Rate Around the World

# Requirements

Script written in R. Packages used: ``tidyverse`` ``ggplot2`` ``dplyr`` ``aov``

# Summary

The goal of this analysis is to determine which sex has the best literacy rate around the world based on country. Furthermore, we want to determine if there is any relationship between literacy rate, GDP and Unemployment.

# Data

The data set contain 125 rows representing 125 countries around the world. The data was originally 3 seperate data sets 1. Unemployment, 2. GDP, 3. Literacy Rate. The datasets were imported and meraged to create 1 dataset for analysis. There are seven columns Country, Overall Literacy Rate, Male Literacy Rate, Female Literacy Rate, Literacy Rate Differential, GDP and Employment Rate. 

<a href="https://ibb.co/84PwdjQ"><img src="https://i.ibb.co/zHPg7St/Capture.png" alt="Capture" border="0"></a>

# Results

After performing the analysis we have discovered that Females have a higher literacy rate than men around the world. I initially ran a Step AIC in both directions to determine which variables should be used in the analysis. A linear algorithm to predict which sex had the best Literacy rate. Furthermore, the model had an R-Square of 0.99 telling me that there was a strong liner relationship in my data. A t-test was then performed to determine that p-value so the null hypothesis would be accepted or rejected. T-test reveled as p-value of 0.014 below the 0.05 threshold so this told me that we should accept the null hypothesis. 


# Future Work 

Focus analysis on low income communities in the United States. Determine what can be done to improve literacy rate in those areas of the country  
