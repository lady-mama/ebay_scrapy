# Purpose of ebay_scrapy for Ebay sellers
To quickly/statistically understand the market with certain keywords,
to understand how to complete the new product information.

1. When you search type word(s) on ebay search, you can see the popular/reasonable products at the top page.
Actually, the formula of being the popular products is similar as SNS.
The way of making our new products up to the top page is the "Organic Advertisement" without paying anything.

2. Before the sellers upload their products, it is important to understand the "Organic Advertisement" tactic.
Using the proper keywords on the product title, matching the certain categories are couple of the major tactics.
Therefore, ebay_scrapy can help you to decide if you will upload the product, and how you need to write the product details. 

# How to use ebay_scrapy
Write the keyword(s) that you want to explore.
If you want detail analyzing, please keep going.

# How to get the APP ID
https://developer.ebay.com/ <- APP ID providing url
You need to sign up for developer ebay and ask the authority to approach the api with APP ID.

# Understanding of Ebay
Ebay has the duration of selling in the market, which makes all products 'Start time' and 'End time'.
Ebay let sellers sell used-products as well. At ebay_scrapy, we can only see the new products, not used.

# DataFrame Description
'Title' : Title of the parsed products
'Category' : Category of the parsed products
'Price' : Price of the parsed products
'ShippingCost' : Shipping Cost of the parsed products
'Starttime' : Uploaded time on ebay for each parsed products
'Endtime' : To-be-deleted time on ebay for each parsed products

# Up-coming
Offering the information of keyword-related products.
Deeper data analyzing with regressions.