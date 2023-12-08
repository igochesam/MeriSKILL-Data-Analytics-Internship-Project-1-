# MeriSKILL Data Analytics Internship (Project 1)
Sales Data Analysis

## Introduction

The goal of this project is to analyse the given sales data to identify trends, top-selling products, and revenue metrics for business decision-making. This project contains a large sales dataset from which I have extracted valuable insights. It involved exploring sales trends over time, identifying the best-selling products, calculating revenue metrics such as total sales and profit margins, and creating visualizations to present my findings effectively. This project served to test my ability to manipulate and derive insights from large datasets, enabling me to make data-driven recommendations for optimizing sales strategies.

## Objective of the Analysis

The objective of this analysis is to identify trends, top-selling products, and revenue metrics from the given dataset and report findings using the appropriate media such as graphs and charts.

## Data Exploration

A quick overview of the dataset shows that it contains 185950 rows x 11 columns. I however made sure to assign the appropriate data types to the various columns. For example, the date column was assigned the DateTime format, as appropriate, and the amounts in the 'sales' and 'price each' columns were all set to two decimal places for consistency.

## Data Cleaning

In cleaning the data, I first of all checked for missing values in the dataset and fortunately, there were no missing values. Next, I noticed that the 'month' column displayed its contents using figures to represent the months of the year. I had to change this to use the names of the months instead. I extracted the months from the date column using the TEXT function. Also, no duplicate values were found after a thorough check.

## Key Findings

1. The state that brings in the highest revenue is San Francisco, very likely due to the tech market present there. New York and Los Angeles are also in this group, most likely due to their high population.
2. Apple products significantly contribute to revenue, even though they don't rank amongst the top products sold by quantity.
3. AAA and AA batters are the highest products sold by quantity, but they rank amongst the least in terms of revenue.
4. Sales are at the highest during the end of the year, particular in the months of October, November, and December, with December being the highest.
5. The [sales dashboard](https://github.com/igochesam/MeriSKILL-Data-Analytics-Internship-Project-1-/assets/109409835/bdaae6c5-49e4-43e4-86ac-a332046b2449)
 provides a summary of the key findings.


## Conclusion

The analysis reveals patterns related to seasons, cities, and products. The fact that sales are at the highest in December can be said to be because of the increased spending during the end-of-year holidays and also since brands usually release new products at that time. It is important to understand the buying patterns of customers and their preferences to do proper marketing management, especially during peak periods.

## Recommendation

It is important to take advantage of the observed peak months towards the end of the year with strategic marketing campaigns to improve sales during these periods. The products to really focus on during these periods are Apple products as they contribute hugely to revenue, even though they don't make the list of top products sold by quantity. 


