# Banking-Data-Analysis
## Background and Overview
This dashboard analyzes banking data from 2023 through mid-2025 to understand how customers interact with different products and identify which products generate the most revenue. It also explores broader patterns, including transaction volumes, channel preferences (mobile, branch, ATM, online), and emerging trends over time.

The company has a comprehensive data on their customers segmentation and insight, revenue and cost incurred by customers, transaction behavior, product offerings, and transactional trends and performance. This project thoroughly analyzes this data in order to uncover important trends and insights that will improve it’s revenue and customer retention.

Insights and recommendations are provided on the following key areas:

- **Revenue Analysis:** Identifying which products and customers generate the most revenue versus those that incur higher costs.
- **Transaction Activity Overview:** Tracking transaction trends over time, including seasonal peaks and slowdowns.
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

After having peaked in the late 2023, total fees (revenue) have continued to grow moderately without much sudden declines. The line chart filtered by year shows how much of each the selected year’s total revenue is contributed by the various fees collected. This is shown in terms of value and volume. We see that even though **late payment fees** accounted for the least amount of revenue in volume compared to other fees – insurance fees and credit card payment, it accounted for more than half (52.28%) of the revenue streams in value at €333, 088. Also found that customers within the low-income segment, paid more fees compared to their income level. As a result, **Low-income customers** bore a disproportionately high fee burden relative to their income levels, signaling potential financial strain within this segment.

<img width="783" height="536" alt="Line chart" src="https://github.com/user-attachments/assets/4d6535ea-f74d-4894-862d-7fc5bd8775f5" />

<img width="1035" height="284" alt="Feess" src="https://github.com/user-attachments/assets/b51ce9d4-cf50-46b2-b5b7-4e67c10c0519" />

### Revenue Analysis:
- The bank’s revenue grew at a steady rate through the year so I can’t really say it peaked but the highest revenue amount (value) was in July 2023 and the subsequent lowest being in the same year in September. A Pattern I did notice was that some of the lowest values of the revenue were in the same month for both 2023 and 2024 dataset except 2025. –Loan payment transactions drive the most fee-based revenue (approximately €383,248.58) largely due to: Late payment Amounts, Insurance fees, and some credit card fees.
- There was a decline in the volume of revenue from 2023 by 54 which is a -1.12% change from the previous year while the value of revenue saw a decline of €6,959 at -2.57% change. This decline was mostly in the late payment fee which saw a decline of €4,304 and the rest was shared amongst insurance fee (€1,142) and credit card fee (€1,513).
- The **Middle-Income segment** emerged as the strongest contributor to overall revenue, generating 5,161 transactions (highest by volume) and €286,605.67 in total revenue (highest by value). This indicates that middle-income customers are both highly active and financially significant, making them a critical segment for sustaining growth.
- **Mobile banking** is the leading revenue channel, generating **3,023 transactions and €166,971.73 in value**. **Branch banking** follows closely with 2,923 transactions and €162,786.77 in value. This suggests that while branches remain important, mobile banking is becoming the dominant channel for revenue generation.

<img width="1688" height="578" alt="Rev" src="https://github.com/user-attachments/assets/1b0a650b-c5e3-4f76-b677-aa1f727b8737" />

### Transaction Activity Overview:
- Across all channels, a total of 20,000 transactions were recorded. The Middle-Income segment emerged as the most transaction-active group, accounting for 44.43% of all transactions.
- **Mobile phones** are the most frequently used channel for transactions, which aligns with the growing ease of digital payments through apps. However, the gap between mobile and branch transactions is relatively small, suggesting two possibilities:

    - Older customers may still prefer visiting branches.

  - Network or service limitations could be influencing channel choice.

- When broken down by **customer segment**, the distribution of transactions across channels remains consistent, with mobile dominating. Additionally, transfers, loan payments, and deposits are more common at branches than via mobile, further supporting the idea that certain demographics lean toward in-person banking or face barriers to fully adopting mobile channels.
<img width="1679" height="846" alt="Transc" src="https://github.com/user-attachments/assets/8bdc077f-d5c6-4414-a4ef-58ea6a4d569b" />

