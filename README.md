# Mobile-_Sales_Dashboard_Project
## Project Objective
> The objective of this project is to analyze mobile phone sales data to gain insights into:
* Overall sales trends (monthly, quarterly, yearly)
* Sales performance by mobile model, brand, and payment method
* Customer purchasing behavior
* Key metrics like total quantity, average price, and total transactions
  
_By visualizing these insights in a dashboard, stakeholders can make data-driven decisions on inventory management, marketing strategies, and customer engagement._

## Dataset Used
[Mobile_Dataset.xlsx](https://github.com/Gmanas7735/Mobile-_Sales_Dashboard_Project/blob/main/Mobile%20Sales%20Data.xlsx)

## Questions (KPIs)
> The dashboard aims to answer the following key performance questions:
* Total Sales
  * How much revenue is generated overall?
  * Which months or quarters see the highest sales?
* Total Quantity
  * How many units were sold in a given period?
  * Which brand or model has the highest quantity sold?
* Transactions
  * How many transactions occur over time?
  * Which payment method is most popular?
* Average Price
  * What is the average price of the products sold over time?
  * How does pricing vary by brand or model?
* Sales by City
  * Which cities have the highest sales?
  * Is there a regional trend or pattern in purchases?
* Payment Methods
  * What are the most commonly used payment methods?
  * Do certain payment methods correlate with higher sales?
* Top Customer Ratings and Status by percentage
  * How satisfied are customers overall?
  * Which models or brands receive the highest ratings?

## Process
* 4.1 Data Collection
  * Gathered sales records from local stores [Mobile_Dataset.xlsx](https://github.com/Gmanas7735/Mobile-_Sales_Dashboard_Project/blob/main/Mobile%20Sales%20Data.xlsx).
* 4.2 Data Cleaning & Preparation
  * Removed duplicates, handled missing values.
  * Converted date fields to proper date/time format.
  * Created necessary measures and calculated columns (e.g., Total Sales, Average Price).
* 4.3 Data Modeling
  * Modeled the data in a star schema, relationships between fact table (sales Data table) and dimension tables (Custom_Calendar).
* 4.4 Dashboard Creation
  * Used a BI tool to create visualizations.
  * Built multiple pages:
    * MTD (Month-to-Date) Report
    * Same Period Last Year Comparison
    * Monthly/Quarterly Trends
    * Breakdown by City, Brand, Payment Method
* 4.5 Testing & Validation
  * Cross-checked sample data to ensure accuracy of measures and visuals.
  * Ensured filters and slicers worked as expected (e.g., by brand, city, date range).

## Dashboard
> Below are screenshots of the final dashboard pages. They provide an at-a-glance view of critical KPIs and trends:
* Dashboard Page
  * Total Sales, Total Quantity, Transactions, Avg. Price
  * Year-over-year comparison charts
  * Quarter-wise or Month-wise trend charts
  * Card (Total Sale, Total Quantity, Transactions, Average Price)
  * Slicer (Mobile model, Payment Method, Brand)
* MTD Report (Using Line chart)
  * Month-to-date total sales trends
  * Comparison with previous months/years
  * Card (Total Sale, Total Quantity, Transactions, Average Price)
  * Slicer (Mobile model, Payment Method, Date)
* Same Period Last Year Page (Using Column Chart)
  * Total Sales & Same Period Last Year by Year
  * Total Sales & Same Period Last Year by Quarter 
  * Total Sales & Same Period Last Year by Months 
  * Card (Total Sale, Total Quantity, Transactions, Average Price)
  * Slicer (Mobile model, Payment Method, Date)
> (For example:)
![Dashboard](https://github.com/Gmanas7735/Mobile-_Sales_Dashboard_Project/blob/main/Dashboard.png)

![MTD Report](https://github.com/Gmanas7735/Mobile-_Sales_Dashboard_Project/blob/main/MTD.png)

![Same Period Last Year Page](https://github.com/Gmanas7735/Mobile-_Sales_Dashboard_Project/blob/main/SPLY.png)

## Project Insights
* Sales Growth
  * Identified steady growth in sales from Q1 to Q4, with peak sales in Q4.
* Top Brands & Models
  * Brand Apple, Samsung, OnePlus consistently outperforms other brands in terms of total sales.
  * Model iPhone SE, OnePlus Nord, Galaxy Note 20 remains the best-selling product in multiple cities.
* City Performance
  * Metropolitan areas show higher average purchase value, while smaller cities contribute a substantial volume of sales.
* Payment Method Preferences
  * UPI payment slightly higher than the Debit and credit Card.
  * Cash transactions are more common in rural or suburban regions.
* Customer Ratings
  * Overall rating trend is positive, with minimal negative feedback.
  * Higher-priced models receive more mixed reviews, suggesting a need for better after-sales support or improved features.
* Seasonality
  * Notable spikes in sales during holiday seasons and product launch periods.

## Final Conclusion
### Business Impact: The insights derived from this dashboard help stakeholders understand where to allocate marketing budgets, manage inventory more efficiently, and tailor promotions for high-demand periods.
* Next Steps:
  * 1.	Expand the dataset to include additional metrics like warranty claims, store-level data, and customer demographics.
  * 2.	Enhance the customer feedback loop to improve after-sales service and product quality.
