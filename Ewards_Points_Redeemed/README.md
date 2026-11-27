# Python-Based Ewards Points Redeemed Report Automation

## Project Overview
This project automates outlet-wise Ewards Points Redeemed reporting using Python, Pandas, and OpenPyXL. It processes customer transaction data to summarize redeemed points and rank outlets based on redemption activity.

## Business Analysis
- **Outlet-Wise Summary:** Calculates total Ewards points redeemed by each restaurant.
- **Outlet Ranking:** Ranks outlets from highest to lowest points redeemed.
- **Invoice-Level Deduplication:** Removes repeated invoice entries before aggregation to avoid counting the same redeemed points multiple times.
- **Redemption Overview:** Calculates the grand total of redeemed points across outlets.

## Key Features
- Restaurant-wise points aggregation.
- Ranking of outlets by redeemed points.
- Invoice-level duplicate handling.
- Top 10 outlets chart.
- Conditional formatting for comparison.
- Raw data sheet.

## Tools Used
- Python
- Pandas
- OpenPyXL

## Output
Generates a formatted Excel workbook containing:
1. Ewards Points Redeemed Summary
2. Raw Data

## Conclusion
This automation provides a clear overview of outlet-wise loyalty point redemption activity and supports monitoring of customer rewards usage across restaurants.
