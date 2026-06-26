# Chart Selection Justification - Part 4

## Sales trend view
- Question answered: How are sales and profit changing over time?
- Chart type: Line chart because time-series trends are best shown across a continuous date axis.
- Fields used: order month, sales, profit.
- Design principle: Keep time on the horizontal axis and avoid clutter.
- Mistake avoided: Did not use a pie chart for trend analysis.

## Regional performance view
- Question answered: Which regions generate the strongest sales and profit?
- Chart type: Horizontal bar chart because it ranks categories clearly.
- Fields used: region, sales, profit.
- Design principle: Sort by performance to support quick executive reading.
- Mistake avoided: Did not overload the view with too many geographic labels.

## Category profitability view
- Question answered: Which categories and sub-categories drive profit or losses?
- Chart type: Bar chart because category comparison is the main task.
- Fields used: category, sub-category, sales, profit, profit margin.
- Design principle: Emphasise profit, not just sales.
- Mistake avoided: Did not use decorative chart types that hide negative values.

## Customer segment view
- Question answered: Which customer segments contribute the most sales and profit?
- Chart type: Bar chart for direct segment comparison.
- Fields used: customer segment, sales, profit, return rate.
- Design principle: Use clear labels and consistent aggregation.
- Mistake avoided: Did not mix customer segment with unrelated dimensions in one view.

## Shipping performance view
- Question answered: How do shipping mode and delivery delay relate to performance and return risk?
- Chart type: Bar chart by shipping delay bucket.
- Fields used: delivery days, shipping delay bucket, orders, return rate.
- Design principle: Use buckets to make delivery delays business-friendly.
- Mistake avoided: Did not show every exact delivery-day value where buckets are clearer.

## Discount vs profit view
- Question answered: How does discount relate to profit?
- Chart type: Scatter plot because the dashboard needs to show relationship and spread between two numeric variables.
- Fields used: discount and profit.
- Design principle: Add a zero-profit reference line to highlight risk.
- Mistake avoided: Did not use bars for a relationship between two continuous variables.

## Return analysis view
- Question answered: Where are return patterns concentrated?
- Chart type: Bar chart by category/segment/region.
- Fields used: return flag, category, region, segment.
- Design principle: Focus attention on high-risk groups.
- Mistake avoided: Did not hide return rate behind total sales volume.

## Filters and interaction
- Filters: region, category, customer segment, date, and ship mode.
- Action interaction: Selecting a region filters trend, category, segment, shipping, and return views.
- Design principle: Interactivity supports exploration while the default view remains executive-friendly.
