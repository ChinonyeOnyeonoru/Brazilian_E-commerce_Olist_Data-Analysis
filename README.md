# Ecommerce_Olist-store-Analysis
### Project Description:
Olist Store is the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. The Brazilian eCommerce public dataset of orders (from 2016 to 2018) made at Olist Store has been provided for analysis.
Using the dataset to prepare a PowerBI dashboard with visualisations that answer key questions, as well as prepare a report.
### Dataset:
Link:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Brazilian E-Commerce Public Dataset by Olist:

The Olist Store dataset has information from 100,000 orders made at multiple marketplaces in Brazil. The order can be viewed from multiple dimensions: from order status, price, payment, and freight performance to customer location, product attributes, and finally reviews written by customers. A geolocation dataset that relates Brazilian zip codes to latitude and longitude coordinates is also integrated into the dataset.

A. olist_customers_dataset

B.	olist_geolocation_dataset

C.	olist_order_items_dataset

D.	olist_order_payments_dataset

E.	olist_order_reviews_dataset

F.	olist_orders_dataset

G.	olist_product_dataset

H.	olist_sellers_dataset

I.	product_category_name_translation.
### 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞:
- To Visualise a company’s customer demographics, sales trend, orders by categories, orders changes by year, etc.

- To utilise created visualisations to provide recommendations for improvements.

- To Create a report.

### **Project Instructions:**

- Conduct exploratory data analysis with the Olist Store dataset
- Generate business insights and provide recommendations for improvement. 
- Use the results of the analysis to create a usable PowerBI dashboard with clear, concise, and informative data visualisations that drive recommended improvements for the client. 

After a customer purchases a product from Olist Store, a seller gets notified to fulfil that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.
Here are some ideas of the kinds of analyses you might conduct for Olist Store:
1.	Feedback Sentiment Analysis: Evaluate the polarity of the tweets as customer feedback positive, negative or neutral.
2.	Clustering: Some customers did not write a review. But for those that did, why are they happy or mad? 
3.	Sales Prediction: With purchase date information you will be able to predict future sales. 
4.	Delivery Performance: Be able to work through delivery performance and find ways to optimise delivery times.

### 𝐓𝐨𝐨𝐥𝐬 𝐔𝐬𝐞𝐝

-	PowerBi – Creating a reports

###**Creating Data Visualizations**

**Olist Mode of Payment Analysis** 

![image](https://github.com/user-attachments/assets/3070842d-ccf9-4850-a53d-97febff72aea)

This report analyses the various mode of payment used by Olist customers, based on four key metrics or the Key Performance Indicators (KPI): 
- Payment value distribution
- Total payment value,
- Payment installments
- Average payment value.

1.	Percentage Payment Value by Payment type
   
The pie chart shows the distribution of payment values across different payment types:
- Credit Card: With 78.34% of the total payment amount, credit cards lead the list of accepted payment methods.
- Boleto: With 17.92% of the total payment amount, Boleto is the second most used payment option.
- Voucher: Used seldom, accounting for only 2.37% of the total amount paid.
- Debit Card: make up the smallest share of the payment value, with only 1.37% of the total payment amount. 

2.	Sum of Payment Value by Payment Type

The bar chart at the top right displays the total Sum of Payment Value for each Payment Type:  
-	Credit Card: With a 12.5M total payment value, it leads by a considerable margin.
-	Boleto: Beleto is the significant contributor, with a 2.9 million payment value overall.
-	Voucher: Voucher payment type makes a meagre 0.4 million contribution. 
-	Debt Card: Wth a total of 0.2M, debit cards are the least popular form of payment.

  3.	Sum of Payment Installments by Payment Type

The line chart at the bottom left shows the breakdown of the sum of payment installment across the payment methods. 
-	Credit Card: With a total of 0.27 million installments, credit cards have the highest instalments overall.
-	Boleto: It drastically dropped with only 0.02 million installments. 
-	Voucher: the voucher has extremely low instalment usage of 0.01M
-	Debit Card: The installment declined further to 0.00M 

  4.	Average of Payment Value by Payment Type

The line chart at the bottom right shows the average payment value per transaction for each payment type:

-	Credit Card:  The Credit Card has the highest average payment value, with 163.32 units.
-	Boleto: the average payment value of Boleto is 145.03 units, which is a little less.
-	Debit Card: With an average of 142.57 units, debit cards trail Boleto by a little margin.
-	Voucher: Voucher has the lowest average payment value as a result of a significant drop in the payment value with 65.70 units. 

Key Insights/ Suggestions:
 
- Credit Card is the dominant payment type, both in terms of the total payment value (78.34%) and the highest average payment value (163 units).
- Boleto follows as the second most popular payment method, though it is significantly lower in terms of the number of installments and average payment value.
- Voucher and Debit Card are used sparingly, with vouchers having a particularly low average payment value (66 units).

This analysis suggests that credit cards are the preferred payment method on the Olist platform, likely due to the flexibility of payment installments and higher transaction amounts.




