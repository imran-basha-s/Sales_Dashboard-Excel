# Sales_Dashboard-Excel

![](https://github.com/imran-basha-s/Sales_Dashboard-Excel/blob/main/sales_dashboard.png)

## Coffee Sales Dashboard

This project delves into a rich pool of information concerning coffee beans and 
introduces you to the dynamic coffee industry. It encompasses extensive details 
on coffee sales orders, customer profiles, and a diverse range of coffee products.

The primary objective of this initiative is to construct a comprehensive sales 
dashboard that not only filters but also visually presents the data as required. This 
dashboard plays a crucial role in monitoring performance metrics, facilitating 
informed decision-making, and establishing benchmarks for setting future sales 
targets.

## Dataset

The raw dataset is available in the form of an excelsfile. It has three sheets named, 
“orders, customers, and products.”

The dataset spans from 2nd Jan 2019 to 19th Aug 2022, has 1000 entries and covers
data from 3 countries.

The dataset can be downloaded from [Here](https://www.kaggle.com/datasets/saadharoon27/coffee-bean-sales-raw-dataset/data)

**Orders Worksheet:**

Order ID: A unique identifier for each coffee order.<br>
Order Date: The date when the order was placed.<br>
Customer ID: An identifier linking the order to a specific customer.<br>
Product ID: A unique identifier for each coffee product.<br>
Quantity: The quantity of the coffee product ordered.<br>

**Customers Worksheet:**

Customer ID: A unique identifier for each customer.<br>
Customer Name: The name of the customer.<br>
Email Address: Contact information for customers.<br>
Phone Number: Another contact detail for customers.<br>
And more.<br>

**Products Worksheet:**

Product ID: A unique identifier for each coffee product.<br>
Coffee Type: The type or blend of coffee, such as Arabica or Robusta.<br>
Roast Type: The roast level, including light, medium, or dark roast.<br>
Size: Information about the product size.<br>
Unit Price: The price of a single unit of the coffee product.<br>
Price Per 100g: The price per 100 grams for detailed price comparisons.<br>
Profit: Insights into the profitability of each coffee product.<br>

## Approach

The points below briefly outline the approach adopted to build the dashboard.

1. The required data from different worksheets was merged into the sheet 
named “orders” using XLOOKUP.<br>
2. The sheet named “orders” represents the working sheet for the project.<br>
3. Basic data cleaning & preprocessing like checking for duplicates, 
formatting the date, size, unit price, and sales column was done to tidy up 
the data and make it ready for the next step.<br>
4. Three Pivot Tables, were created - total sales, country bar chart, and top 10 
products.<br>
5. Correspondingly the pivot charts named – total sales timeline, sales by 
country, and top 10 products were generated.<br>
6. All the necessary charts along with timeline and slicers were combined to 
develop a dashboard within the same excel file.<br>

