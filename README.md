# Adidas Sales Analysis
<img src="adidas-logo.png" width="400">
Sales performance analysis of Adidas products sold across major U.S. retailers, covering **January 2020 – December 2021**.

## File

`Adidas-Sales-Analysis.xlsx`

## Sheets

| Sheet | Contents |
|---|---|
| **Dashboard** | Summary dashboard view pulling together the key charts from the analysis sheets below |
| **Data** | The raw sales dataset — 9,648 transaction records |
| **Retailers(Sales vs Profit)** | Chart/table comparing total sales vs. operating profit by retailer |
| **Sales Method** | Chart/table breaking down sales by channel (In-store, Outlet, Online) |
| **Sales Regions** | Table of sales performance by U.S. region and state |
| **Sales Trend** | Chart/table of sales trend over time |
| **Sheet1** | Supporting data extract used to feed the charts above |

## Data Dictionary (Data sheet)

| Column | Description |
|---|---|
| Retailer | Retail chain that sold the product (Foot Locker, Walmart, Sports Direct, West Gear, Kohl's, Amazon) |
| Retailer ID | Unique identifier for the retailer account |
| Invoice Date | Date of the sale |
| Region | U.S. sales region (Northeast, South, West, Midwest, Southeast) |
| State | U.S. state of sale |
| City | City of sale |
| Product | Product category (Men's/Women's Street Footwear, Athletic Footwear, Apparel) |
| Price per Unit | Selling price per unit ($) |
| Units Sold | Number of units sold |
| Total Sales | Units Sold × Price per Unit ($) |
| Operating Profit | Profit generated from the sale ($) |
| Operating Margin | Operating Profit ÷ Total Sales (%) |
| Sales Method | Channel of sale (In-store, Outlet, Online) |

## Key Stats

- **Records:** 9,648 transactions
- **Date range:** Jan 1, 2020 – Dec 31, 2021
- **Retailers:** 6 (Foot Locker, Walmart, Sports Direct, West Gear, Kohl's, Amazon)
- **Regions / States:** 5 regions, 50 states
- **Product categories:** 6
- **Sales channels:** 3 (In-store, Outlet, Online)
- **Total Sales:** ~$899.9M
- **Total Operating Profit:** ~$332.1M

## How to Use

1. Open the **Dashboard** sheet for a high-level visual summary.
2. Drill into the individual analysis sheets (Retailers, Sales Method, Sales Regions, Sales Trend) for the underlying charts and tables.
3. Refer to the **Data** sheet for the full raw transaction log if you need to build custom pivot tables or run further analysis.
