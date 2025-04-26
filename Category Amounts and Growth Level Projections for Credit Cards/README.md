
# Credit Card Category Amounts and Growth Level Projections Analysis

This project contains data related to credit card categories, their amounts, and projections for growth levels. The goal of the project is to analyze the data, perform various tasks, and generate projections at different growth levels for the credit card categories.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Tasks](#tasks)
- [Conditional Formatting](#conditional-formatting)
- [Formulas Used](#formulas-used)
- [Charts & Visualization](#charts-visualization)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The dataset contains credit card category data along with their amounts. Projections are made based on different growth levels ranging from 10% to 40%. The analysis includes the use of dynamic arrays to calculate projections, filtering, and the application of conditional formatting for better visual representation.

## Data Description
The dataset includes the following columns:
- **ID**: Unique identifier for each record
- **Category**: The category of the credit card
- **Amount**: The amount associated with the category
- **Projected Amount**: The calculated projected amount based on growth rates

### Sample Data

| ID  | Category | Amount | Projected Amount |
| --- | -------- | ------ | ---------------- |
| 1   | Red      | 2745   | 274.50           |
| 2   | Blue     | 5498   | 549.80           |
| 3   | Blue     | 2759   | 275.90           |
| 4   | Green    | 7184   | 718.40           |
| 5   | Yellow   | 7320   | 732.00           |

## Tasks

### Task 1: Easy
- **Objective**: Fill in the Projected Amount Column by using a dynamic array to multiply the Amount column by the Growth Rate.
- **Solution**: A single formula is used in cell E15 to calculate the projected amount for each entry based on the given growth rate.

### Task 2: Medium
- **Objective**: Create a filtered version of the source table by writing a single formula. You should only return rows where the Amount is less than 4000.
- **Solution**: A single formula is used in cell G15 to filter the rows based on the condition where the amount is less than 4000.

### Task 3: Hard
- **Objective**: Create the Projections at various Growth Levels.
  - Complete the growth rate headers by writing a formula in cell M14.
  - Complete the growth projections data for the whole table using a formula in cell M15.
- **Solution**: A single formula is used to calculate the projections at various growth levels (10%, 20%, 30%, and 40%) based on the amount and growth rate.

## Conditional Formatting
- **Highlight Policy Type**: Conditional formatting is used to highlight the `Policy Type` column with red text if the policy type contains the word "PLATINUM".
- **Paid Amount**: Conditional formatting is applied to the `Paid Amount` column to visually indicate the size of amounts.
- **Gray Background for PLATINUM**: The cells from columns B to H are highlighted in grey if the policy type is "PLATINUM".

## Formulas Used
- Dynamic Arrays for Growth Projections
- Filter formula for selecting rows with amounts less than 4000

## Charts & Visualization
### Task 1: Line Chart
- **Chart 1**: A line chart is created to visualize the Cost of Acquisition (COA) over time.
  - The chart includes clear labels, titles, and axis titles for better readability.

### Task 2: Scatter Plot
- **Chart 2**: A scatter plot is created to analyze the relationship between marketing spend and the number of purchases.
  - A trend line is added for better insight into the data.

### Task 3: Scatter Plot with Weekend/Weekday Differentiation
- **Chart 3**: A 2-series scatter plot is created to compare marketing spend with the number of purchases, differentiating between weekdays and weekends.

## Contributing
Feel free to fork the repository, make changes, and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
