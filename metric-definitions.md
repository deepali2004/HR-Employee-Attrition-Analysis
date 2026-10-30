# KPI Definitions

This document records the values shown on the dashboard. Confirm the original DAX or calculation logic before marking the definitions as verified.

| KPI | Displayed value | Definition to verify |
|---|---:|---|
| Employee count | 1,470 | Is this a row count or distinct employee count? |
| Attrition count | 237 | Confirm the filter used to identify employees who left. |
| Attrition rate | 16.1% | Likely attrition count divided by employee count; verify numerator and denominator. |
| Average age | 36.92 | Confirm age field and filters. |
| Average salary | 6.50K | Confirm income field, unit, and filters. |
| Average years at company | 7.01 | Confirm tenure field and filters. |

## Category Definitions to Verify

- **Age groups:** The screenshot shows 18–25, 26–35, 36–45, 46–55, and 55+; verify boundaries and whether the final group is 55+ or 56+.
- **Salary slabs:** The screenshot shows up to 5k, 5k–10k, 10k–15k, and 15k+; verify whether boundary values overlap.
- **Years at company:** Confirm whether the chart uses exact tenure values or grouped categories.

## Validation

- [ ] Compare every measure with the original Power BI report.
- [ ] Confirm whether slicers affect the KPI cards.
- [ ] Confirm units, currency, rounding, and filter context.
- [ ] Test the attrition-rate calculation against the underlying data.
