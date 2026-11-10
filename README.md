# FNP Sales Analysis Dashboard

An interactive Excel dashboard that analyzes online gifting sales for FNP. It turns 1,000 orders into insights on revenue, customer spending, delivery performance, product and category mix, seasonality, and geography.

![Dashboard Preview](images/dashboard.png)

## Objectives

- Identify which occasions, categories, and products drive revenue
- Understand seasonal and hourly demand patterns
- Measure delivery efficiency and customer spending behaviour
- Find the top-performing cities for targeted marketing and logistics

## Key Metrics

| Metric | Value |
|---|---|
| Total Orders | 1,000 |
| Total Revenue | 3,520,984 |
| Average Customer Spend | ~3,521 per order |
| Average Order-to-Delivery Time | 5.53 days |

## Key Insights

- **Occasions:** Anniversary (~670K) and Raksha Bandhan (~630K) are the top revenue occasions.
- **Categories:** Colors leads with roughly 1M in revenue, close to 28% of the total, followed by Soft Toys and Sweets.
- **Seasonality:** Revenue peaks in February (~700K) and August (~735K), with a smaller peak in November. February and August together contribute about 40% of total revenue.
- **Time of day:** Orders peak in the evening, around 7 to 8 PM.
- **Geography:** Demand is spread across tier-2 and tier-3 cities such as Imphal, Dhanbad, and Kavali.
- **Operations:** An average delivery time of 5.53 days is a risk for date-sensitive gifting.

## Recommendations

- Plan inventory and campaigns ahead of the February, August, and November peaks.
- Focus on Colors, Soft Toys, and Sweets, and review bundling for lower-performing categories.
- Schedule promotions in the evening, when buying intent is highest.
- Reduce delivery time with regional fulfilment in high-order cities.
- Increase average order value through gift bundles and add-ons.

## Dashboard Features

- KPI cards for orders, revenue, delivery time, and average spend
- Revenue by occasion, category, month, and hour of order
- Top 5 products by revenue and top 10 cities by orders
- Slicers for Occasion, Order Date, and Delivery Date

## Tools Used

- Microsoft Excel (data cleaning, pivot tables, pivot charts, slicers)

## Repository Structure

```
fnp-sales-analysis-dashboard/
├── FNP_Sales_Analysis.xlsx
├── images/
│   └── dashboard.png
├── Executive_Summary.pdf
└── README.md
```

## How to Use

1. Download `FNP_Sales_Analysis.xlsx`.
2. Open it in Microsoft Excel (2016 or later is recommended).
3. Use the slicers on the right to filter by occasion and date.

## Limitations and Next Steps

- The data covers a single year of order dates (2023), so year-on-year trends cannot be assessed.
- Planned extensions: customer segmentation, repeat-purchase analysis, and a cost and margin view.

## Author

**Shabbar**
Data Analyst | Python, SQL, Power BI, Excel

Connect with me on LinkedIn: [add your profile link here]
