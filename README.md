# MeriSKILL Data Analytics Internship (Project 1)
Sales Data Analysis

## Introduction

The goal of this project is to analyse the given sales data to identify trends, top-selling products, and revenue metrics for business decision-making. This project contains a large sales dataset from which I have extracted valuable insights. It involved exploring sales trends over time, identifying the best-selling products, calculating revenue metrics such as total sales and profit margins, and creating visualizations to effectively present my findings. This project served to test my ability to manipulate and derive insights from large datasets, enabling me to make data-driven recommendations for optimizing sales strategies.

## Objective of the Analysis

The objective of this analysis is to identify trends, top-selling products, and revenue metrics from the given dataset and report findings using the appropriate media such as graphs and charts.

## Data Exploration

A quick overview of the dataset shows that it contains 185950 rows x 11 columns. I however made sure to assign the appropriate data types to the various columns. For example, the date column was assigned the datetime format, as appropriate, and the amounts in the 'sales' and 'price each' columns were all set to two decimal places for consistency.

## Data Cleaning

In cleaning the data, I first of all checked for missing values in the dataset and fortunately, there were no missing values. Next, I noticed that the 'month' column displayed its contents using figures to represent the months of the year. I had to change this to use the names of the months instead. I did this by extracting the months from the date column using the TEXT function. Also, no duplicate values were found after a thorough check.


