# TrendHive Customer Segmentation
## Project Background
TrendHive, an online retail store, has grown rapidly in recent years, attracting a diverse customer base and processing a significant volume of transactions. As a result, the company seeks to better understand its customers, improve targeted marketing strategies, and increase overall customer satisfaction and retention. I have teamed up with the Head of Analytics to analyze transaction data and perform RFM Analysis (Recency, Frequency, Monetary value) to segment customers into meaningful groups. This segmentation will provide actionable insights to tailor marketing campaigns, allocate resources effectively, and identify opportunities for growth.
## Executive Summary
After analysis of TrendHive’s 400K records spanning 2009 - 2010, its customers were split into the following 7 groups based on their RFM scores: “Retain”, “Re-engage”, “Nurture”, “Reward”, “Spoil”, “Upsell”, and “Treasure”. 35% of customers fell into the “Nurture” category, the least active and lower-valued customers. Approximately 5% of customers fell into the “Treasure” category. These are the most valued customers as they make frequent purchases with extreme spending. By focusing on targeted engagement strategies, TrendHive can enhance customer loyalty, optimize marketing ROI, and unlock new opportunities for revenue growth.
![transactions (1)](https://github.com/user-attachments/assets/30a54b0c-a844-4e7b-b226-2cd06b673d31)

## Cluster Analysis
| Group     | Number of Customers | % of Total Customers |
|-----------|---------------------|----------------------|
| RETAIN    | 914                 | 21.3%                |
| RE-ENGAGE | 902                 | 21.0%                |
| NURTURE   | 1499                | 35.0%                |
| REWARD    | 494                 | 11.5%                |
| SPOIL     | 197                 | 4.6%                 |
| UPSELL    | 53                  | 1.2%                 |
| TREASURE  | 226                 | 5.3%                 |
| Total     | 4285                | 100.0%               |


![cluster](https://github.com/user-attachments/assets/cef05351-1e6c-415f-b736-6402fb9f0c1b)

1. Blue Cluster: **RETAIN**
- This group consists of valuable customers who make frequent purchases, though their recent activity may vary. The priority should be on retention strategies to ensure their continued loyalty and consistent spending.

2. Orange Cluster: **RE-ENGAGE**
- This group consists of lower-value customers who buy infrequently and haven't made recent purchases. The emphasis should be on re-engaging them to encourage a return to regular purchasing habits.

3. Green Cluster: **NURTURE**
- This group consists of the least active and lowest-value customers, though they have made recent purchases. They may be new or require further nurturing to boost their engagement and spending levels.

4. Red Cluster: **REWARD**
- This group consists of high-value customers who make purchases very frequently, with many still actively buying. They are your most loyal customers, and recognizing their loyalty is crucial for keeping them engaged.

![outlier](https://github.com/user-attachments/assets/3c5728fb-10a0-4d1f-9daa-f042cabaa725)

5. Pink Cluster: **SPOIL**
- High spenders but not necessarily frequent buyers. Their purchases are large but infrequent.

6. Brown Cluster: **UPSELL**
- Frequent buyers who spend less per purchase. These customers are consistently engaged but might benefit from upselling opportunities.

7. Purple Cluster: **TREASURE**
- The most valuable outliers, with extreme spending and frequent purchases. They are likely your top-tier customers who require special attention.

![distribution](https://github.com/user-attachments/assets/2096d77a-c4a4-43c1-9cd0-0c31549c4117)
## Recommendations
1. Blue Cluster: **RETAIN**
   - Implement loyalty programs, personalized offers, and regular engagement to ensure they remain active.
2. Orange Cluster: **RE-ENGAGE**
   - Use targeted marketing campaigns, special discounts, or reminders to encourage them to return and purchase again.
3. Green Cluster: **NURTURE**
   - Focus on building relationships, providing excellent customer service, and offering incentives to encourage more frequent purchases.
4. Red Cluster: **REWARD**
   - Implement a strong loyalty program, provide exclusive offers, and recognize their loyalty to keep them engaged and satisfied.
5. Pink Cluster: **SPOIL**
    - Focus on maintaining their loyalty with personalized offers or luxury services that cater to their high spending capacity.
6. Brown Cluster: **UPSELL**
    - Implement loyalty programs or bundle deals to encourage higher spending per visit, given their frequent engagement.
7. Purple Cluster: **TREASURE**
    - Develop VIP programs or exclusive offers to maintain their loyalty and encourage continued engagement.

