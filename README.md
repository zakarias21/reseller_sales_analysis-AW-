# Sales Territory Performance (AdventureWorks Reseller Sales)

This project analyzes **which sales territories perform best over the last two years of Reseller Sales?** in the AdventureWorks Reseller Sales dataset.

This project answers that directly with:
1. A territory ranking by total reseller sales (primary KPI).
2. Supporting metrics that explain *why* a territory performs well.

## What’s Included
- **Territory Sales Ranking**  
  Direct answer to the question using total sales and rank.

- **Profit Margin by Territory**  
  Correctly aggregated margin using total sales vs total product cost.

- **Average Order Value (AOV)**  
  Calculated at the order level (not reseller level) for accurate averaging.

- **Active Reseller Depth**  
  Count of active resellers and average active span in months.

- **Top Products per Territory**  
  Ranked products by revenue within each territory.

- **Repeat Purchase Rate**  
  Shows reseller loyalty within the 2‑year window.

- **Year‑over‑Year Retention Rate**  
  Retention aligned to the actual last two years in the dataset (no hardcoded years).

## How to Use
1. Load the AdventureWorks DW tables (FactResellerSales, DimSalesTerritory, DimDate, DimProduct, DimReseller).
2. Run the SQL files in order.
3. Use the Territory Sales Ranking as the primary answer, and the other queries as evidence and context.

## Key Outcome
A ranked list of top‑performing sales territories for the last two years, with supporting evidence on profitability, order quality, customer loyalty, and product drivers.
