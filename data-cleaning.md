# Data Cleaning and Preparation

## Project Overview

Data preparation was part of the team's workflow for the HR Employee Attrition Analysis project. Microsoft Excel was used for data preparation, followed by dashboard development and analysis in Power BI.

## Dataset Overview

- **Total records:** 1,470
- **Total columns:** 39, including one entirely empty column
- **Attrition cases:** 237
- **Attrition rate:** 16.12%

The dataset contains employee information such as age, department, education field, gender, job role, monthly income, job satisfaction, overtime, and years at the company.

## Data Quality Checks

An inspection of the supplied CSV identified the following:

| Check | Result |
|---|---|
| Total records | 1,470 |
| Duplicate full rows | 0 |
| Duplicate employee IDs | 0 |
| Entirely empty columns | 1 |
| Missing values in YearsWithCurrManager | Present |

## Recommended Cleaning Steps

### 1. Remove Empty Columns

Review the `Unnamed: 38` column. Since it contains no data, remove it from the analysis copy if confirmed to be unnecessary.

### 2. Handle Missing Values

Investigate missing values in `YearsWithCurrManager`. Do not automatically replace them with zero, because a missing value does not necessarily mean zero years.

### 3. Validate Data Types

Check that numerical fields, categorical fields, and employee identifiers use appropriate data types.

### 4. Validate Categories

Review category labels for fields such as `Attrition`, `Department`, `EducationField`, `Gender`, `JobRole`, and `SalarySlab` to ensure consistency.

### 5. Validate Key Metrics

Compare the cleaned data with the Power BI dashboard to confirm the employee count, attrition count, attrition rate, average age, and average years at company.

## My Contribution

My primary contribution focused on Power BI dashboard development, KPI cards, interactive slicers, and attrition analysis. Data preparation was part of the wider team's workflow.

## Notes

The data quality checks above were performed on the supplied CSV during repository preparation. They should not be described as cleaning steps originally performed by the project team unless confirmed from the original workflow.

The gender breakdown in the dashboard screenshot does not currently reconcile with the supplied CSV and requires further validation.
