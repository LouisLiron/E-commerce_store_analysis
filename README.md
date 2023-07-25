# E-commerce_store_data_analysis

## Abstract

The dataset at hand encompasses transnational data, encompassing all transactions between 01/12/2010 and 09/12/2011, associated with a UK-based and registered non-store online retail company. The company's core focus revolves around the sale of distinctive all-occasion gifts. Remarkably, a substantial portion of the company's clientele consists of wholesalers. The project's objective entails delving into the dataset, uncovering its intrinsic characteristics, and providing answers to questions posed by a stakeholder.

## Variables

- InvoiceDate - This refers to the specific date on which a particular transaction occurred. It is in the MM/DD/YYYY format.
- Description - This provides information about the product being purchased, along with a few details about it.
- Categories - This column categorizes the items in the Description column into different groups.
  - Home And Office Decor
  - Gifts
  - Stationary
  - Jewelry
  - Signs
  - Personal
  - Quantity - This column indicates the quantity or number of items purchased.
  - UnitPrice - This tells us the price of the individual items.
- Total - This column represents the product of the Quantity and UnitPrice columns. 
- Country - This column specifies the country from which the order is being received.

## Objective
The primary aim of this analysis is to address the following questions:
1. What are the key customer segments based on their purchasing behavior during the time period?
2. Can you identify any seasonal patterns or trends in sales for different product categories?
3. Which are the top selling products overall?

## Analysis
### 1. What are the key customer segments based on their purchasing behavior during the time period?

During the process of cleaning the dataset and conducting Exploratory Analysis, I recognized the importance and necessity of segmenting the products into categories or segments. This segmentation was undertaken to facilitate easier and faster responses to my stakeholder's inquiries. As a result, a significant amount of time was invested in studying the data and grouping the products into six categories. These categories are based on how our customers interact with us, ranging from their most desired items to those they seldom inquire about. 

*Results*: 

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/fd74edc8-1429-4010-bc50-7f7a24971776)

Let's delve into the information provided in the image above. Firstly, we can infer from the table that a significant number of our customers are interested in Home and Office Decor items. This category includes products such as Place setting white heart, set of three heart cookie cutlery, ribbon reel Christmas sock bauble, ribbon reel hearts design, and many more. These items are commonly used for home and office decoration or practical use in these spaces.

During the observed time period, our customers, who are predominantly wholesalers, made purchases of products from this Home and Office Decor category, amounting to over 6.6 million pounds. The total number of items purchased within this category was 327,647, contributing to 62% of the total sales made last year, securing the top spot in the list of items bought.

The subsequent category in the dataset is the Gifts category, which accounts for 25% of the total items purchased from the store during the observed time period. This category reveals another group of products that customers are interested in after the Home and Office Decor items. Some of the items in this category include Blue dragonfly helicopters, red dragonfly helicopters, yellow shark helicopter, red shark helicopters, and more.

Following the Gifts category, we have the Signs category. Interestingly, we have a notable number of customers who purchase products from this category, prompting the creation of a separate category for analysis. Items in the Signs category comprise Airline Lounge, Metal sign, bathroom metal sign, area patrolled metal sign, fanny's rest stop metal sign, and others. This category only controls 5.9% of the total items bought during the time period.

Moving on to the sixth and final category, we have the Jewelry category. This category consists of purchases of items like earrings, necklaces, pendants, bracelets, and more. Being the last category in terms of the number of items bought from it, the Jewelry category has a 1.1% share in the total items purchased and records a total sales value of 123,382 pounds.

### 2. Can you identify any seasonal patterns or trends in sales for different product categories?
In order to analyze the trends and seasonality of various product categories, I conducted a visualization by plotting graphs and created a new file for better insight into the dataset's patterns. You can access this file named "Ecommerce_Product_trends_and_seasonality.ipnyb" to explore the trends and seasonal patterns of the products.

### Gifts category: 

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/4bd3100a-c899-46d3-b703-7838df7c4b59)

It can be reasonably inferred that the most predictable segments of this graph are likely to be the beginnings and endings of the year, as they coincide with periods of celebration, gift-giving, and festivities. This observation holds true for almost all the other graphs as well.

To start with, seasonality occurs when the performance of an event, such as sales, is consistently influenced by specific time periods within the dataset's timeframe. As depicted in the above graph, sales exhibit fluctuations during the mid part of the year, but from September onward, a noticeable rise in sales begins to occur. While this surge could potentially be influenced by external factors, it is reasonable to conclude that these particular times of the year hold significant importance for sales patterns.

### Home and Office Decor: 

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/dc17c465-a317-415b-818e-9c3e15c58c91)

The Home and Office Decor category, which stands out as the best-performing category in the dataset, reveals several noteworthy insights. Initially, the first six months showed relatively modest sales figures, lacking significant excitement. However, as we entered the seventh month, a noticeable rise in sales occurred. This upward trend continued steadily, with only a minor decline in the final months of the year.

The success of the Home and Office Decor category can be attributed to its offerings of decorative and beautification items, aligning with consumer preferences. The considerable sales in this category played a pivotal role in its remarkable success throughout the observed period.


