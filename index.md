---
layout: default
title: Global Literacy Rates Analysis
---

# Global Literacy Rates Analysis

## Project Overview

This project analyzes global literacy rates using data from Our World in Data. The goal was to explore how literacy rates differ across countries, regions, and over time.

Using Python, pandas, matplotlib, seaborn, and SciPy, I investigated long-term literacy trends and created visualizations to better understand global education patterns.

---

## Research Questions

1. How have global literacy rates changed over time?
2. Which countries have the highest and lowest literacy rates?
3. How do literacy rates differ across regions?
4. Which countries experienced the largest literacy improvements over time?

---

## Global Literacy Rates Over Time (1970-2023)

![Global Literacy Trend](images/literacy_trend.png)

The positive slope (0.48) shows that global literacy rates have generally increase over time. On average, literacy has risen by about 0.48 percentage points per year.

The R² value of 0.52 suggests that time explains about half of the variation in literacy rates. This means that there is a clear upward trend overall, but it's not perfectly consistent. Other factors that may influence these results are differences between countries, gaps in data reporting, and regional inequality.

Overall, the regression supports what the graph shows. Global literacy has improved over time, but progress is uneven.

---

## Top 10 Countries With the Highest Literacy Rate

![Top 10 Highest Literacy Rate](images/10_highest.png)

sdfjs

---

## Top 10 Countries With the Lowest Literacy Rate

![Top 10 Lowest Literacy Rate](images/10_lowest.png)

sdfjslkd

---

## Literacy Rates by Region

![Literacy by Region](images/literacy_region.png)

ksdfhd

---

## Countries With Largest Literacy Improvements

![Countries Literacy Improvements](images/literacy_improvements.png)

asdkfd

---

## Key Findings

- Global literacy rates generally increased from 1970–2023.
- European countries had the highest average literacy rates.
- Several countries in Africa and Asia still face lower literacy levels.
- Bangladesh, Iran, and Nepal showed some of the largest literacy improvements over time.

---

## New Technique Used

For this project, I researched and applied linear regression using the SciPy library.

I used regression analysis to measure the overall trend in global literacy rates over time and calculate the average yearly increase in literacy rates.

This helped quantify the trend rather than only visually interpreting it from the graph.

---

## Data Source

- Our World in Data Literacy Dataset
- https://ourworldindata.org/literacy

---

## Project Files

- [View Colab Notebook](./Final%20Project/YOUR_NOTEBOOK_NAME.ipynb)
- [View Dataset](./Final%20Project/global_literacy_rates.csv)

---

## Reflection

One challenge in this project was dealing with missing and inconsistent yearly data across countries. Different countries reported literacy data in different years, which made direct comparisons more difficult.

If I had more time, I would expand this project by incorporating additional datasets such as GDP, education spending, or school enrollment to better understand what factors most influence literacy rates.