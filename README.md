# Customer Segmentation through RFM Analysis
## Objective
Segment customers of an online retail business using RFM analysis (Recency, Frequency, Monetary) combined with K-Means clustering. Identify distinct customer groups based on their purchasing behaviors and develop data-driven strategies for personalized marketing, 
customer retention, and improving overall business performance.\
![scatter](https://github.com/user-attachments/assets/3f956e48-9c86-42af-8daa-159bb4a1f18b)
*Full Write-Up in Jupyter Notebook*
## Data Description
[Online Retail Data](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

**InvoiceNo**: Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation\
**StockCode**: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product\
**Description**: Product (item) name. Nominal\
**Quantity**: The quantities of each product (item) per transaction. Numeric\
**InvoiceDate**: Invoice date and time. Numeric. The day and time when a transaction was generated\
**UnitPrice**: Unit price. Numeric. Product price per unit in sterling (Â£)\
**CustomerID**: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer\
**Country**: Country name. Nominal. The name of the country where a customer resides
## Cluster Analysis
![cluster](https://github.com/user-attachments/assets/cef05351-1e6c-415f-b736-6402fb9f0c1b)

1. Blue Cluster: **RETAIN**
- This group consists of valuable customers who make frequent purchases, though their recent activity may vary. The priority should be on retention strategies to ensure their continued loyalty and consistent spending.
- Action: Implement loyalty programs, personalized offers, and regular engagement to ensure they remain active.

2. Orange Cluster: **RE-ENGAGE**
- This group consists of lower-value customers who buy infrequently and haven't made recent purchases. The emphasis should be on re-engaging them to encourage a return to regular purchasing habits.
- Action: Use targeted marketing campaigns, special discounts, or reminders to encourage them to return and purchase again.

3. Green Cluster: **NURTURE**
- This group consists of the least active and lowest-value customers, though they have made recent purchases. They may be new or require further nurturing to boost their engagement and spending levels.
- Action: Focus on building relationships, providing excellent customer service, and offering incentives to encourage more frequent purchases.

4. Red Cluster: **REWARD**
- This group consists of high-value customers who make purchases very frequently, with many still actively buying. They are your most loyal customers, and recognizing their loyalty is crucial for keeping them engaged.
- Action: Implement a strong loyalty program, provide exclusive offers, and recognize their loyalty to keep them engaged and satisfied.

## Outliers Analysis
![outlier](https://github.com/user-attachments/assets/3c5728fb-10a0-4d1f-9daa-f042cabaa725)

1. Pink Cluster: **SPOIL**
- High spenders but not necessarily frequent buyers. Their purchases are large but infrequent.
- Action: Focus on maintaining their loyalty with personalized offers or luxury services that cater to their high spending capacity.

2. Brown Cluster: **UPSELL**
- Frequent buyers who spend less per purchase. These customers are consistently engaged but might benefit from upselling opportunities.
- Action: Implement loyalty programs or bundle deals to encourage higher spending per visit, given their frequent engagement.

3. Purple Cluster: **TREASURE**
- The most valuable outliers, with extreme spending and frequent purchases. They are likely your top-tier customers who require special attention.
- Action: Develop VIP programs or exclusive offers to maintain their loyalty and encourage continued engagement.

![distribution](https://github.com/user-attachments/assets/2096d77a-c4a4-43c1-9cd0-0c31549c4117)
