# Customer Cohort and Retention Analysis

Welcome to my portfolio! Explore my project on Customer Cohort and Retention Analysis where I delve into generating valuable insights about customer behavior. The dataset I've worked with is sourced from the UCI repository and focuses on transactions from a UK-based online retail business registered between 01/12/2009 and 09/12/2011. This company specializes in unique all-occasion gift-ware and serves a diverse customer base that includes wholesalers.

## Project Overview:
The project begins with essential ETL activities conducted in the Power Query editor. Beyond the foundational data, I've created Customer Dimension and DimDate tables to facilitate in-depth analysis. Notably, I've chosen to represent customer visits using the start date of the month, enabling month-level retention analysis.

## Key Dataset Attributes:

**InvoiceNo:** Unique identifier for each transaction.
**StockCode:** Product code for items.
**Description:** Product name.
**Quantity:** Quantity of products per transaction.
**InvoiceDate:** Date and time of transaction.
**UnitPrice:** Product price per unit.
**CustomerID:** Unique customer identifier.
**Country:** Customer's country.
## Project Components:

### Customer Insights:
This dashboard provides a comprehensive overview of customer activity, categorizing customers into segments such as active, new, retained, and churned. Users can leverage the slicer to explore total sales during specific periods. I've introduced loyalty badges to classify customers based on their behavior and categorized sales amounts by loyalty level.
![Summary](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/850b1cbb-0864-48e2-bbf2-ee6bdc6e52d5)

### Insights:

The dataset spans around 25 months.
Customer categorization:
Loyal and Most Frequent: visits >= 20
Loyal and Regular: 15 <= visits < 20
Occasional: visits > 8
Irregular/New: visits <= 8
New/Irregular customers constitute around 80% of the customer base, contributing significantly to sales.
Average sale value per head is significantly higher for Loyal and Most Frequent customers compared to new/irregular customers.
### Retention Analysis:
This dashboard provides a summary of customer retention rates, both in terms of percentage and customer count, analyzed on a monthly basis.
![Retention](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/1b334492-5abb-4fa2-a7dd-26d6d8dddf1e)

### Churn Analysis:
This dashboard highlights churn by presenting the count of customers who have churned.
![Churn](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/7ec70bba-05fd-4e05-96da-c48f9350bcaf)


### Customers Flow:
Visualizations in this dashboard illustrate the flow of customers over time, emphasizing churned, recovered, and retained customers. A comprehensive bar chart showcases the contribution of different customer categories to the overall customer count.
![Customers flow](https://github.com/prasadkanthuri/Data_Insights/assets/135444495/ba2f9b46-0c3e-4898-af2d-e3bc729c3e61)


## Key Recommendations:

Only 2.3% of the total 5881 customers have been retained, signaling an opportunity for the management to enhance the retention rate. Strategies like offering additional benefits to regular clients or introducing new schemes could be explored.
Feel free to reach out to me for a more detailed understanding of this project and its insights. Let's connect and discuss how these findings can be applied to drive business growth and customer satisfaction.




