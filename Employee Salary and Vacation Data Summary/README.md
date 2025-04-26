# Employee Salary and Vacation Data Summary

This project focuses on managing and analyzing employee salary, overtime, vacation, and non-work days data. The goal is to calculate key metrics like vacation pay, non-work days, and provide summary statistics for better reporting.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Tasks](#tasks)
- [Formulas Used](#formulas-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The project analyzes employee salary and vacation-related data, and the following key objectives are addressed:
- Calculate vacation pay based on vacation days and salary.
- Calculate non-work days by adding days missed and vacation days.
- Summarize key statistics such as total non-work days and average vacation pay.

## Data Description
The dataset includes the following columns:
- **Employee ID**: Unique identifier for each employee.
- **Salary**: The salary of the employee.
- **DaysMissed**: The number of days the employee missed work.
- **DaysVacation**: The number of vacation days taken by the employee.
- **Overtime**: The overtime pay (if any).
- **Vacation Pay**: The total pay received for vacation days.
- **Non Work Days**: The total number of non-working days, including missed and vacation days.

### Sample Data

| Employee ID | Salary  | DaysMissed | DaysVacation | Overtime | Vacation Pay | Non Work Days |
|-------------|---------|------------|--------------|----------|--------------|---------------|
| 1           | 50000   | 2          | 5            | 1000     | 1250         | 7             |
| 2           | 60000   | 3          | 4            | 1500     | 1200         | 7             |
| 3           | 45000   | 1          | 10           | 800      | 2250         | 11            |

## Tasks

### Task 1: Easy
- **Objective**: Fill in the values for the [Non Work Days] column by adding [DaysMissed] and [DaysVacation].
- **Solution**: A simple formula adds the missed days and vacation days to calculate the total non-work days:
  ```excel
  = [DaysMissed] + [DaysVacation]

