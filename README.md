# Sales Performance Analysis using Microsoft Excel

## Objective

Analyze retail sales data using Microsoft Excel to identify business insights related to sales, profit, customers, products, and regional performance. Build an interactive dashboard using Pivot Tables, Pivot Charts, Slicers, and Excel formulas.

## Dataset

- Dataset: Sample Superstore
- Tool Used: Microsoft Excel
- Total Records: 9,994
- Total Columns: 21

## Data Audit

### Dataset Inspection

- Reviewed the dataset structure and identified all available fields.
- Verified that the dataset contains 21 columns and 9,994 records.

### Data Display Issues

- Order Date and Ship Date initially displayed as `########`.
- Cause: Column width was insufficient to display the formatted date.
- Resolution: Adjusted the column display so the dates were visible.

### Missing Value Investigation

- Used **Go To Special → Blanks** to identify missing values.
- Found missing values in the **Postal Code** column.
- Investigated the affected records and found that all **11 Burlington, Vermont** records had missing postal codes.
- Since Postal Code is not required for the dashboard analysis, the values were left unchanged and documented.