### Signs category:

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/176dee71-abf0-4bf7-bb6f-3737df5c390f)


Moving on to the Signs category, an intriguing observation emerges from the graph. Similar to some other categories, the Signs category did not exhibit favorable performance for most of the year until a significant spike occurred in the month of August. Following this spike, the total sales of this category consistently remained above 50,000 pounds.


### Personal category: 

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/d2e5d452-b049-4c16-b561-b091d5ac9201)

Regarding the Personal category, it didn't exhibit significant activity during the first seven months, with sales remaining relatively low and stable without notable fluctuations or excitement. However, from July onward, there was a noticeable upward climb in sales, and this positive trend persisted throughout the dataset's timeframe.

When considering seasonality, there doesn't appear to be a distinct pattern of seasonally related fluctuations in sales for the Personal category. However, the dataset clearly indicates a definite and consistent upward trend, suggesting a positive trajectory in sales over time.The trend for the Signs category is undoubtedly upward, indicating a sustained growth pattern over time. This positive trajectory suggests that the Signs category has experienced notable improvements and promising prospects for continued success.

### Jewelry category:

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/8003f5db-f4ed-468c-8cfe-18c324ecf52e)

The performance of this category throughout the year has been remarkably dynamic and vibrant. Numerous significant spikes can be observed during various time periods. Notably, major spikes occurred in May, mid-July, and November, indicating periods of exceptional sales growth. However, there was also a noticeable decline in sales in February during the observed timeframe.

The constant fluctuations in sales generate considerable excitement in the overall performance of this category. Despite the ups and downs, a clear upward trend can be discerned, suggesting a positive overall trajectory in sales over time. Additionally, the absence of any distinct seasonality in sales patterns further contributes to the category's dynamic and ever-evolving nature.

### Stationary category:

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/20e36e86-f82c-4ae3-b3e0-4d87ef5a75c9)

For this category, had the dataset concluded in November, one could have confidently concluded that it experienced a positive and sustainable growth trajectory. However, the situation changes when considering the drastic decline in sales during November. Prior to that decline, the sales performance appeared quite promising, characterized by a steady upward trend without significant fluctuations.

The absence of seasonality in this category further supports the notion that its sales patterns do not follow a specific seasonal trend. While the abrupt decline in November may raise questions about the category's overall performance, the presence of an earlier upward trend indicates the potential for positive growth in the future, provided the November decline is addressed and managed appropriately.


### 3. Which are the top selling products overall, and are there any specific products that show a significant increase or significant decrease in sales?

To accurately analyze the data, a separate file named "Ecommerce_Best-and-worst-Products.ipynb" was created. In this analysis, the focus was on determining the percent change in product values over the dataset's timeframe.

When considering the increase and decrease in values, the percent change was calculated. For instance, if a product initially had a price of £10, a 100% increase would mean that the product's value at the end of the timeframe is now worth £20. This calculation is done as follows: £10 * 1.00 = £10 (increase of £10), £10 + £10 = £20.

Within the provided file, a table was generated, and the percent change of each item was computed. The results of this analysis are presented in the file for further examination and evaluation.

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/0eea772c-670a-4b33-ab75-615e71a2c0f2)

The table above showcases the top five items that have experienced significant increases in price or value. Topping the list is the Green Regency Teacup and Saucer, which exhibited an impressive 10379.23% increase in value. This remarkable growth is noteworthy. At the bottom of the table, the Rabbit Night Light shows the least increase with 2823.86%.

These five items stand out as the best performers in terms of price appreciation. For a comprehensive evaluation of all products and their performance, I invite you to explore the entire analysis presented in the "Ecommerce_Best-and-worst-Products.ipynb" file. It provides a detailed overview of the various items and their respective changes in value, enabling a deeper understanding of their market performance.


## Conclusion
Here are five great takeaways from this analysis; 

- Key Customer Segments: The Home and Office Decor category stands out as the most popular among customers, accounting for 62% of the total items purchased. Following closely is the Gifts category, with 25% of total purchases. Signs and Personal categories are also significant contributors, while Jewelry is the least preferred category.

- Seasonality and Trends in Sales: The analysis revealed distinct seasonal patterns and trends in sales for different product categories. Home and Office Decor showed an upward trend throughout the year, with significant spikes in August and September. Signs category experienced a notable surge in August. Personal category had an upward trend from July onward, while Jewelry had frequent spikes in sales throughout the year.

- Top Selling Products: The Green Regency Teacup and Saucer was the top-performing product with an impressive 10379.23% increase in value. The Rabbit Night Light showed the least increase at 2823.85%. The analysis provides further insights into other top-performing products.

- Dynamic Sales Performance: The Jewelry category displayed a dynamic sales performance, experiencing significant spikes in sales during May, mid-July, and November. This category showcased fluctuations and an overall upward trend.

- Data Analysis and Segmentation: Proper data cleaning and segmentation played a vital role in the analysis, enabling a more in-depth understanding of customer behavior and product performance.

These takeaways highlight crucial insights into customer behavior, product popularity, seasonal trends, and significant increases in product value. Further exploration in the provided files can lead to a deeper understanding of the dataset and its implications.
