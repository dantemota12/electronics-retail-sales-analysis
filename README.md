# Electronics Retail Sales Analysis (Q4 2024)
Cleaned and analyzed 753 Q4 2024 sales transactions of an electronics retailer across seven Latin American cities using Google Sheets: data standardization, KPIs, pivot tables, charts, and an executive summary with recommendations.

## Business question
Which categories, cities, and months drive sales, and where are the growth and risk areas?

## Data
753 sales transactions from Q4 2024 (orders, dates, city, product, quantity, unit price, and total amount).

## Process
- Standardized inconsistent city names (mixed casing, extra spaces, variants) with `PROPER`.
- Resolved 16 missing values in unit price and total amount.
- Validated there were no duplicate orders.
- Split product strings into category, type, and specifications.
- Calculated KPIs with `SUM`, `AVERAGE`, and `COUNT`.
- Built pivot tables by category, city, and month, plus charts.

## Key findings
- Quarterly sales: **$2.94M**, with an average transaction of **$3,911**.
- Tablets lead with **672 units sold**.
- November peaked at **$1.03M**, followed by an **11% drop** in December.
- Tulum trails Monterrey by about **90%** in sales.

## Recommendations
- Cross-sell accessories and related products with tablets.
- Review the holiday-promotion strategy to sustain December sales.
- Run a low-cost market study in Tulum before investing more.

## Tools
Google Sheets, pivot tables, charts.

## Files
- `sprint-1_proyecto-1_limpieza-y-resumen-de-datos-en-hojas-de-calculo.xlsx`: cleaned data, analysis, and executive summary.
- `images/`: screenshots of the pivot tables and charts.
- [View the Google Sheet](https://docs.google.com/spreadsheets/d/1e-iAuIjlfBlkLoXhA6lLmpZ_ShDpCwbq/edit?usp=sharing&ouid=116118350435914609784&rtpof=true&sd=true )


## Notes
Amounts are shown in the currency of the source data (not specified). The analysis covers a single quarter.
