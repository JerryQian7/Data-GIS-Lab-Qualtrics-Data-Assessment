# Data-GIS-Lab-Qualtrics-Data-Assessment

## Qualtrics -  Merging Data

As part of my project to analyze how students use the Data & GIS Lab at Geisel Library, I was given two datasets: LibAnalytics and Qualtrics.
These two datasets originated from different entry tracking softwares, but constituted the data for lab entries over the last few years.

First, I cleaned, dropped, and seleced the correct columns from both datasets. Then I concatenated both datasets into a final working dataset and exported as a .csv file.


## Qualtrics - Cleaning and Reports

### Cleaning

This notebook analyzes all types of data from users in the Data & GIS Lab, from their major and the busiest time or week here in the lab. By combining lab statistics from LibAnalytics and Qualtrics from the past few years, the goal is to find out how to best utilize the lab for students.

Starting off from the merged data, many of the columns contain missing values, inconsistent formats, and hard-to-decipher categorization. The first portion of the notebook is dedicated to cleaning and reformatting the data.

Within my cleaning, I utilized many helper functions and packages, reformatting string patterns, creating dictionaries to help me keep track of my columns.

### Reports

In this section, I create pivot tables and graphs that show how the lab is used. Some are univariate analysis, and others combine multiple variables to look at the differences between each entry.

I assessed the missingness of each column and imputed values based on best fit, then sorted each entry into time intervals through string formatting and calendar mappings in Pandas, as well as matplotlib visualizations to analyze trends in user entry, such as popular lab times and majors, to provide insights on how to efficiently staff the lab
