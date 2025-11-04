### 🌳 Balanced Tree — Danny Ma (7th Case Study)
**Project:** Balanced_Tree_DannyMA_7th_Case_Study  
**Description:** Balanced Tree is a retail clothing company. This case study uses product and sales datasets to produce high-level sales reporting, transaction analysis, product/segment/category analytics, and a scheduled monthly report. The bonus task recreates `product_details` from `product_hierarchy` and `product_prices` (recursive CTE recommended).

**Datasets:**  
- `balanced_tree.product_details` (product metadata)  
- `balanced_tree.sales` (transactional sales: quantity, price, discount_pct, member_status, transaction_id, timestamp)  
- `product_hierarchy` (used for bonus)  
- `product_prices` (used for bonus)

**Tools:** SQL (PostgreSQL examples), DAX / Power BI (for visualization)  
**Case link / reference:** https://8weeksqlchallenge.com/case-study-7/

**Key deliverables:**  
- High-level sales metrics (total qty, revenue, total discount)  
- Transaction-level analysis (unique transactions, avg products/transaction, transaction revenue percentiles, member vs non-member splits)  
- Product / Segment / Category analytics (top products by revenue, revenue split by segment/category, penetration, combos)  
- Reporting script to run monthly (parameterised by month)  
- Bonus: single-query to reconstruct `product_details` from hierarchy & prices (recursive CTE)




