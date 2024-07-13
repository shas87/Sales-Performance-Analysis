# Maven Toys Sales Performance Analysis
In this project, I will be assuming the role of an analyst who has just been hired by the company : Maven Toys. As they look to expand their business with new stores, they've brought me in to analyze patterns and trends in their data and help them make informed decisions.

**Dataset**<br/>
This particular dataset contained multiple tables: Sales, Inventory, Products, Stores data wasn't just a singular table full of data, an understanding of how to join or establish relationship between different tables without having redundant or repeating records were important.

# Objective
Create an executive dashboard which shows key metrics like revenue, profit, loss, inventory, out of stock products. It should be possible to select the date and time, store and product in the MS-Excel dashboard and data should change to reflect the applied  filters.

Answer the following questions:
1. Which is the most profitable store?
2. List down top 5 most profitable products.
3. List down most in demand product.
4. Which store shows most potential and should get investment?
5. Which product shows least promise and should be discontinued?
6. What is our market penetration? That is, how many stores and cities are we currently in? 
7. Which product category drives the highest profits?

# Data Model
Products (35 unique products):
- Product_ID - Unique ID given to each product offered
- Product_Name - Unique name given to each product offered
- Product_Category - Category group assigned to each product based on its characteristics/utility
- Product_Cost - Expense incurred for making/attaining the product, in US dollars
- Product_Price - Price at which the product is sold to customers, in US dollars

Stores (50 different stores):
- Store_ID - Unique store ID given to each toy store
- Store_Name - Unique store name given to each toy store
- Store_City - City in Mexico where the store is located
- Store_Location - Classification of location in the city where the store is located (Downtown,
- Commercial, Residential, Airport)
- Store_Open_Date - Date when the store was opened

Sales:
- Sale_ID - Unique Sale_ID for each transaction conducted in a store
- Date - Date on which the transaction occurred
- Store_ID - Unique store ID given to each toy store
- Product_ID - Unique ID given to each product offered
- Units - No of units of the product sold

Inventory:
- Store_ID - Unique store ID given to each toy store
- Product_ID - Unique ID given to each product offered
- Stock_On_Hand - Stock quantity of the product in the store

**one to many relationship between tables:**
1. Products --> Sales
2. Stores --> Sales
3. Products --> Inventory
4. Stores --> Inventory

# Deliverable
A dashboard or report containing analysis and actionable insights.

# Dashboard 

![dash](https://github.com/shas87/excelProject/assets/139848347/cbd012b1-9850-401e-8fb6-3e72c37c9752)

[Dashboard](https://drive.google.com/drive/folders/1aMsxzQNsM-9YcWLoz2ZbOMelMGfwLBcT?usp=sharing)

**1. Which is the most profitable store?** <br/>

Maven Toys Ciudad de Mexico 2

![d2](https://github.com/shas87/excelProject/assets/139848347/57b337b0-0ea2-4567-a41f-f2d75a52e640)

**2. List down top 10 most profitable products.**

![d1](https://github.com/shas87/excelProject/assets/139848347/c67857cd-564c-4df9-a9a9-2dfe700048ec)

**3. List down the most in demand product.** <br/>

Colorbuds

![image](https://github.com/shas87/excelProject/assets/139848347/6598ed26-8ba9-4e76-87dd-9fbcff683d22)

**4. Which store shows most potential and should get investment?** <br/>

Maven Toys Ciudad de Mexico 2, should get more investment because maximum profit is generated from this store.

**5. Which product shows least promise and should be discontinued?** <br/>

Classic Dominoes product should be discontinued because revenue and number of units sold both are on the lower side.

![52](https://github.com/shas87/excelProject/assets/139848347/e906aee2-df33-46f9-a3de-33ad172d874b)  ![51](https://github.com/shas87/excelProject/assets/139848347/5aa2f2f9-c529-4fd7-a981-657fea8c0e6f)

**6. What is our market penetration? That is, how many stores and cities are we currently in?** <br/>

Total number of stores: 50 <br/>
Number of cities: 29 <br/>

![2](https://github.com/user-attachments/assets/904b8aa4-cdf3-4ac9-84c3-2c10f277ccd6)

**7. Which product category drives the highest profits?** <br/>

Largest profit among the five product categories was observed in Toys, reaching $1,079,527. This figure was 113.46% higher than the lowest total profit, which was in the Sports & Outdoors category at $505,718<br/>

Toys accounted for a significant portion of the total profits, contributing to 26.89% of the overall profits across all five product categories.

![3](https://github.com/user-attachments/assets/1263b2d3-b9cf-4628-bb1d-c80730c05eb1)

**How would you advice Maven Toys to proceed with their expansion based on the insights you've garnered?** <br/>

- Based on the insights gathered from my analysis, Maven Toys can approach the expansion based on the store location. Maven Toys should consider expanding further in downtown areas, especially in cities with strong economic activity and high population density. There should be a focus on storefront visibility and unique promotions to capture the attention of passersby.

![newsnip](https://github.com/user-attachments/assets/84c68976-c682-4d00-82d0-4461ef778217)

- They should increase their offering in Toys and Electronics product category.

![81](https://github.com/user-attachments/assets/d8586f0b-4ab8-4c8e-b4c1-58091c8d2edb)

![3](https://github.com/user-attachments/assets/94f10e39-be96-470a-a7ea-718a752ee397)
   
