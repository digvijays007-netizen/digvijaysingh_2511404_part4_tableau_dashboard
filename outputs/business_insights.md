# Business Insights - Part 4 Tableau Dashboard

## Calculated fields created
- Profit Margin = Profit / Sales
- Cost = Sales - Profit
- Average Order Value = Sales / Number of Orders
- Return Rate = Returned Orders / Total Orders
- Shipping Delay Bucket = delivery days grouped into 0-2, 3-5, 6-8, and 9+ day buckets

## Insight 1: Sales trend
Observation: Peak monthly sales occur in **2025-08**.

Data evidence: Monthly sales reach **10,861,499.92** with profit of **1,735,384.80**.

Business interpretation: Leadership should understand what campaigns, categories, or seasonal patterns drove this peak.

Recommended action: Compare peak-month product mix and campaign channels against lower months.

## Insight 2: Regional performance
Observation: **South** is the strongest sales region.

Data evidence: Regional sales total **64,693,706.73** and profit totals **9,987,912.33**.

Business interpretation: This region may contain scalable practices or stronger demand conditions.

Recommended action: Study regional playbooks and apply learnings to weaker regions.

## Insight 3: Category profitability
Observation: **Technology** contributes the highest category profit.

Data evidence: Profit for this category is **28,043,309.91**.

Business interpretation: Category focus should consider profit, not only sales.

Recommended action: Prioritise profitable sub-categories in inventory and promotion planning.

## Insight 4: Sub-category risk
Observation: The lowest-profit sub-category is **Office Supplies / Paper**.

Data evidence: Profit is **318,706.90** on sales of **2,128,252.66**.

Business interpretation: Low or negative profitability may be caused by discounting, returns, shipping cost, or cost structure.

Recommended action: Review pricing and discount rules for this sub-category.

## Insight 5: Customer segment behavior
Observation: **Home Office** generates the highest sales among customer segments.

Data evidence: Segment sales are **74,500,746.01** and profit is **11,555,047.08**.

Business interpretation: Segment-level targeting can improve campaign efficiency.

Recommended action: Build segment-specific offers and monitor segment return rates.

## Insight 6: Discount impact
Observation: Discount and profit have correlation of **-0.266**.

Data evidence: The dashboard scatter plot shows profit risk at higher discount levels.

Business interpretation: Discounts need margin guardrails because sales growth can hide profit erosion.

Recommended action: Add approval thresholds for high discounts and monitor profit by discount band.

## Insight 7: Shipping and delivery performance
Observation: The highest return-rate delay bucket is **6-8 days**.

Data evidence: Return rate in that bucket is **4.85%** across **660** orders.

Business interpretation: Delivery delay may contribute to customer dissatisfaction and returns.

Recommended action: Review carrier performance and consider service-level targets for high-value orders.

## Insight 8: Return pattern and business risk
Observation: **Furniture** has the highest category return rate.

Data evidence: Return rate is **7.67%**.

Business interpretation: Returns can reduce profit quality and create operational cost.

Recommended action: Investigate product quality, expectations, and fulfilment issues in high-return categories.
