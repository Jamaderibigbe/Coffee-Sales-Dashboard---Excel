## Coffee-Sales-Dashboard---Excel

### About
This project aims to explore the Coffee Order Dataset by analyzing the performance of various branches, coffee sizes, and roast types. It involves tracking sales trends over time across different coffee types to understand how customer loyalty impacts sales

In this project Today, we are going to creation Coffee Sales Dashboard. This dashboard will provide a comprehensive overview of  coffee sales data, allowing us to gain valuable insights.

### the details of what this dashboard will include

1. A dynamic line chart showcasing the total sales over time, segmented by the different coffee types we offer:
  - Arabica
  - Excelsa,
  - Libreca, and
  - Robusta.

2. we will create visually engaging bar chart illustrating sales by country. Our sales are currently distributed across three key markets:
  - the United States,
  - Ireland, and
  - the United Kingdom.

3. we will highlight our top five customers with another informative bar chart, providing insights into our most valuable client relationships.

    To enhance usability, we will incorporated a user-friendly timeline feature. This enables seamless manipulation of the visuals, allowing users to effortlessly navigate through           different time periods and explore our sales data in greater detail.

4. We also have a rose-type named slicer, allowing us to choose between dark, light, or medium roasts, and the visuals will adjust accordingly
   Additionally, we have two other slicers. One is for size, as these coffees come in different packages: 0.2 kilo, 0.5 kilo, 1 kilo, and 2.5 kilo packages.
   Lastly, we have another slicer that indicates whether or not the customers have a loyalty card.

#### Purposes Of The Project
build a dynamic and interactive Coffee sales Dashboard.

#### About Data
The dataset consists of sales transactions spanning 21 columns and over 1,000 rows of valuable data for analysis [Coffee order Data](https://github.com/Jamaderibigbe/Coffee-Sales-Dashboard---Excel/blob/main/coffeeOrdersData%20Start.xlsx)

#### Approach Used
> Let's take a moment to review the data we'll be working with. Once again, this dataset focuses on coffee sales. We have three different tables
  - Order Table
  - Customer Table and
  - Product table
> in the Order table We have columns for Order ID, Order Date, Customer ID, Product ID, and Quantity, all of which are already populated.
However, we have other couple of columns from F to M where the data is not yet populated. In such cases, we need to perform lookups to gather the necessary data from different tables.
The Customers table contains all customer information, with the unique key or primary key being the Customer ID.
The Product table contains all product information, with the unique key or primary key being the Product ID.

##### We'll use the XLOOKUP formula to retrieve customer data. Then, for gathering product data, we'll utilize the traditional INDEX MATCH method, and The IF Function."
To review the Excel formula in use, please click on the following [link](https://docs.google.com/spreadsheets/d/1nMGg64LbEb1V1UT3iaGAoPvzMLKLuFfEEYKd6NUFwbI/edit?usp=sharing).

> After confirming that our data has no duplicate or null values, we move on to creating a pivot table and chart, which forms the foundation of our dashboard.
  Before proceeding to Pivot tables and pivot charts for analysis and visualization, I converted the order sheet data range into an actual table.

> We generated a pivot table that includes years and months, allowing us to visualize the trend of total sales over time.
  As a result, we created the following chart

![Sales over Time](https://github.com/Jamaderibigbe/Coffee-Sales-Dashboard---Excel/blob/main/Total%20Sales%20over%20Time.PNG)

> We generated a pivot table that includes Sales and Country, allowing us to visualize the total sales made in each Country.
  As a result, we created the following chart

![Sales by Country](https://github.com/Jamaderibigbe/Coffee-Sales-Dashboard---Excel/blob/main/Sales%20by%20Country.PNG)


> We generated a pivot table that includes Our Top Customer against sales, allowing us to visualize our Top 5 customer
  As a result, we created the following chart

![Top 5 Customers](https://github.com/Jamaderibigbe/Coffee-Sales-Dashboard---Excel/blob/main/Top%205%20Customers.PNG)

> Following that, we created slicers for Size, type of roast, and loyalty card, and inserted our timeline, all of which contributed to the creation of the below dashboard
![Dashboard](https://github.com/Jamaderibigbe/Coffee-Sales-Dashboard---Excel/blob/main/Coffee%20Dashboard.PNG)

> With the above dashboard, we are able to address the following questions:

- How do total sales evolve over time across different coffee types?

- What is the distribution of sales by country?

- Who are our top 5 customers based on sales?

- How the timeline feature is used to manipulate our visuals and gain deeper insights?

> To actively engage with the dashboard created, please click the following link to download the Excel file [coffeeOrderData Finished](https://github.com/Jamaderibigbe/Coffee-Sales-Dashboard---Excel/blob/main/coffeeOrdersData%20Finished.xlsx)
