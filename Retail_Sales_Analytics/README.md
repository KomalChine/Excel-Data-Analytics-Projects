# Retail Sales Analytics Dashboard (Excel)

## Project overview
An end-to-end Excel analytics portfolio project that explores 600 synthetic retail transactions from January–December 2025. It summarizes sales, profit, order volume, units sold, average order value, and profit margin, then compares performance by month, category, and region.

## Files
- `Retail_Sales_Analytics_Dashboard.xlsx` — formatted workbook with Dashboard, Raw_Data, Analysis, and Project_Guide sheets.
- `retail_sales_data.csv` — source dataset for reuse in Excel, Power BI, or Python.
- `README.md` — project documentation.

## How to run
1. Download or clone this repository.
2. Open `Retail_Sales_Analytics_Dashboard.xlsx` in Microsoft Excel (desktop Excel is recommended for formula recalculation and charts).
3. Start with `Project_Guide`, inspect `Raw_Data`, review formula summaries in `Analysis`, and explore the `Dashboard`.
4. Use the table filters on `Raw_Data` to inspect regions, categories, dates, and payment methods.

## Skills demonstrated
- Excel Tables and structured tabular data
- `SUMIFS`, `COUNTIFS`, `EDATE`, `IFERROR`, `COUNTA`, and `SUM`
- KPI design and dashboard layout
- Monthly, category, and regional analysis
- Column and line charts
- Data validation dropdowns, filters, and conditional formatting-ready data

## Dataset dictionary
| Field | Description |
|---|---|
| Order Date | Transaction date |
| Order ID | Unique order identifier |
| Customer | Synthetic customer name |
| Region / City | Sales geography |
| Category / Product | Product grouping and item |
| Quantity | Units sold |
| Unit Price | Selling price per unit before discount |
| Discount | Discount rate |
| Sales | Net sales after discount |
| Cost | Total product cost |
| Profit | Sales minus cost |
| Payment Method | Transaction payment type |

## Key business questions
1. Which product categories generate the most revenue and profit?
2. How does sales performance change month by month?
3. Which region contributes the most profit?
4. What is the overall average order value and profit margin?
5. Which products or regions should management investigate further?

## Notes and limitations
The data is entirely synthetic and created for educational and portfolio use. The dashboard KPI cards and charts show overall totals; the dropdowns are included as filter-control examples, while the transaction table's built-in filters provide row-level exploration. For an advanced version, add PivotTables and slicers or connect the CSV through Power Query.
