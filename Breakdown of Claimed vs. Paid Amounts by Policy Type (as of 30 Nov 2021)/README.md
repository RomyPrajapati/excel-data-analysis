# Insurance Policy Claims Analysis

## Overview
This dataset contains details of various insurance policies, including the policy holder's information, the policy type, policy expiration, and claims associated with each policy. The focus is on the **Claimed Amount** and **Paid Amount**, highlighting the differences between them.

---

## Data Description

| ID | Policy ID | Policy Holder | Policy Type | Policy Expiry | Deductible ($) | Max Policy Coverage | Claimed Amount | Paid Amount |
|----|-----------|---------------|-------------|---------------|----------------|---------------------|----------------|-------------|
| 1  | X273      | Name          | PLATINUM    | 30 Nov 2021   | 100            | 10,000              | 12,000         | 10,000      |
| 2  | XNN3      | Name          | GOLD        | 30 Nov 2021   | 100            | 10,000              | 10,000         | 2,000       |
| 3  | X882      | Name          | GOLD        | 30 Nov 2021   | 100            | 10,000              | 10,000         | 10,000      |
| 4  | X928      | Name          | GOLD        | 30 Nov 2021   | 100            | 8,000               | 10,000         | 2,000       |
| 5  | X277      | Name          | SILVER      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 4,000       |
| 6  | X292      | Name          | BRONZE      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 8,000       |
| 7  | X983      | Name          | PLATINUM    | 30 Nov 2021   | 100            | 10,000              | 10,000         | 3,000       |
| 8  | X827      | Name          | BRONZE      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 4,000       |
| 9  | X763      | Name          | SILVER      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 2,000       |
| 10 | X336      | Name          | PLATINUM    | 30 Nov 2021   | 100            | 10,000              | 10,000         | 6,000       |
| 11 | X334      | Name          | PLATINUM    | 30 Nov 2021   | 100            | 10,000              | 10,000         | 8,000       |
| 12 | X337      | Name          | BRONZE      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 10,000      |
| 13 | X884      | Name          | GOLD        | 30 Nov 2021   | 100            | 10,000              | 10,000         | 8,000       |
| 14 | X992      | Name          | GOLD        | 30 Nov 2021   | 100            | 10,000              | 10,000         | 3,000       |
| 15 | X736      | Name          | GOLD        | 30 Nov 2021   | 100            | 10,000              | 10,000         | 200         |
| 16 | X912      | Name          | SILVER      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 2,000       |
| 17 | X112      | Name          | SILVER      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 3,000       |
| 18 | X224      | Name          | BRONZE      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 6,000       |
| 19 | X247      | Name          | BRONZE      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 7,000       |
| 20 | X239      | Name          | BRONZE      | 30 Nov 2021   | 100            | 10,000              | 10,000         | 9,000       |

---

## Conditional Formatting Rules

1. **Highlight Policy Type (PLATINUM) in Red**  
   - **Policy Type Column:** All cells that contain "PLATINUM" are highlighted in **red text** to quickly identify premium policies.
   
2. **Highlight Paid Amounts Based on Value**  
   - A color scale is applied to the **Paid Amount** column to visually represent the size of the paid amounts, with higher amounts appearing in **darker colors**.

3. **Grey Background for PLATINUM Policies**  
   - **Columns B-H (Policy ID to Paid Amount)**: These columns are highlighted in **grey** for all policies where the policy type is "PLATINUM".

---

## Features

- **Data Analysis & Visualization**: This dataset can be analyzed to evaluate claim trends, paid amount distribution, and policy type impacts.
- **Conditional Formatting**: Provides visual representation to enhance analysis of the claims, payments, and policy details.
- **Easy-to-use Spreadsheet**: Suitable for insurance claim analysis, payment verification, and policy analysis.

---

## How to Use

1. **Download the Excel File**: You can download the data file from the repository.
2. **Open in Excel**: All conditional formatting and formulas should automatically be applied when you open the file in Excel.
3. **Analyze**: You can use the data for further analysis on insurance claims, claims processing, or policy payout modeling.

---

## Tools Used

- **Microsoft Excel**: For data entry, formatting, and conditional formatting.
- **GitHub**: For version control and easy sharing of the portfolio.

---

## License
This repository is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

