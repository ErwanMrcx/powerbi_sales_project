# Analysis of the sales, orders and stock data with powerBI

## Context of the project
In this project, we are trying to build a useful dashboard that can be used by supplychain team. 

Here we aim to help on 2 topics:
- Be able to have quick look on where our items will be delivered and when they will be delivered. The main goal is to know if the shipment will be late or not.
- Be able to compare the sales and the minimum of ordering by items. To be more specific, each supplier have a minimum of quantity to order by item and we are looking for items where the sales are not enough big to order regularly. 
(One item that can not be order regulary will be overstock)

## Steps followed
- Get all the data on several csv files. There are 11 files (dimensional files with data products and facts files with sales, orders and stock)
- Create a star based model in order to link each database
- Developping the dashboard

## Questions
- Where and when my products will be delivered. Is there any shipments that are stuck?
- Whats are my sales for each departments, each stores? Is my sales are in adequation with my order and stock capacity?

## Dashboard
![alt text](https://github.com/ErwanMrcx/powerbi_sales_project/blob/main/pictures/orders%20follow%20up.jpg)
![alt text](https://github.com/ErwanMrcx/powerbi_sales_project/blob/main/pictures/sales_performance.jpg)

## Conclusion
- Some products needs to be rework, because sales are not high enough. There is a risk of overstock.
- Some shipments are late. The company needs to pay attention to it.

