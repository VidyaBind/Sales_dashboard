# Sales Dashboard (Excel)

An interactive sales dashboard built in Excel with pivot tables, pivot charts and slicers. It analyzes 2,707 orders across product categories, sales channels, countries and discount levels.

<img width="728" height="346" alt="Sales_dashboard" src="https://github.com/user-attachments/assets/a1e01ebf-6a18-423f-b57c-ec2a1e73990a" />

## Key metrics

| Metric | Value |
|---|---|
| Total revenue | $645,223 |
| Gross profit margin | 45.9% |
| COGS | $348,839 |
| Total orders | 2,707 |
| Units sold | 6,698 |

## Key insights

- **Two categories drive most of the revenue.** Camping and Hiking together make up about 59% of revenue, while Fitness contributes only about 9%.
- **Corporate is the least profitable channel.** Its gross margin is 42.1%, against 47.4% for all other channels combined (5.3 points lower).
- **Discounts cut margin.** Average gross margin falls from 52.7% with no discount to 42.0% at a 20% discount. 56% of orders carry some discount.

## What's in the dashboard

- **KPI cards:** revenue, gross profit, margin, COGS, orders and units sold
- **Monthly revenue and profit** trend
- **Top 5 countries by revenue**
- **Revenue by product category**
- **Gross margin by sales channel**
- **Discount level vs margin**
- **Revenue by region** (donut chart)
- **Country map** of revenue
- **Slicers** to filter everything by Product Category, Country and Quarter

## How to use

1. Download `sales-dashboard.xlsx`.
2. Open it in **Excel for desktop** (Windows or Mac).
3. Go to the **Dashboard** sheet and click the slicers on the right to filter every chart at once.
4. Use the **All Pivot Table** and **Sales Data** buttons at the top to jump to the underlying pivot tables and raw data.

## Workbook structure

| Sheet | Purpose |
|---|---|
| `Dashboard` | The finished, interactive dashboard |
| `Pivot table` | The pivot tables that feed each chart and KPI card |
| `Data` | The raw order-level data (2,707 rows) |

## Requirements

- Microsoft Excel (desktop). The slicers and the map chart do not work in Google Sheets or LibreOffice, and may not display in older Excel versions.

## Skills demonstrated

Pivot tables and pivot charts, calculated fields (gross margin), slicers, dashboard layout, and data storytelling.

## Data

The dataset is sample data created for this project. *(Edit this line if your data comes from another source.)*
