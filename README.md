# AdventureWorks-Analisis
Context: A financial analysis was conducted on AdventureWorks' transactional data (2017), integrating sales, product, customer, territory, and marketing campaign information using SQL JOINs. The objective was to evaluate performance by country to identify where the highest revenue is generated and which markets are most profitable considering marketing investment.

Analysis: A consolidated country-level dataset was built, calculating key KPIs: revenue, costs, gross profit, margin, and ROI.
The approach included data cleaning (handling NULLs and standardization), metric validation (QA of totals and margins), and aggregations using GROUP BY.
Revenue was cross-referenced with campaign spending to measure the actual efficiency of marketing by territory.

Conclusions: Highly profitable markets were identified where ROI significantly exceeds the average, indicating efficient budget allocation.
Some countries show high revenue but low margin, highlighting issues with costs or pricing. Some markets have low ROI, suggesting inefficient campaigns or overinvestment in marketing.
Key insight: The market with the highest revenue isn't always the most profitable, so decisions should be based on margin and ROI, not just sales volume.
