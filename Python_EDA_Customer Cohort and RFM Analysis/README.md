# Customer Cohort and RFM Analysis
Developed a personal project involving cohort and RFM analysis to optimize customer insights. Leveraged data to identify successful acquisition periods, retention challenges, and customer segments. Through RFM segmentation, identified high-value Champions, potential Loyal Customers, and at-risk segments. These insights drove targeted strategies to enhance customer engagement, loyalty, and revenue. Project showcased ability to translate data into actionable insights, contributing to informed decision-making and potential revenue growth in real-world scenarios.

## Cohort
A cohort is a group of subjects who share a defining characteristic. We can observe how a cohort behaves across time and compare it to other cohorts. Cohorts are used in medicine, psychology, econometrics, ecology and many other areas to perform a cross-section (compare difference across subjects) at intervals through time.

### Types of cohorts:

**Time Cohorts** are customers who signed up for a product or service during a particular time frame. Analyzing these cohorts shows the customers’ behavior depending on the time they started using the company’s products or services. The time may be monthly or quarterly even daily.

**Behaovior cohorts** are customers who purchased a product or subscribed to a service in the past. It groups customers by the type of product or service they signed up. Customers who signed up for basic level services might have different needs than those who signed up for advanced services. Understaning the needs of the various cohorts can help a company design custom-made services or products for particular segments.

**Size cohorts** refer to the various sizes of customers who purchase company’s products or services. This categorization can be based on the amount of spending in some periodic time after acquisition or the product type that the customer spent most of their order amount in some period of time.

## RFM (Recency, Frequency, Monetary)
analysis is a customer segmentation technique that uses past purchase behavior to divide customers into groups. RFM helps divide customers into various categories or clusters to identify customers who are more likely to respond to promotions and also for future personalization services.

**RECENCY (R):** Days since last purchase

**FREQUENCY (F):** Total number of purchases

**MONETARY VALUE (M):** Total money this customer spent.

In this Project, we will be implementing the concepts of Cohort and RFM analysis for our data set to gain the Insights that drives the business.

The Data is collected from the UCI repository. https://archive.ics.uci.edu/dataset/502/online+retail+ii

The data set named Online Retail - II includes the sales of an online store between 01/12/2009 - 09/12/2011.

The majority of the company's customers are corporate customers. Variables Description:

InvoiceNo : The number of the invoice, unique per each purchase. Refund invoice numbers contain "C"

StockCode : Unique code per each item

Description : Name of the item

Quantity : The number of items within the invoice

InvoiceDate : Date and time of the purchase

UnitPrice : Price of a single item, as of Sterlin

CustomerID : Unique id number per each customer

Country : The country where the customer is living


## Performing Cohort Analysis
![Cohort-1](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/9099a5ef-3e17-40c6-8d75-953115f6e896)

![Cohort-2](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/b6b260b8-063f-431f-83ac-7e5ccb87cf7f)

## RFM Analysis

![RFM-1](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/62b47849-4a85-4f48-8709-adfbfc5ec113)

![RFM-2](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/8e8091bc-e0d9-4109-ac46-2569968375bb)

## Insights & Recommendations:
**Champions (663 customers):** These are your high-value, highly engaged customers. They generate substantial revenue (approx. $4,543,051) and exhibit consistent purchasing behavior. Focus on nurturing these customers and offering them personalized experiences to maintain their loyalty.

**Loyal Customers (742 customers):** While not as high in revenue as Champions, Loyal Customers still contribute significantly (approx. $2,037,582). They showcase steady engagement and repeat purchases. Continue catering to their preferences to ensure continued loyalty.

**Potential Loyal Customers (517 customers):** These customers show promise with their revenue contribution (approx. $377,157), but there's room for growth. Invest in targeted marketing and engagement strategies to encourage repeat purchases and elevate them to Loyal or Champion status.



**At Risk (611 customers):** These customers have generated substantial revenue (approx. $726,405), but their engagement might be declining. Implement re-engagement campaigns, special offers, or personalized recommendations to prevent them from lapsing.


**Hibernating (1017 customers):** While the revenue contribution (approx. $410,038) is notable, these customers show low recent engagement. Rekindle their interest through tailored campaigns, showcasing new offerings or reminding them of their past positive experiences.


**About to Sleep (343 customers):** Although the revenue contribution (approx. $151,373) is moderate, these customers might be slipping away. Reach out with targeted communications to awaken their interest and prevent them from becoming dormant.

**Need Attention (207 customers):** Despite a moderate revenue contribution (approx. $219,494), these customers exhibit signs of waning engagement. Address their needs promptly, offering personalized incentives to re-engage them.

**Promising (87 customers):** These customers have potential with a revenue contribution (approx. $31,937). Nurture them with personalized interactions, providing value to elevate their engagement and purchasing frequency.

**Can't Lose (77 customers):** While the customer count is low, their revenue contribution (approx. $315,658) is significant. Treat them as VIPs, offering exclusive experiences and tailored solutions to reinforce their loyalty.

**New Customers (50 customers):** These customers are in the early stages, with a revenue contribution (approx. $19,310). Focus on providing exceptional onboarding experiences to convert them into higher-value segments.

## Conclusion
The combined analysis of customer cohorts and RFM segments provides valuable insights for our business. By understanding customer behavior over time, we identified successful acquisition periods and challenges in retention. The RFM segmentation revealed distinct customer groups, such as high-value Champions and potential Loyal Customers. These insights enable us to tailor strategies, focus on high-value segments, re-engage at-risk customers, and allocate resources effectively. Ultimately, our data-driven approach empowers us to enhance customer loyalty, optimize revenue, and shape targeted marketing efforts for sustainable growth.
