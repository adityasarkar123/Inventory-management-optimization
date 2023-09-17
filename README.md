# Optimizing Inventory Management for Efficient Supply Chain

This project involves an Inventory Management analysis utilizing SQL and PowerBI. The analysis was conducted on Inventory, Production, and Sales data sourced from the AdventureWorks 2019 database. The dataset is based on a fictional company named 'FitCapacity' and aims to address specific operational challenges.

**Objective:**
The primary objectives of this analysis are to:

1. Determine products with the highest and lowest turnover rates.
2. Calculate the average duration of product unavailability and assess the frequency of stockouts.
3. Categorize products into high-selling, low-selling, and average-selling.
4. Leverage insights to offer recommendations for optimizing inventory levels. This may involve refining reorder points, prioritizing specific products for procurement, or considering discontinuation of slow-moving items for enhanced operational efficiency.

**Overview:**
This analysis delves into the operations of a company with 14 production/storage locations, focusing on four key product categories: Bikes, Accessories, Clothing, and Components. The total inventory value stands at an impressive 74 billion USD, with Bikes and Accessories leading in both sales impact and inventory influence.

**Key Findings:**
1. The Stock Turn Ratio, at 42%, indicates slower sales and a notable accumulation of unsold goods. Optimizing production to align with demand is crucial for enhancing stock turnover and overall industry performance.

2. On-time production stands at 48%. As demand escalates, augmenting production capacity through effective resource utilization (time, labor, and materials) is imperative for expediting production and sales delivery.

3. Leveraging the Pareto principle (80/20 rule) for inventory, we identified crucial product categories:
   - AZ goods (High Value, uncertain demand) significantly impact annual revenue. Implementing tailored strategies for production, sales, and delivery management is essential to mitigate low stock levels.
   - BZ goods (Medium value, uncertain demand) warrant regular monitoring as they contribute significantly to annual revenue.
   - CZ goods (Low value, uncertain demand) should be subject to periodic review.

4. Noteworthy, 26.5% of goods fall below the Re-order point, while a staggering 72.8% are below Safety Stock levels. A mere 0.73% are currently in stock, underscoring the need to address this imbalance and make products available for sales.

5. Subassembly locations house goods with the highest inventory value and quantity, followed by the Miscellaneous storage location.

6. Sales trends exhibit seasonality, reflected in the forecast. Bundling complementary goods during peak seasons could optimize inventory in alignment with ABC analysis.

7. The annual revenue shows an upward trajectory over the years, albeit with evidence of sales seasonality.

**Recommendations:**
- Strict adherence to Safety Stock and Reorder Points is imperative to address unforeseen demands or supply disruptions.
- Scaling up on-time production is vital, and regular inventory audits are advised to maintain optimal inventory levels and mitigate the risk of overstocking or stockouts.
