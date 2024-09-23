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

This analysis suggests that credit cards are the preferred payment method on the Olist platform, likely due to the flexibility of payment installments and higher transaction amounts. Which can be as result of misappropriate distribution of payment method amongst Olist customers. 

Also, The credit card shows the wealthier audience. There should be further investigation in order to increase reach across demographics.

Lastly, the voucher conditions should be improved such as duration, installment payment. This might reduce the significant drop of the quantity.  

### Olist Sentiment Analysis 

![image](https://github.com/user-attachments/assets/4649e70f-039d-4c6b-852a-5ce409ace6ce)


This report presents the analysis of customer sentiments from the reviews of the Olist platform. The reviews were classified into three categories: Positive, Negative, and Neutral sentiments, and the analysis shows the key insights into review scores and reoccurring themes for each sentiment type. From the review scores, 4-5 are rated as Positive reviews, 3 are rated as Neutral reviews, and 1-2 are rated as Negative reviews.
 
1.	Total Review Score by Sentiment Type
   
- Positive Reviews: This is the majority of the review, which has 33k total review scores.
- Negative Reviews: The negative review has 3k total review scores.
- Neutral Review: This makes up 2k total review scores.
 
According to the bar chart, the distribution highlights a predominantly positive sentiment towards Olist's products and services.
 
2.	Count Review Scores by Sentiment Type
   
- Positive sentiments: This shows 69.67% of the total reviews.
- Negative Sentiments: This makes up 22.80% of the total reviews.
- Neutral sentiments: This accounts for 7.49% of total reviews.
 
 This analysis confirms that the majority of customers have a favourable experience, with a minority expressing dissatisfaction.
 
3.	Common Themes in Positive Reviews
The positive reviews contain phrases like:
- Product-related: “produto” (product), qualidade” (quality), “perfeito” (perfect), “bom” (good), and “lindo” (beautiful).
- Delivery: “entrega” (delivery), “entregou” (delivered), “chegou” (it arrived), “rápido” (fast).
- Customer Experience: “atemdimento” (service), “satisfeito” (satisfied), “recomendo” (recommend), and “parabens” (congratulations).

Customers displayed the satisfaction of the quality of the products, timely delivery, and services through the positive comments.
 
4.	Common Themes in Negative Reviews
   
The negative reviews frequently included terms linked to:
- Product Issues: “produto” (product), “defeituoso” (defective), “danificado” (damaged).
- Delivery Problems: “entrega” (delivery), “demorado” (delayed), “prazo” (deadline), “nao chegou” (didn’t arrive).
- Customer Service Complaints: “problema” (problem), “não” (no response), “retorno” (returned), “não recebi” (did not receive).
 
The negative feedback is mainly on the defective goods, delayed deliveries, and customer service issues.
 
5.	Count of Sentiment Types by Review Scores
   
This analysis shows the review scores for each sentiment, where every customer added a rating on the scale of 1–5 to the reviews:
- 5-Star Review: Positive reviews make up 55.05% of the score.
- 1-Star Reviews: 18.26% of reviews are unfavourable.
- 4-Star Reviews: 14.4% mainly positive
- 3-Star Reviews: 7.51% shows neutral to mildly positive reviews.
- 2-Star Reviews: 4.69% are leaning negative reviews.

It can be observed that although the majority of reviews are positive, a considerable percentage (more than 18%) are strongly negative, indicating improvement on the areas. 

Key Insights: 

**Strong Positive Sentiment**: A large portion of Olist customers expressed satisfaction, especially in the area of the quality of the product, timely delivery, and overall service.

**Concerns**: The Negative reviews are mainly from delayed or poor delivery, damaged products, and communication issues. Attention is needed to reduce negative feedback. 

**Neutral Reviews**: A portion of reviews is neutral, showing some customers are neither highly satisfied nor dissatisfied. 

In conclusion, while Olist has a favourable overall reputation, especially for product quality and delivery, improving customer satisfaction could further enhance customer satisfaction. 

![image](https://github.com/user-attachments/assets/5b9f5c8e-677d-41e2-90e2-29b6b9586b42)


