# Credit Card Reward Data Analysis

This project focuses on analyzing credit card rewards, including total cash back rewards, cash back amounts by credit card type, and total sign-up bonuses paid. The project uses formulas and logical functions to calculate these rewards based on various criteria, including card type, cash back rates, and sign-up bonus criteria.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Tasks](#tasks)
- [Formulas Used](#formulas-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to analyze credit card spending and rewards data. Using SUMPRODUCT and conditional formulas, we calculate:
- The total cash back earned across all credit card transactions.
- The cash back earned by each card type.
- The total sign-up bonus paid to cardholders who meet the necessary criteria.

## Data Description
The dataset contains the following columns:
- **ID**: Unique identifier for each record.
- **Credit Card**: The name of the credit card.
- **Total Spend**: The total spend on the credit card.
- **Cashback Reward %**: The cash back reward percentage associated with the card.
- **Sign Up Bonus Criteria 1, 2, 3**: The conditions for receiving the sign-up bonus.
- **Sign Up Bonus Cut Off Date**: The deadline by which the criteria must be met.
- **Total Cash Back Reward Paid**: The total amount of cash back reward paid.

### Sample Data

| ID  | Credit Card      | Total Spend | Cashback Reward % | Sign Up Bonus Criteria 1 | Sign Up Bonus Criteria 2 | Sign Up Bonus Criteria 3 | Sign Up Bonus Criteria Met By | Sign Up Bonus Cut Off Date | Total Cash Back Reward Paid |
| --- | ---------------- | ----------- | ----------------- | ------------------------ | ------------------------ | ------------------------ | ----------------------------- | ------------------------- | --------------------------- |
| 1   | Travel Master    | 400         | 1.0%              | null                     | null                     | null                     | 31 Dec 2022                 |                           |                             |
| 2   | Travel Master    | 200         | 1.3%              | MET                      | null                     | MET                      |                             |                           |                             |
| 3   | Travel Master    | 300         | 1.9%              | null                     | null                     | null                     |                             |                           |                             |

## Tasks

### Task 1: Easy
- **Objective**: Complete the [Total Cash Back] calculation using a single SUMPRODUCT formula.
- **Solution**: A SUMPRODUCT formula calculates the total cash back reward by multiplying the total spend by the cashback reward percentage for all cardholders.

### Task 2: Medium
- **Objective**: Complete the [Cash Back Amounts By Credit Card Type] calculations using a conditional SUMPRODUCT formula.
- **Solution**: A conditional SUMPRODUCT formula is used to calculate the cash back amount for each credit card type, based on specific conditions (e.g., the type of card).

### Task 3: Hard
- **Objective**: Complete the [Total Sign Up Bonus Paid] calculation.
- **Solution**: A SUM function is used to calculate the total sign-up bonuses paid, adding up the bonuses for all cardholders who meet the criteria.

## Formulas Used
### Total Cash Back Calculation
- **Formula**: 
  ```excel
  =SUMPRODUCT([Amount Spent Range], [Cash Back Rate Range])

