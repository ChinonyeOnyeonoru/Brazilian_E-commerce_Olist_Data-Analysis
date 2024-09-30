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

1.	**Percentage Payment Value by Payment type**
   
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

  3.	**Sum of Payment Installments by Payment Type**

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

**Key Insights/ Suggestions**:
 
- Credit Card is the dominant payment type, both in terms of the total payment value (78.34%) and the highest average payment value (163 units).
- Boleto follows as the second most popular payment method, though it is significantly lower in terms of the number of installments and average payment value.
- Voucher and Debit Card are used sparingly, with vouchers having a particularly low average payment value (66 units).

This analysis suggests that credit cards are the preferred payment method on the Olist platform, likely due to the flexibility of payment installments and higher transaction amounts. Which can be as result of misappropriate distribution of payment method amongst Olist customers. 

Also, The credit card shows the wealthier audience. There should be further investigation in order to increase reach across demographics.

Lastly, the voucher conditions should be improved such as duration, installment payment. This might reduce the significant drop of the quantity.  

### Olist Sentiment Analysis 

![image](https://github.com/user-attachments/assets/4649e70f-039d-4c6b-852a-5ce409ace6ce)


This report presents the analysis of customer sentiments from the reviews of the Olist platform. The reviews were classified into three categories: Positive, Negative, and Neutral sentiments, and the analysis shows the key insights into review scores and reoccurring themes for each sentiment type. From the review scores, 4-5 are rated as Positive reviews, 3 are rated as Neutral reviews, and 1-2 are rated as Negative reviews.
 
1.	**Total Review Score by Sentiment Type**
   
- Positive Reviews: This is the majority of the review, which has 33k total review scores.
- Negative Reviews: The negative review has 3k total review scores.
- Neutral Review: This makes up 2k total review scores.
 
According to the bar chart, the distribution highlights a predominantly positive sentiment towards Olist's products and services.
 
2.	**Count Review Scores by Sentiment Type**
   
- Positive sentiments: This shows 69.67% of the total reviews.
- Negative Sentiments: This makes up 22.80% of the total reviews.
- Neutral sentiments: This accounts for 7.49% of total reviews.
 
 This analysis confirms that the majority of customers have a favourable experience, with a minority expressing dissatisfaction.
 
3.	**Common Themes in Positive Reviews**
The positive reviews contain phrases like:
- Product-related: “produto” (product), qualidade” (quality), “perfeito” (perfect), “bom” (good), and “lindo” (beautiful).
- Delivery: “entrega” (delivery), “entregou” (delivered), “chegou” (it arrived), “rápido” (fast).
- Customer Experience: “atemdimento” (service), “satisfeito” (satisfied), “recomendo” (recommend), and “parabens” (congratulations).

Customers displayed the satisfaction of the quality of the products, timely delivery, and services through the positive comments.
 
4.	**Common Themes in Negative Reviews**
   
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


### Olist Product Analysis


![image](https://github.com/user-attachments/assets/5b9f5c8e-677d-41e2-90e2-29b6b9586b42)

This report presents an analysis of the products available at the Olist store. With the focus on the most popular product category, customer distribution by state, and the highest-rated product categories. 

1. **Top 10 Products Based on Orders**
   
The bar chart in the top left displays the top 10 product categories based on orders:
- Bed, Bath, and Table: With 14,000 thousand ordered products. This product category becomes the most popular.
- Furniture & Décor and Health & Beauty: These two product categories made a significant volume of orders, with 12,000 and 11,000, respectively.
- Sports & Recreation, Computers & Accessories ordered the same number of items with 10,000, while Housewares, Watches & Gifts, Garden & Tools, Telephony, and Auto are other noteworthy categories.
 
2. **Count of Product by Customer State**
   
The bar chart in the upper right shows the distribution of product purchases by state.

- São Paulo (SP): The capital of Brazil (São Paulo) has the highest number of purchases, with over 19.1k.
- Rio de Janeiro (RJ) and Minas Gerais (MG) also have significant purchase volumes of 7.9k and 7.3k, but with a hug different between São Paulo (SP).
- Other Staes: The distribution displays smaller purchase volumes across different states, with a long tail for regions with fewer purchases.
 
This indicates that a significant portion of purchases are made in Brazil's more populous state.

3.	**Count of Product Categories by Customer State**
 
The treemap visualises the count of product category purchases by customers from different states.
- SP (São Paulo): Due to its wide range of preferences and large customer base, it stands out as the state with the largest diversity in product categories.
- MG (Minas Gerais) and RJ (Rio de Janeiro): These two states have the same count of 69. And they are the second with the largest diversity in product categories.
- Smaller States: AP (Amapá), RR (Roraima), and AC (Acre). There are fewer purchases and a lesser variety of products in states.
 
This demonstrates that states with larger populations have higher purchasing power and exhibit a greater range of consumer preferences.
 
4.	**Highest-Rated Product Categories (Top 10)**
 
The bar chart in the bottom right shows the top 10 of the highest rating of the product categories with the highest average review scores.
- Health & Beauty and Sports & Leisure: They have the highest average review scores with 4.14 and 4.11, respectively. This indicates that they have strong customer satisfaction in these areas.
- Auto, Housewares, and Garden &Tools: With scores ranging from 4.07 to 4.04, also do well third and fourth products.
- Bed, Bath & Table: The remaining five categories, with average scores ranging from 4.02 to 3.90, are watches & gifts, telephony, computers & accessories, furniture & decor,
 
These categories show high levels of satisfaction; the majority of highly rated products have average scores above 4.0, indicating a steady level of quality.
 
**Key Insights**:
 
**Popular Product Categories**: The most popular products on Olist are home goods (Bed, Bath & Table, Furniture, and Housewares), personal care (Health & Beauty), and electronics (Computers & Accessories).
 
**State Distribution**: São Paulo (SP) is the most product-purchasing state in terms of both quantity and variety of product categories, with Rio de Janeiro (RJ) and Minas Gerais (MG) following closely.

**Customer Satisfaction**: With most top-rated categories scoring above 4.0, it is evident that customers are especially happy with certain product kinds. Examples of these categories are Health & Beauty and Sports & Leisure.
 
All in all, this analysis shows that there is strong product performance in key categories and regions, and there are chances to keep focussing on highly rated and in-demand product segments.
 
![image](https://github.com/user-attachments/assets/5815b627-23a5-4f6a-8c7d-8f6910417a91)






![image](https://github.com/user-attachments/assets/974df34e-9d39-491e-8eb1-4f1f1dfedc69)
###**Report on Olist Business Analysis**

The distribution of Olist's customers, order approvals, and delivery performance over the years and locations are examined in this study along with other key indicators. The insights offer a thorough understanding of consumer behaviour and operational effectiveness.

1. **Customers Distribution by State (Top 5)**
This displays the top five customer distributions by their state:

- **São Paulo (SP)**: With 41.7K clients, SP leads the highest number of customers.
- **Rio de Janeiro (RJ)**: With 12.9K users, RJ ranks second-largest customer base.
- **Others**: Minas Gerais (MG), Paraná (PR), and Rio Grande do Sul (RS): This state accounts for 11.6K, 5.5K, and 5.0K customers, respectively, come next.

This analysis indicates Brazil's Southeast and South, especially in São Paulo, have a substantial customer base.

2. **Approved Orders by Year and Region**

This report shows the number of approved orders from 2016 to 2018 in each region, namely, Central-West, North, Northeast, South, and Southeast. 



  ||Central-West|North|Northeast|South|Southeast|
  |--------|--------|--------|--------|--------|--------|
  |2016|0.016k|0.06k|0.03k|0.049k|0.18k|
  |2017|2.5k|0.9k|4.4k|6.4k|29.1k|
  2018|3.2k|0.9k|4.9k|7.5k|37.6k

- **2016**: The year significantly had the least approved order in all the regions, with 0.016k in the Central-West, 0.06k in the North, 0.03k in the Northeast, 0.049k in the South, and 0.18k in the Southeast, respectively.
- **2017**: These years had the second highest approved orders with 29.1k in the Southeast.
- **2018**: This year had the highest approved orders, with 37.6k in the Southeast.

There was significant growth in all the regions. The South region outperformed other regions in approved orders. Indicating that both the customer region and orders have consistent growth annually.

3.	**Order Delivery by Year, Quarter, and Month**

This analysis displays the delivery performance of orders between 2016 and 2018. 

- **2016**: They had the lowest deliveries in Quarter 3 September 2016, with 1 (0.0k). 
- **2017**: Having the highest deliveries in Quarter 4 November 2017, with 7221 (7.1k),

- **2018**:  The year had the second highest deliveries in Quarter 1 March, with 7219 (7.1k) and a significant sudden decrease from Quarter 3 August to September 2018. 

There was a rise and fall in delivery from Quarter 3 September to Quarter 4 December 2016. The delivery raised from 1 in September to 279 in Quarter 4 October of the same year. The delivery trends indicated a consistent monthly performance and a notable increase in deliveries year over year. This might be as a result of seasonal or promotional factors.

4.	**Top 5 States and Regions by Customer Count**

This report shows the South and Southeast made it to the top five regions, having MG, SP, RJ, PR, and RS as the states. 

- **São Paulo (SP)**: With 41746, SP had the highest customer base.
- **Rio de Janeiro (RJ)**: With 12852, RJ is the second highest state by customer count.
- **Minas Gerais (MG)**: Has 11635 customers.
- **Rio Grande do Sul (RS)**: Has 5466 customers.
- **Paraná (PR)**: With 5045 customers. 

From the geographic distribution, it shows that (SP) has then dominant state. And the customers spread across all 27 Brazilian states. 


**Olist Business Analysis 2**


![image](https://github.com/user-attachments/assets/f70c9f8a-71e0-4d26-a575-70016569379d)


This analysis shows the key business metrics for Olist, such as orders, customer statistics, freight and payment values, and performance by year. Here are the key insights and suggestions. 

1.	**Total Orders and Total Customers**:

-	Total Orders: The Olist platform had 96.46k of total orders.
-	Total Customers: There were 99.44K total unique customers on the platform.

This indicates a nearly one-on-one ratio between orders and customers, indicating that the majority of customers placed a single order during the study period.

2.	**Average Price and Freight Value**: 
-	Average Order Price: There were 120.65 units for the average order price per order.

3.	**Average Freight Value and Order Status**: 
Freight Value:  depending on the order status, the average freight amount varies. That is, order status has an impact on freight value. 
- Delivered Orders: Average freight cost of 19.9.
- Cancelled Orders: With an average freight cost of 14.6.
This shows that cancelled orders incurred lower average shipping costs than delivered orders, likely as a result of fewer logistical requirements.

4.	**Freight Value and Price Trends by Year**:

- 2016: With 0.006M in freight value and 0.04M in price.
- 2017: Freight value of 0.9M and 5.9M in 2017.
- 2018: With 1.2M in freight value and 7.2M in price. 

From the report, the freight value increased from 0.006M in 2017, 0.9M in 2017, 1.2M in 2018, while the price also had an increase with 0.04M in 2016, 5.9M in 2017, 7.2M in 2018. Over the years, there has been a significant rise in sales and freight costs, indicating potential changes in freight-related expenses or pricing strategies.

5.	**Customer City and State (Top 10 Customer City)**:

The report counts the orders by state and customer city, with the top ten cities accounting for a large portion of the total orders:

- Major Cities: Cites like Xanxere had 29 total orders, Xaxim had 10 orders, and Xinguara had 9 orders, having the majority of orders.
-	Minority Cities: Ze doca, Xiqe-xique, Xapuri, Xavantina, Zacarias, Zortea, and Xexeu had lesser orders. 

Olist's customer geographic distribution is examined, with a focus on the leading customer cities and states. The majority of the customers are in states like SC, Pará (PA), Maranhão (MA), Bahia (BA), Acre (AC), SC, São Paulo (SP), SC, and Pernambuco (PE).

6.	**Standard Deviation of Payment Value by Year and Payment Type**: 


The analysis displays the standard deviation of the payment value along with a variety of payment methods, such as boleto, credit card, debit card, and voucher. It shows the variation in payment amounts by displaying the activities along with the year and payment type. For example: 


||Boleto|Credit Card|Debit Card|Voucher|
  |--------|--------|--------|--------|--------|
  |2016|169.7|196.0|55.4|54.9|
  |2017|217.3|228.2|80.6|84.5|
  |2018|211.8|269.7|289.7|95.8|


Payment Trends:  From 2018 to 2018, there was a minor increase in the average payment value, which has remained relatively stable over the years. With the consistency in the standard deviation of payment values, it indicated a stable payment pattern.  
 
**Key Insights/Recommendations**:

-	Steady Growth: The analysis shows a strong growth trend in both sales volume and freight expenses between 2016 and 2018, indicating a growing market for Olist's stores.
-	Credit Card dominating: The average payment value and its variability both show that consumers prefer credit cards for larger-value purchases.
-	Geographic Distribution: Olist's customer base is widely distributed over several states, while a considerable proportion of orders are placed in the company's top-performing cities.
-	Freight Efficiency: Delivered orders incurred higher freight costs than cancelled ones, and when sales volumes grew over years, there was a significant increase in freight expenses.
-	Optimise for High-Value Transactions: In order to increase sales even more, Olist should concentrate on enhancing credit card customers' rewards and incentives. This is because credit cards are used for larger transactions. 
-	Improvement in logistics for Cancelled Orders: In order to minimise losses associated with cancellations, Olist should investigate why cancelled orders incurred a slightly lower freight value.
-	Expansion: Although some states and cities show strong performance. There should be more expansion to other minor cities; there should be potential growth in such areas. Which can be done through targeted marketing campaigns. 
