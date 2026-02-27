# Analysing Coffee Sales

---

## Overview
In this project, coffee sales over the period March 2024 - March 2025 were analysed. Data source: .xlsx file at https://www.kaggle.com/datasets/reignrichard/coffee-store-sales

## Steps performed
- Staging, normalizing and further transformations of the data in `Power Query`; a portion of the M language script used is given in FactSales-querysteps.txt
- A star schema was applied and `Power BI` was used to vizualize the data and create the report below:

<img width="837" height="487" alt="image" src="https://github.com/user-attachments/assets/7b84ac5b-54cb-4442-bcde-3856123c6ff3" />


## Key insights
- The **Americano** is the most popular, and most of its sales are in the **Morning** and **Afternoon**
- **October 2024** has significantly more sales than any other month
- Only **23%** of new customers in any month are likely to make another purchase in subsequent months and most customers (**87%**) have purched 3 or less drinks
- **11.5%** of the total revenue is from the top 5 spending customers, which includes a customer with 108 total transactions who generated about 33% of all Cortado revenue, has been a regular since April 2024 and usually makes purchases in the Morning but never the Evening:

<img width="829" height="486" alt="image" src="https://github.com/user-attachments/assets/c1104d76-dc70-415c-89ef-66818e4b5503" />

