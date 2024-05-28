# Analysis of Sales, Orders, and Stock Data with PowerBI

## Project Context
This project focuses on developing a comprehensive dashboard using PowerBI for the supply chain team. The dashboard addresses two main objectives:

1. **Delivery Tracking**: Quickly view the delivery status of items to determine if shipments are on time or delayed.
2. **Sales vs. Order Minimums**: Compare sales against the minimum order quantities per item to identify products at risk of overstock due to insufficient sales.

## Steps Followed
- **Data Collection**: Gathered data from 11 CSV files, including dimensional files (product data) and fact files (sales, orders, stock).
- **Data Modeling**: Created a star schema model to link the datasets.
- **Dashboard Development**: Built the dashboard in PowerBI to visualize key metrics and insights.

![Star Model](https://github.com/ErwanMrcx/powerbi_sales_project/blob/main/pictures/star_model.jpg)

## Key Questions Addressed
- **Delivery Status**: Where and when will products be delivered? Are there any shipments that are delayed?
- **Sales Performance**: What are the sales figures for each department and store? Are the sales aligned with order and stock capacities?

## Dashboard
The dashboard includes visualizations for tracking orders and sales performance:

- **Orders Follow-up**:
  ![Orders Follow-up](https://github.com/ErwanMrcx/powerbi_sales_project/blob/main/pictures/orders%20follow%20up.jpg)
- **Sales Performance**:
  ![Sales Performance](https://github.com/ErwanMrcx/powerbi_sales_project/blob/main/pictures/sales_performance.jpg)

  
## Technical Details
- **Data Sources**: CSV files containing product, sales, orders, and stock data.
- **Data Modeling Tool**: PowerBI for creating the star schema model.
- **Visualization Tools**: PowerBI for building interactive dashboards.
- **Programming Languages**: DAX (Data Analysis Expressions) for calculations in PowerBI.


## Future Work
- **Enhanced Predictive Analytics**: Incorporate machine learning models to predict future sales and stock levels.
- **User Feedback Integration**: Implement features based on feedback from the supply chain team to continuously improve the dashboard.
- **Real-time Data Updates**: Integrate real-time data feeds to provide up-to-the-minute insights.


## Conclusion
- **Product Optimization**: Some products need to be re-evaluated due to low sales, which poses a risk of overstock.
- **Delivery Management**: Several shipments are delayed, indicating a need for better monitoring and management to ensure timely deliveries.
