

## Balanced_Tree_DannyMA_7th_Case_Study
## DANNY MA 7TH CASE


## Introduction:
Balanced Tree Clothing Company prides themselves on providing an optimised range of clothing and lifestyle wear for the modern adventurer! Danny, the CEO of this trendy fashion company has asked you to assist the team’s merchandising teams analyse their sales performance and generate a basic financial report to share with the wider business.
Available Data For this case study there is a total of 4 datasets for this case study - however you will only need to utilise 2 main tables to solve all of the regular questions, and the additional 2 tables are used only for the bonus challenge question!

Product Details balanced_tree.product_details includes all information about the entire range that Balanced Clothing sells in their store.

<img width="404" height="510" alt="385222379-cf86646a-16c8-466d-8c41-4bd72d714711" src="https://github.com/user-attachments/assets/fabe4bb7-799f-452c-b8c5-a93a50b0a119" />


Product Sales balanced_tree.sales contains product level information for all the transactions made for Balanced Tree including quantity, price, percentage discount, member status, a transaction ID and also the transaction timestamp.

<img width="537" height="428" alt="384959821-d2d90bd2-ec66-4b03-b16c-e6dfaa7e0b7f" src="https://github.com/user-attachments/assets/386687c8-676d-43a8-ad3b-4cd36bbc4c73" />


Product Hierarcy & Product Price Thes tables are used only for the bonus question where we will use them to recreate the balanced_tree.product_details table.

<img width="538" height="357" alt="384959914-1cfd5352-eac4-46fc-b526-1436530aaeb7" src="https://github.com/user-attachments/assets/734160bf-b1c7-410f-a8cb-b99a280cdf4e" />


balanced_tree.product_prices

<img width="330" height="559" alt="384960056-87af078c-605f-4f4b-90cd-6d0ad195f207" src="https://github.com/user-attachments/assets/aa9f4ce0-4dc9-49f8-b39e-ed4d69afaed5" />


Interactive SQL Instance You can use the embedded DB Fiddle below to easily access these example datasets - this interactive session has everything you need to start solving these questions using SQL. You can click on the Edit on DB Fiddle link on the top right hand corner of the embedded session below and it will take you to a fully functional SQL editor where you can write your own queries to analyse the data. You can feel free to choose any SQL dialect you’d like to use, the existing Fiddle is using PostgreSQL 13 as default. Serious SQL students will have access to the same relevant schema SQL and example solutions which they can use with their Docker setup from within the course player!
Case Study Questions The following questions can be considered key business questions and metrics that the Balanced Tree team requires for their monthly reports.
Each question can be answered using a single query - but as you are writing the SQL to solve each individual problem, keep in mind how you would generate all of these metrics in a single SQL script which the Balanced Tree team can run each month.
High Level Sales Analysis What was the total quantity sold for all products? What is the total generated revenue for all products before discounts? What was the total discount amount for all products?
Transaction Analysis How many unique transactions were there? What is the average unique products purchased in each transaction? What are the 25th, 50th and 75th percentile values for the revenue per transaction? What is the average discount value per transaction? What is the percentage split of all transactions for members vs non-members? What is the average revenue for member transactions and non-member transactions?
Product Analysis What are the top 3 products by total revenue before discount? What is the total quantity, revenue and discount for each segment? What is the top selling product for each segment? What is the total quantity, revenue and discount for each category? What is the top selling product for each category? What is the percentage split of revenue by product for each segment? What is the percentage split of revenue by segment for each category? What is the percentage split of total revenue by category? What is the total transaction “penetration” for each product? (hint: penetration = number of transactions where at least 1 quantity of a product was purchased divided by total number of transactions) What is the most common combination of at least 1 quantity of any 3 products in a 1 single transaction?
Reporting Challenge Write a single SQL script that combines all of the previous questions into a scheduled report that the Balanced Tree team can run at the beginning of each month to calculate the previous month’s values. Imagine that the Chief Financial Officer (which is also Danny) has asked for all of these questions at the end of every month. He first wants you to generate the data for January only - but then he also wants you to demonstrate that you can easily run the samne analysis for February without many changes (if at all). Feel free to split up your final outputs into as many tables as you need - but be sure to explicitly reference which table outputs relate to which question for full marks :)

Bonus Challenge Use a single SQL query to transform the product_hierarchy and product_prices datasets to the product_details table.

Hint: you may want to consider using a recursive CTE to solve this problem!

Conclusion Sales, transactions and product exposure is always going to be a main objective for many data analysts and data scientists when working within a company that sells some type of product - Spoiler alert: nearly all companies will sell products! Being able to navigate your way around a product hierarchy and understand the different levels of the structures as well as being able to join these details to sales related datasets will be super valuable for anyone wanting to work within a financial, customer or exploratory analytics capacity. Hopefully these questions helped provide some exposure to the type of analysis we perform daily in these sorts of roles.

There is link: https://8weeksqlchallenge.com/case-study-7/
