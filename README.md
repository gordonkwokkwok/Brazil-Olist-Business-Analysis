# Brazil-Olist-Business-Analysis

## Brief
Olist Store is the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. The Brazilian ecommerce public dataset of orders (from 2016 to 2018) made at Olist Store is provided to your company for analysis.

Your manager is asking you to critically analyse the provided datasets using Business Intelligence tools and provide some marketing findings / recommendations in a report format. The dataset has information of 100k orders made at multiple marketplaces in Brazil. Its features allow viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. A geolocation dataset that relates Brazilian zip codes to lat/lng coordinates is also integrated in the dataset.

After a customer purchases the product from Olist Store, a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where they can give a note for the purchase experience and write down some comments.

## Objective
1. Create data pipeline to ingest data in PostgreSQL or SQL server database
2. Use Power BI to answer following questions:
    - How many customers, orders, and orders per customer does the company have?
    - What is the number of customers by state?
    - What is the number of orders by month?
    - What are the top 5 product categories?
3. Visualise the company’s customers’ demographics, sales trend, orders by categories, orders changes by year, etc. and use Power BI to help make better decisions
4. Map and compare report data with data from database query to validate the reports (functional testing).
5. Critically analyse relevant data using statistical methods (e.g., Predictive Modelling or Machine Learning)
6. Provide some recommendations and improvements (please refer to point 3 in the project description)


## Prerequisite
Use "!pip install --" command to install the following libraries:
```
!pip install os
!pip install pandas
!pip install sqlalchemy
!pip install transformers
!pip install -U deep-translator
```

## Database Schema
The scraped data will be cleaned, transformed, loaded and stored in MySQL Database:
<img width="800" src="https://user-images.githubusercontent.com/112631794/200159344-c0ffd689-1486-48a5-b060-1d513b77830c.png">


## Power BI Dashboard
### P.1 Home
<img width="800" alt="1_home" src="https://user-images.githubusercontent.com/112631794/203075509-ea97c94a-348f-4e82-8ae1-513e253b05bd.png">

### P.2 Customer
<img width="800" alt="2_customer" src="https://user-images.githubusercontent.com/112631794/203076162-31f66365-9d2b-4c50-8421-61cbdc16db4e.png">

### P.3 Delivery
<img width="800" alt="3_delivery" src="https://user-images.githubusercontent.com/112631794/203076464-dd0ce43d-e62f-477a-9cfc-9690ccaa9059.png">

### P.4 Satisfactory
<img width="800" alt="4_satisfactory" src="https://user-images.githubusercontent.com/112631794/203076510-36c2c945-e27a-4f5f-b60e-e3ae2b4bc2b2.png">

### P.5 Forecast
<img width="800" alt="5_forecast" src="https://user-images.githubusercontent.com/112631794/203076531-4ea68c92-5b68-45b9-8410-8e14c1708110.png">

## Contributers
- [Frankie Lam](https://www.linkedin.com/in/frankie-lam-609732248/)
- [Gordon Kwok](https://www.linkedin.com/in/gordonkwokch/)
- [Janny Leung](https://www.linkedin.com/in/janny-leungjingyi/)
- Natalie Lau
