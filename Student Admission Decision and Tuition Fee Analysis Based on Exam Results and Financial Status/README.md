# Conditional Formulas Challenge

This project involves using conditional logic in Excel to process and analyze student admissions data from a university entrance exam. The tasks include determining pass/fail status, admission eligibility, assigning course fees, and calculating total fees collected.

---

## Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Tasks & Logic Used](#tasks--logic-used)
- [Formulas](#formulas)
- [Summary](#summary)

---

## Overview

The goal is to assist university staff in automating the evaluation process for entrance exam data by applying Excel functions like `IF`, `OR`, `SWITCH`, and nested logic for fee calculation. This improves accuracy and efficiency in admissions processing and financial planning.

---

## Dataset Description

The dataset includes the following key fields:

- `Student Name`
- `Score`
- `Passing Grade`
- `Interview Superstar`
- `Major`
- `Study Term`
- `Scholarship Status` (e.g., Regular, Semi Scholarship, Finance Support)
- Calculated Fields:
  - `Student Passed`
  - `Accept Student`
  - `Fees Per Year`
  - `Total Fees Collected`

---

## Tasks & Logic Used

| Task | Difficulty | Column | Logic / Formula Used | Purpose |
|------|------------|--------|----------------------|---------|
| Task 1 | Easy | `Student Passed` | `=IF([@Score] >= [@Passing Grade], "Yes", "No")` | Identifies whether the student has passed based on score. |
| Task 2 | Medium | `Accept Student` | `=IF(OR([@Student Passed]="Yes", [@Interview Superstar]="Yes"), "Yes", "No")` | Determines admission eligibility based on exam pass or interview performance. |
| Task 3 | Medium | `Fees Per Year` | `=SWITCH([@Major], "Economics", 4000, "Finance", 3000, "Banking", 2500)` | Assigns tuition fee based on selected major. |
| Task 4 | Hard | `Total Fees Collected` | 
```excel
=IF([@Accept Student]="Yes",
    IF([@Scholarship Status]="Regular", [@Fees Per Year]*[@Study Term],
    IF([@Scholarship Status]="Semi Scholarship", [@Fees Per Year]*[@Study Term]*0.5,
    IF([@Scholarship Status]="Finance Support", [@Fees Per Year]*[@Study Term]*0.1, 0))),
0)

