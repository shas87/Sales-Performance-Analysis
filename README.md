# Maven Toys Sales Performance Analysis
In this project, I will be assuming the role of a analyst who has just been hired by this fictional company - Maven Toys. As they look to expand their business with new stores, they've brought me in to analyze interesting patterns and trends in their data and help them make informed decisions.

# Tools used
MS-Excel

# Objective
Create an executive dashboard which shows key metrics like revenue, profit, loss, inventory, out of stock products. It should be possible to select the date and time, store and product in the excel dashboard and data should change to reflect the applied  filters

Answer the folowing questions:
1. Which is the most profitable store?
2. List down top 5 most profitable products
3. List down most in demand product
4. Which store shows most potential and should get investment?
5. Which product shows least promise and should be discontinued? 

# Data Modeling
Products (35 unique products) -
- Product_ID - Unique ID given to each product offered
- Product_Name - Unique name given to each product offered
- Product_Category - Category group assigned to each product based on its characteristics/utility
- Product_Cost - Expense incurred for making/attaining the product, in US dollars
- Product_Price - Price at which the product is sold to customers, in US dollars

Stores (50 different stores)
- Store_ID - Unique store ID given to each toy store
- Store_Name - Unique store name given to each toy store
- Store_City - City in Mexico where the store is located
- Store_Location - Classification of location in the city where the store is located (Downtown,
- Commercial, Residential, Airport)
- Store_Open_Date - Date when the store was opened

Sales 
- Sale_ID - Unique Sale_ID for each transaction conducted in a store
- Date - Date on which the transaction occurred
- Store_ID - Unique store ID given to each toy store
- Product_ID - Unique ID given to each product offered
- Units - No of units of the product sold

Inventory:
- Store_ID - Unique store ID given to each toy store
- Product_ID - Unique ID given to each product offered
- Stock_On_Hand - Stock quantity of the product in the store

one to many relatinships
