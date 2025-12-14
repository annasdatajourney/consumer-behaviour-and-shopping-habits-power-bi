# Consumer Behaviour and Shopping Habits – Power BI

## Project Overview

This project presents an end-to-end Power BI analysis of consumer behaviour and shopping habits based on a real-world retail dataset.  
The objective was to transform raw transactional and behavioural data into clear, business-focused insights covering customers, products, discounts, reviews, and delivery performance.

The project includes:
- data cleaning and transformation in Power Query,
- relational data modelling,
- interactive dashboards,
- and business insight generation.

---

## Data Source

The dataset used in this project comes from **Kaggle** and represents consumer shopping behaviour, including:
- customer demographics,
- purchase history,
- product and category data,
- discounts and promotions,
- payment methods,
- delivery types,
- customer review ratings.

---

### Data preparation (Power Query)

The dataset was cleaned and prepared using Power Query before building the data model and visualisations.

Applied transformations included:
- renaming columns
- changing data types
- filtering rows
- handling missing values
- creating calculated columns

Power Query transformations were applied to the following queries:
- [shopping_trends](power_query/shopping_trends.png)
- [shopping_trends (continued)](power_query/shopping_trends2.png)
- [shopping_behaviour_updated](power_query/shopping_behaviour_updated.png)



---

## Data Model

A relational data model was created to support accurate filtering and aggregation across the report.

The model includes:
- transactional and behavioural tables,
- a calendar table for time-based analysis,
- one-to-many relationships following best practices.

![Data Model Diagram](screenshots/model/data_model.png)


---

## Dashboard Pages

The report consists of five dashboard pages:

### 1. Summary
High-level overview of sales value, average purchase amount, number of customers, payment methods, and overall trends.

![Summary](screenshots/summary.png)

---

### 2. Customer Analysis
Customer demographics, returning customers, purchase frequency, seasonality, and geographic distribution.

![Customer Analysis](screenshots/customer_analysis.png)

---

### 3. Products and Categories
Most frequently purchased products, category split, product colours, sizes, and seasonality.

![Products and Categories](screenshots/product_and_categories.png)

---

### 4. Special Offers and Discounts
Analysis of discounts, promotional codes, subscription impact, and comparison of discounted vs non-discounted purchases.

![Special Offers and Discounts](screenshots/special_offers_and_discounts.png)

---

### 5. Customer Reviews and Delivery
Customer review ratings (1-5 scale), product-level review performance, and delivery method analysis.

![Customer Reviews and Delivery](screenshots/customer_reviews_and_delivery.png)

---

## Key Insights

- Customer review ratings vary by product and delivery method.
- A small number of product categories generate the majority of purchases.
- Discounts and promotions have a measurable impact on purchasing behaviour.
- Free and standard shipping account for the largest share of orders.
- Returning customers show stable purchasing patterns over time.

---

## Tools Used

- Power BI Desktop  
- Power Query  
- DAX  
- Kaggle dataset  
- GitHub