### Customer Behavior Trends:
- The bank served a total of **8,025** customers, distributed as follows:

    - Middle-income segment: 5,680 customers (largest group)

    - High-income segment: 4,647 customers

    - Low-income segment: 3,530 customers

  Between 2023 and 2024, the customer base grew by 71 customers (1.32%)
- Although low-income customers contribute the least to overall transactions and revenue (both in volume and value), they incur disproportionately higher fees relative to their income. The fee-to-income ratio highlights this imbalance, indicating that some low-income customers are bearing a heavier financial burden compared to other segments.
- The most popular **financial product** among customers is **credit cards**. This trend may help explain why middle- and high-income customers account for more transactions: their higher income brackets and stronger credit scores make them better positioned to access and repay credit facilities, driving greater engagement with this product category.
- There is a positive relationship between customer credit scores and both transaction activity and fee volume. In other words, customers with higher credit scores tend to:

    - Carry out more transactions

    - Incur higher fee volumes, likely due to greater engagement with credit-based products.

<img width="1676" height="850" alt="Customer" src="https://github.com/user-attachments/assets/97a4dd86-8215-4a1f-bb2a-34c68dc297ba" />

<img width="1052" height="270" alt="relate" src="https://github.com/user-attachments/assets/97c8fcc6-3186-40ca-b537-35724e8c61f0" />

### Regional:
- **Growth trends:** Only Murcia and Zaragoza showed an increase in revenue volume over the period, while Valencia experienced a notable, dropping from €34,398.69 to €28,310.04 from 2023 - 2024.

- **Top contributors:** Barcelona, Malaga, and Murcia emerged as the leading branches, each generating over €85,000 in revenue value.
<img width="620" height="825" alt="Branch" src="https://github.com/user-attachments/assets/4cb8c0b4-3765-4391-a0a1-e4509f5ec8fb" />

### Product Evaluation:
- Product recommendations generally align with customer financial needs and behaviors. For example, low-income segment customers are frequently recommended the Financial Literacy Program, which is appropriate given their higher fee-to-income ratio. This suggests that targeted recommendations are being used to address financial strain within this segment.

<img width="1055" height="312" alt="Product" src="https://github.com/user-attachments/assets/a2311015-d07b-4c45-bc4b-6132aa7ea889" />

## Recommendations
Based on the insights provided, the following recommendations have been provided:
- **Strengthen Focus on Middle-Income Customers:** Since middle-income customers generate the highest revenue (volume and value), targeted offers—such as mid-tier investment products or loyalty programs—could deepen engagement and sustain growth.
- **Expand Mobile Banking Capabilities:** With mobile banking leading in revenue and closely followed by branch usage, improving mobile app performance (e.g., reducing downtime, simplifying transfers) could accelerate adoption and reduce reliance on physical branches.
- **Address Fee Burden for Low-Income Customers:** The high fee-to-income ratio among low-income customers suggests a need for:

  - Fee-capping or flexible payment options

  - Enhanced financial literacy initiatives (building on the existing Financial Literacy Program)

  - Product designs that reduce reliance on costly transactions (e.g., no-fee basic accounts)
- **Leverage Credit Card Popularity:** With credit cards as the most popular product, especially among middle- and high-income segments, consider:
    - Premium rewards for high-transaction users
    - Cross-selling investment or savings products to credit-active customers
    - Risk-based pricing to maintain portfolio quality as usage grows
- **Monitor Seasonal and Regional Trends:** Use MoM and YoY tracking to anticipate seasonal slowdowns and design promotions accordingly. Investigate factors driving Murcia and Zaragoza’s revenue growth to replicate in underperforming regions

<img width="1692" height="948" alt="Bank dashboard 1" src="https://github.com/user-attachments/assets/21c24410-5f3a-4012-bfcb-348639280891" />

<img width="1687" height="952" alt="Bank dashboard 2" src="https://github.com/user-attachments/assets/e538bfe1-5ae3-4b4d-a0f9-7a447940c88a" />

<img width="1698" height="953" alt="bank dashboard 3" src="https://github.com/user-attachments/assets/f3822220-0dcf-4039-8fe5-ed4db37f0923" />
