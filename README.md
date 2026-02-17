# 📊 Page View Time Series Visualizer

## Overview

This project analyzes time series data from the freeCodeCamp forum, tracking daily page views from May 2016 to December 2019.

The objective is to explore long-term growth trends, yearly comparisons, and seasonal patterns using structured data analysis and visualization techniques in Python.

---

## Dataset

The dataset contains:

- `date` — Daily timestamp
- `value` — Number of page views

To improve analytical accuracy, extreme outliers were removed by excluding values below the 2.5th percentile and above the 97.5th percentile.

---

## Visualizations

### 1. Line Plot — Overall Growth Trend
A time series line chart showing daily page views over the full date range.

- Title: **Daily freeCodeCamp Forum Page Views 5/2016-12/2019**
- X-axis: Date
- Y-axis: Page Views

Purpose:
- Identify overall growth trend
- Observe long-term engagement patterns

---

### 2. Bar Plot — Yearly and Monthly Comparison
A grouped bar chart displaying average daily page views per month, grouped by year.

- X-axis: Years
- Y-axis: Average Page Views
- Legend: Months

Purpose:
- Compare yearly performance
- Identify seasonal traffic trends

---

### 3. Box Plots — Distribution & Seasonality

Two adjacent box plots:

**Year-wise Box Plot (Trend)**
- Shows distribution of page views for each year

**Month-wise Box Plot (Seasonality)**
- Shows distribution across months (Jan–Dec)

Purpose:
- Analyze variability
- Identify seasonality
- Detect changes in distribution over time

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

## Project Structure

