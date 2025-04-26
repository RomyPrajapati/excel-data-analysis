# Marketing Analysis Charts

This project focuses on visualizing key marketing metrics such as Cost of Acquisition (COA), Marketing Spend, and Number of Purchases over time and by weekday/weekend segmentation. The charts help in understanding spending behavior, purchasing trends, and acquisition efficiency.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Chart Tasks](#chart-tasks)
- [Formulas and Calculations](#formulas-and-calculations)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
This project analyzes and visualizes marketing data using various chart types to draw insights from trends and relationships between marketing efforts and customer purchases. Data is segmented and visualized across time and day categories to assist in strategic decision-making.

---

## Data Description

The dataset includes the following columns (relevant to this analysis):

- **Date**: The date of the data entry.
- **COA (Cost of Acquisition)**: The cost incurred to acquire one customer.
- **Marketing Spend**: Total amount spent on marketing for that date.
- **Number of Purchases**: Total number of purchases made.
- **Is Weekend**: Categorizes the date as "WEEK" or "WEEKEND" based on the day.
- **Weekday Spend/Purchases**: Filtered spend and purchases data for weekdays.
- **Weekend Spend/Purchases**: Filtered spend and purchases data for weekends.

---

## Chart Tasks

| Task | Difficulty | Chart Type | Description |
|------|------------|------------|-------------|
| Chart 1 | Easy | Line Chart | **COA Over Time**: Plotted a line chart showing Cost of Acquisition over time with proper labels, axis titles, and units. |
| Chart 2 | Medium | Scatter Chart | **Marketing Spend vs Purchases**: Plotted a scatter chart comparing marketing spend with number of purchases. Added a trendline and applied visual formatting. |
| Chart 3 | Hard | 2-Series Scatter Chart | **Marketing Spend vs Purchases – Week vs Weekend**: Categorized dates as "WEEK" or "WEEKEND". Filtered data into separate series and plotted a scatter chart to compare weekday vs weekend purchasing behavior. Used different markers/colors to distinguish both series. |

---

## Formulas and Calculations

### 1. **Is Weekend Column**
```excel
=IF(OR(WEEKDAY([@Date])=1, WEEKDAY([@Date])=7), "WEEKEND", "WEEK")

