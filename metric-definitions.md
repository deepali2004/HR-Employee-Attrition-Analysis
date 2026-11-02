# KPI Definitions and Data Validation

## Overview

This document defines the key performance indicators displayed in the HR Attrition Analysis dashboard and records validation checks against the supplied dataset.

## KPI Summary

| KPI | Value | Definition |
|---|---:|---|
| Employee Count | 1,470 | Total employee records |
| Attrition Count | 237 | Employees whose attrition status is Yes |
| Attrition Rate | 16.12% | Attrition count divided by total employee records |
| Average Age | 36.92 | Mean employee age |
| Average Monthly Income | Approximately 6.50K | Mean monthly income; confirm currency and units |
| Average Years at Company | 7.01 | Mean employee tenure at the company |

## Attrition Rate Calculation

Attrition Rate = (Employees with Attrition = Yes / Total Employees) × 100

Using the supplied dataset:

Attrition Rate = (237 / 1,470) × 100 = 16.12%

## Data Validation

The supplied CSV agrees with the dashboard on the following metrics:

- Total employee records
- Attrition count
- Overall attrition rate
- Average age
- Average years at company

The average monthly income is also consistent with the displayed value of approximately 6.50K. The exact unit and currency should be confirmed.

## Gender Chart Discrepancy

The supplied dataset contains:

| Gender | Attrition Count |
|---|---:|
| Male | 150 |
| Female | 87 |
| Total | 237 |

The dashboard screenshot appears to show 140 male and 79 female attrition cases, totaling 219.

This discrepancy requires investigation. Possible explanations include visual-level filters, different filter contexts, or a difference between the screenshot and the supplied dataset.

Do not treat the gender chart as reconciled until the original Power BI report has been checked.

## Validation Checklist

- [ ] Verify the DAX measures in the original Power BI report.
- [ ] Check page-level, visual-level, and slicer filters.
- [ ] Confirm the salary unit and currency.
- [ ] Reconcile the gender chart with the source dataset.
- [ ] Confirm all KPI values after applying the intended filters.
