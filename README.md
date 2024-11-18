In this analysis project, I used Online Retail and Online Retail II data and here the key features :

- InvoiceNo : ID Categorical a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter ‘c’, it indicates a cancellation.
- StockCode : ID Categorical a 5-digit integral number uniquely assigned to each distinct product.
- Description : Feature Categorical product name.
- Quantity : Feature Integer the quantities of each product (item) per transaction.
- InvoiceDate : Feature Date the day and time when each transaction was generated.
- UnitPrice : Feature Continuous product price per unit sterling.
- CustomerID : Feature Categorical a 5-digit integral number uniquely assigned to each customer.
- Country : Feature Categorical the name of the country where each customer resides.

To develop a more precise customer segmentation model, need to leverage RFM analysis (Recency, Frequency, Monetary) alongside an understanding of customer behavior during peak and dip seasons. This approach enables us to create more targeted and effective customer segments based on their transaction history, recent engagement, and seasonal behavior.
RFM analysis is a method used to evaluate and segment customers based on three key metrics:

- Recency (R): How recently a customer has made a purchase. Customers who purchased recently are more likely to respond to marketing campaigns and promotions. (days)
- Frequency (F): How often a customer makes a purchase. Customers who make frequent purchases are typically more loyal and engaged.
- Monetary (M): How much a customer spends in total. Customers who spend more are typically more valuable to the business.

Data :
- D. Chen. “Online Retail,” UCI Machine Learning Repository, 2015. [Online]. Available: https://doi.org/10.24432/C5BW33. (Online Retail).
- Chen, D. (2012). Online Retail II [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5CG6D. (Online Retail II).

Medium : 
https://medium.com/@vegatrain33/customer-segmentation-and-targeting-in-online-retail-eba0a541cc0b
