# Part 4: Tableau Executive Dashboard & Data Storytelling

## Business problem summary
Retail leadership needs an executive dashboard to monitor sales performance, profitability, customer segments, category performance, shipping performance, discount impact, and return patterns.

## Dataset description
- Dataset: `data/dashboard_sales_data.xlsx`
- Records: 4,200
- Date fields: `order_date`, `ship_date`
- Geographic fields: `region`, `state`, `city`
- Categorical fields: customer segment, category, sub-category, ship mode, campaign channel
- Numerical measures: sales, quantity, discount, profit, delivery days, customer rating
- Flag fields: return flag

## Tableau workbook description
The required packaged workbook file is stored at `tableau/executive_dashboard.twbx`. The screenshots and supporting documentation show the intended executive dashboard design, views, filters, and story.

**Validation note:** This environment cannot run Tableau Desktop, so the packaged workbook file is a best-effort workbook package with the dataset included. Before final submission, open the TWBX in Tableau Desktop/Public, confirm it opens correctly, and rebuild or reconnect the workbook if Tableau requires a version-specific update.

## Calculated fields created
- Profit Margin = Profit / Sales
- Cost = Sales - Profit
- Average Order Value = Sales / Number of Orders
- Return Rate = Returned Orders / Total Orders
- Shipping Delay Bucket = delivery days grouped into meaningful buckets

## Dashboard components
- Sales trend view
- Regional performance view
- Category profitability view
- Customer segment view
- Shipping performance view
- Discount vs profit view
- Return analysis view
- KPI cards for sales, profit, margin, and return rate

## Filters and interactions used
- Region filter
- Category filter
- Customer segment filter
- Date filter
- Ship mode filter
- Region selection/filter interaction to update supporting views

## Key business insights
The dashboard highlights total sales of **217,017,651.92**, total profit of **33,306,312.84**, profit margin of **15.35%**, and return rate of **4.55%**. The strongest sales region is **South**, while return and discount views highlight risks that need operational follow-up.

## Dashboard story summary
The story connects growth, profitability, customer segment performance, shipping quality, discount impact, and return risk. It is designed for leadership decision-making rather than isolated chart review.

## Assumptions and limitations
- Shipping delay bucket thresholds are business-friendly groupings created for dashboard readability.
- Return rate uses `return_flag` as the return indicator.
- The dashboard is descriptive and should be paired with operational investigation for causal decisions.
- Tableau Desktop validation is required before final GitHub submission.

## Screenshots included
- `screenshots/full_dashboard.png`
- `screenshots/sales_trend_view.png`
- `screenshots/regional_performance_view.png`
- `screenshots/category_profitability_view.png`
- `screenshots/filter_interaction_view.png`
