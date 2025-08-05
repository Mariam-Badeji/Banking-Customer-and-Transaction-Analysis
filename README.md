# Banking-Date-Analysis
## Background and Overview
This dashboard analyzes banking data from 2023 through mid-2025 to understand how customers interact with different products and identify which products generate the most revenue. It also explores broader patterns, including transaction volumes, channel preferences (mobile, branch, ATM, online), and emerging trends over time.

The company has a comprehensive data on their customers segmentation and insight, revenue and cost incurred by customers, transaction behavior, product offerings, and transactional trends and performance. This project thoroughly analyzes this data in order to uncover important trends and insights that will improve it’s revenue and customer retention.

Insights and recommendations are provided on the following key areas:

- **Revenue Analysis:** Identifying which products and customers generate the most revenue versus those that incur higher costs.
- **Transaction Analysis:** Tracking transaction trends over time, including seasonal peaks and slowdowns.
- **Customer Behavior Trends:** Evaluation of how each customer interact with product and if they are getting the right recommendation for their financial needs and Understanding customer behavior across segments and channels (mobile, branch, ATM, online).
- **Regional Comparisons:** An assessment of which bank branch city got the most revenue.
- **Product Performance:** Evaluates which product type brought in the most revenue in terms of fees.

## Data Modeling and Structure

The raw banking data was normalized into First Normal Form (1NF) to eliminate redundancy and ensure consistent, accurate analysis. This process done with Excel, involved:

- Separating transaction details, customer information, and product data into structured tables
- Standardizing fields such as currency and dates
- Creating relationships between tables to support reliable aggregations and time-based analysis

<img width="2260" height="1315" alt="Normal Form 8" src="https://github.com/user-attachments/assets/78c52d98-5977-4a97-9fa3-0cad03d261fc" />

This foundation improved the accuracy of calculations—such as revenue, costs, and trends—and enabled efficient reporting in Power BI.

## Executive Summary
### Overview of Findings

After having peaked in the late 2023, total fees (revenue) have continued to grow moderately without much sudden declines. The line chart filtered by year shows how much of each the selected year’s total revenue is contributed by the various fees collected. This is shown in terms of value and volume. We see that even though **late payment fees** accounted for the least amount of revenue in volume compared to other fees – insurance fees and credit card payment, it accounted for more than half (52.28%) of the revenue streams in value at €333, 088. Also found that customers within the low-income segment, paid more fees compared to their income level. On the other hand, **Low-income customers** bore a disproportionately high fee burden relative to their income levels, signaling potential financial strain within this segment.

<img width="783" height="536" alt="Line chart" src="https://github.com/user-attachments/assets/4d6535ea-f74d-4894-862d-7fc5bd8775f5" />

<img width="1035" height="284" alt="Feess" src="https://github.com/user-attachments/assets/b51ce9d4-cf50-46b2-b5b7-4e67c10c0519" />

### Revenue Analysis

