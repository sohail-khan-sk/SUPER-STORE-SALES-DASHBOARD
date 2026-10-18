# Super Store Sales Dashboard & 15-Day Forecast

An interactive Power BI dashboard that analyzes Super Store sales (2019–2020), compares year-over-year trends, and forecasts the next 15 days of sales.

## Overview

| KPI | Value |
|---|---|
| Sales | $1.57M |
| Quantity | 22K units |
| Profit | $175.26K (about 11.2% margin) |
| Avg delivery time | 3.93 days |

## Objectives

- Analyze sales and profit over time using time series techniques
- Find the products, regions, customer segments and shipping/payment habits that drive performance
- Forecast short-term (15-day) sales to support planning
- Provide an interactive dashboard with a Region slicer (Central, East, South, West)

## Dashboard Pages

**1. Super Store Sales Dashboard**
- KPI cards: Sales, Quantity, Profit, Avg Delivery Days
- Map of sales and profit by state
- Sales by Category, Sub-Category and Ship Mode
- Sales by Segment and Payment Mode
- Monthly Sales and Monthly Profit, 2019 vs 2020

**2. 15 Days Forecast of SuperStore Sales**
- Daily sales history (Jan 2019 to Dec 2020)
- Detailed 15-day forecast with confidence band
- Top 10 states by sales

## Key Insights

- 2020 sales and profit were higher than 2019 in every month, with the strongest months from September to December.
- Office Supplies is the top category (0.64M); Phones, Chairs and Binders are the top sub-categories.
- California (0.34M), New York (0.19M) and Texas (0.12M) account for about 41% of sales.
- Consumers make up 48% of sales; Standard Class is the most used shipping mode and Cash on Delivery the most used payment mode (43%).
- Daily sales are very volatile, so the 15-day forecast is best read as the expected average level, with a wide confidence band.

## Tools Used

- Microsoft Power BI Desktop (DAX, Power Query, built-in forecasting)
- Time series analysis (year-over-year comparison, trend and seasonality, 15-day forecast)

## Repository Structure

```
super-store-sales-dashboard/
├── README.md
├── Sales_Dashboard.pbix        # Power BI file
├── Sales_Dashboard.pdf         # Exported dashboard
├── data/                       # Dataset (or a link to its source)
└── images/
    ├── dashboard.png
    └── forecast.png
```

## How to Use

1. Download or clone this repository.
2. Open `Sales_Dashboard.pbix` in Power BI Desktop (free for Windows).
3. Use the Region slicer to filter all visuals.
4. Open the forecast page to see the 15-day outlook.


## Future Improvements

- Validate forecast accuracy on held-out days (MAPE / RMSE)
- Compare with Prophet or SARIMA models
- Add profit by category and state views
- Add weekly and region-level forecasts

## Author

Sohail Khan | [LinkedIn](https://linkedin.com/in/sohail-k19/) | [GitHub](https://github.com/sohail-khan-sk)
