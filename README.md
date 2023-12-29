# Online-Payment-Platform
## Analysis on customers Online Payments

### Introduction
Company X is an online payment platform where consumer can pay bills, buy recharge,
transfer money etc.
Some of the billers on the platform are internet service companies, cable TV, Airlines,
Schools, Utility providers (PHCN, Waterboards, etc), Betting companies, Retail Stores, Hotel
and Travel etc

### Analytical

**1. Give top 3 metrics that defines the success of the platform**

- Successful to unsuccessful transactions ratio
- Chargebacks and bad debt
- Churn rate

**2. If you were to predict if a customer (consumers that use the platform) will churn (i.e. stop
using the platform) what factors/features will you consider?**

Among many, below are some major reasons why a customer leaves or never returns:

- Billing and Invoicing Mistakes
- Missed Renewals
- Lack of Timely – Proactive Support
- Lack of Payment Flexibility
- Failed Payments


**3. What methods will you use to segment customers on the platform**

Here are some common ways to segment customers:
The customer segmentation process helps you understand who your target audience is, refine your customer experience and reduce churn.

- Demographic Information: Such as age, gender, marital status.
- Geographic Information: This entails the location of customers.
- Customer Behavior: This is dependent on how the customers have interacted with your brand in the past. Some of the factors include brand loyalty, past purchases, and current user status.


### Technical 

- Service Provider table
- payment table

**SQL Concepts**

My SQL code contains a nested function (i.e, query in a query) and I applied some SQL commands such as;

- SELECT statement to retrieve the columns required
- COUNT() aggregate function to retrieve the number of rows
- MAX() aggregate function to get the last payment date for each customer
- AS alias to temporarily name column
- FROM command to specify the table to select
- GROUP BY clause to show the last payment date for each customer
- HAVING clause used for an aggregate function instead of WHERE clause
- MONTH() function to retrieve customers whose last subscription was made in the moth of may.

**1. Count of customer that have done 2 or more different products.**

<img width="780" alt="image" src="https://github.com/mrdimejisam/Online-Payment-Platform/assets/111657348/36de8b4f-8fec-4b9c-a7cc-f3cf14bc9711">


**2. State what would you consider as a churned customer? Write an sql query to show the
count of customers that fit this criterion.**

Churned customers are customers that have stopped using and paying for your product or service.

Since the payment table shows the monthly payment details from the month of April, 2021 to September of the same year which is a 6 months payment history.
Therefore, I presume that customers who have not made any payment transaction in the last 4 months (i.e last payment was made in May) would be considered to have churned.

<img width="781" alt="image" src="https://github.com/mrdimejisam/Online-Payment-Platform/assets/111657348/4920a695-2a15-42ee-9caf-e4968fe00bac">


**3. Write an sql query to show the top 5 products whose availability is critical to ensure
sustained revenue.**

For a product to be critical to ensure sustained revenue, it has to be a product that generate more revenue.

<img width="779" alt="image" src="https://github.com/mrdimejisam/Online-Payment-Platform/assets/111657348/d10f1047-cf34-4028-b790-ef6e7043133b">


### Visual (Tableau)

1. show the growth rate of transaction volumes per month.
2. Show the growth rate of customer on the platform.

![image](https://github.com/mrdimejisam/Online-Payment-Platform/assets/111657348/e521907d-3369-416d-9d16-2a4e6d3f38a2)



**Data Structure**

<img width="461" alt="image" src="https://github.com/mrdimejisam/Online-Payment-Platform/assets/111657348/5323d6f9-af5e-4056-ad8a-222afda96ecd">
