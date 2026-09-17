Shoe Sales Performance Analysis

An end-to-end Excel analysis of a global footwear retailer's sales data — from raw data cleaning to an interactive dashboard — built to answer eight core business questions for management.

**Tools used:** Excel (Power Query-style cleaning with TRIM, CLEAN, PROPER), LOOKUP functions, PivotTables, PivotCharts, slicers, and a consolidated dashboard.

---

## 1. Data Preparation

- Cleaned raw shoe sales data using `TRIM()`, `CLEAN()`, and `PROPER()` to standardize text fields (product names, categories, countries, payment types) and remove inconsistent spacing/casing.
- Joined the Shoe Sales table with a separate Price table using a lookup function (`VLOOKUP`/`XLOOKUP`) on product ID to bring pricing into the main dataset.
- Built Seven Pivot Tables covering revenue by month, category, product, brand, country, and payment type, then visualized each with a matching chart.
- Consolidated everything into a single-page interactive Dashboard with slicers for filtering by category.

## 2. Headline Numbers

| Metric | Value |
|---|---|
| Total Revenue | $355,048 |
| Total Cost | $192,713 |
| Total Profit | $162,335 |
| Profit Margin | 47% |
| Units Sold | 4,012 |
| Avg. Revenue per Unit | ~$88.50 |

A 47% margin is a strong, healthy position for a Shoe retailer — costs are well controlled relative to revenue.

## 3. Business Questions & Findings

**1. How is the business performing overall?**
Revenue of $355K against a 47% profit margin signals a fundamentally healthy business. The bigger question isn't profitability — it's consistency of demand month to month (see below).

**2. How have revenue and profit changed over time?**
Revenue held steady in the $40–45K/month range from January through May, then jumped sharply to $70,771 in June — a 59% spike over the prior month — before falling back to $49,497 in July. August shows only $16,041, which most likely reflects a partial or incomplete reporting period rather than a genuine collapse in sales, and should be confirmed before drawing conclusions from it.

**3. Which products are driving sales?**
By revenue: Canvas ($63,488), Oxford ($58,905), and Brogues ($58,576) are the top three — together over 51% of total revenue. Derby ($16,704) is the lowest by revenue.

**4. Which products are driving profitability?**
Sales volume and profitability tell different stories at the product level:

| Product | Revenue | Profit | Margin |
|---|---|---|---|
| Derby | $16,704 | $9,396 | **56.2%** |
| Boots | $41,040 | $19,980 | 48.7% |
| Loafers | $24,462 | $11,778 | 48.2% |
| Monk Straps | $51,175 | $24,150 | 47.2% |
| Oxford | $58,905 | $26,367 | 44.8% |
| Canvas | $63,488 | $27,776 | 43.7% |
| Slippers | $40,698 | $17,784 | 43.7% |
| Brogues | $58,576 | $25,104 | 42.9% |

Derby, the lowest-revenue product, is actually the **most profitable per dollar sold** — its low revenue reflects low sales volume, not a weak product. Brogues, the second-highest revenue earner, has the **weakest margin** of any product — it's carrying a heavier cost load than its sales figures suggest.

**5. Which categories and brands perform best?**
Formal footwear dominates at 51% of revenue ($179,935), more than double the next category (Casual, 23%/$82,917). At the brand level, Clarks (35%/$123,543) and Zara (27%/$94,797) together account for over 60% of all revenue — a concentration worth watching from a supplier-risk perspective.

**6. Which countries contribute the most to the business?**
The USA leads ($39,127 revenue / $17,892 profit), followed closely by the UK, Ghana, Zimbabwe, and India. Revenue is genuinely global and fairly evenly distributed across 14 countries rather than concentrated in one or two markets — a sign of diversified demand, not a red flag.

**7. What purchasing patterns can we identify from payment method and product preferences?**
Payment method is nearly evenly split: Card (27%), Bank Transfer (27%), Cash (25%), Mobile Money (21%). Given meaningful revenue from Ghana, Zimbabwe, Kenya, Uganda, and Nigeria, the 21% Mobile Money share is notable and likely to grow — this channel should not be deprioritized in favor of card/bank rails.

**8. What actions should management take based on the findings?**
See recommendations below.

## 4. Recommendations

1. **Investigate why Derby sells so little** despite having the best margin of any product (56.2%). This looks like an easy revenue win — low visibility, pricing, or limited stock could all be fixable causes rather than a real lack of demand.
2. **Audit Brogues' cost structure.** It's the second-highest revenue earner but has the thinnest margin (42.9%) — that points to a cost problem (supplier pricing, materials, logistics) rather than a demand problem, and is worth a closer look before assuming it's a top performer.
3. **Investigate the June spike.** Identify what drove the 59% jump (promotion, seasonal demand, restock) so it can be deliberately repeated rather than treated as a one-off.
4. **Confirm the August figure** before treating it as a real decline — if it reflects an incomplete period, restate it before it influences planning.
5. At brand-level base on revenue,  Clarks and Zara (60%+ of revenue) are the highest-selling ones.
6. **Lean into Formal footwear and the Clarks/Zara partnership**, but monitor the concentration risk — two brands driving 60%+ of revenue is efficient but exposed if either relationship weakens.
7. **Keep all four payment rails fully supported**, with particular attention to Mobile Money infrastructure in African markets where it already carries meaningful share.


## Dashboard

![Shoe Sales Dashboard](Shoe_Sales_Dashboard.png)

## Project Overview

This project analyzes shoe sales data to identify sales trends, product performance, profitability, and key business insights.

## Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Data Cleaning
- Data Analysis

## Key Analysis

- Sales performance by product
- Sales trends over time
- Top-performing products
- Profit and margin analysis
- Product/category performance
