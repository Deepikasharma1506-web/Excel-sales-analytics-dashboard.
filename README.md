# Sales Analytics Dashboard (Excel)

## Overview
End-to-end Excel portfolio project using a synthetic 2025 sales dataset. Includes raw data, cleaned data, calculated metrics, summary tables, KPI cards, and charts.

## Business questions
- What are total revenue, estimated profit, and profit margin?
- Which regions and categories contribute most?
- How do monthly revenue and profit trend?
- Which products generate the most revenue?
- How do KPI cards change by region?

## Dataset
600 synthetic sales orders across 2025; currency is INR. This is practice data, not real company data.

## Data cleaning
- Missing City values replaced with `Unknown` in Clean_Data.
- Leading/trailing spaces removed from text fields.
- Original raw data preserved in Raw_Data.
- Revenue recalculated as `Quantity × Unit_Price_INR × (1 - Discount_Rate)`.
- Profit recalculated as `Calculated_Revenue - Estimated_Cost_INR`.
- Profit margin calculated as `Calculated_Profit / Calculated_Revenue`.

## Workbook tabs
- `Dashboard`: KPI cards and charts; select region in B4.
- `Raw_Data`: original data.
- `Clean_Data`: cleaned records and calculated measures.
- `Analysis`: formula-driven chart source tables.
- `Data_Dictionary`: field definitions.
- `Start_Here`: usage guide.

## Tools
Microsoft Excel, Excel Tables, formulas, data validation, charts, conditional formatting.

## Limitations
Synthetic practice data. Costs are estimated. The region selector filters KPI cards; charts display overall dataset summaries.

## How to use
Open `workbook/Sales_Analytics_Dashboard.xlsx` in Excel and allow formulas to recalculate. On Dashboard, change cell B4 to All, North, South, East, or West.
