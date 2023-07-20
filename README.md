# E-commerce_store_data_analysis

## Abstract

The dataset at hand encompasses transnational data, encompassing all transactions between 01/12/2010 and 09/12/2011, associated with a UK-based and registered non-store online retail company. The company's core focus revolves around the sale of distinctive all-occasion gifts. Remarkably, a substantial portion of the company's clientele consists of wholesalers. The project's objective entails delving into the dataset, uncovering its intrinsic characteristics, and providing answers to questions posed by a stakeholder.

## Variabeles

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
1. What are the key customer segments based on their purchasing behavior during the time period?

During the process of cleaning the dataset and conducting Exploratory Analysis, I recognized the importance and necessity of segmenting the products into categories or segments. This segmentation was undertaken to facilitate easier and faster responses to my stakeholder's inquiries. As a result, a significant amount of time was invested in studying the data and grouping the products into six categories. These categories are based on how our customers interact with us, ranging from their most desired items to those they seldom inquire about. 

*Results*: 

![image](https://github.com/LouisLiron/E-commerce_store_analysis/assets/124049051/fd74edc8-1429-4010-bc50-7f7a24971776)

Let's delve into the information provided in the image above. Firstly, we can infer from the table that a significant number of our customers are interested in Home and Office Decor items. This category includes products such as Place setting white heart, set of three heart cookie cutlery, ribbon reel Christmas sock bauble, ribbon reel hearts design, and many more. These items are commonly used for home and office decoration or practical use in these spaces.

During the observed time period, our customers, who are predominantly wholesalers, made purchases of products from this Home and Office Decor category, amounting to over 6.6 million pounds. The total number of items purchased within this category was 327,647, contributing to 62% of the total sales made last year, securing the top spot in the list of items bought.
