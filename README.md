# Maven-Market-Report

![](Maven_Market.png)

## Introduction 
This is a Power BI project on the sales analysis of a store called 'Maven Market' (the dataset is sourced from Kaggle). 
The project is to analyze and derive insights to answer crucial questions and help the store make data-driven decisions.

## Problem statement

Problem statement:
1. Which store generates the most profit?
2. What is the monthly revenue, profit, orders and returns compared to the previous month?
3. What is the total revenue, total profit and profit margin?
4. Who is the best customer based on revenue?
5. From which region are the stores generating the most revenue?
6. What is the best product based on profit?

## Skills demonstrated:

The following Power BI features were incorporated:

- Bookmarking
- DAX
- Quick Measures
- Page Navigation
- Modelling 
- Filters
- Tooltips
- Buttons
- Parameters

## Modelling:
![](MMR_diagram.png)

This schema organizes retail data, with Products, Customers, Stores and Calendar as primary entities.
Transactions Data and Return Data tables connect to these entities through foreign keys, establishing relationships for tracking product transactions and returns.

Products, Customers, Stores and Calendar tables have a one-to-many relationship with both Transactions Data and Return Data tables.

## Visualization:

The report comprises 4 pages:
1. Main
2. Customer
3. Product
4. Stores

You can interact with the report [here](https://app.powerbi.com/groups/me/reports/c63c115c-8edf-4899-ac4b-9a4dd27cf513/ReportSection?experience=power-bi).
---
## Main Page
![](mainpagenew.png)

Features:
- In the top left is a button to clear all the filters applied to this page.
- Under that button, there are buttons to navigate through pages.
- There is a slicer under the line chart that you can customize to see the profits trending for a period you would like.
- On the bar chart, there is a feature that, when you hover over a certain bar, you will see a custom tooltip.
- In the top 15 product list, you can right-click on a product name, go to the drill-through and click on Product. This will navigate you to the product page, where you can gather key insights about that product.

## Customers Information Page
![](customer.png)

Features:
- In the top left is a button to clear all the filters applied to this page.
- Under that button, there are buttons to navigate through pages.
- There's a time filter above the Top Customer section. Use it to pick the timeframe and see who the top customer was during that period.

## Product Infromation Page
![](product.png)

Features:
- On the left side of the page there are the navigation buttons that are in every page of the report.
- Right-clicking and clicking on drill through Product on a product from the top 15 list takes users to this page for detailed product information. It's a quick way to see key metrics of the product you chose.
- The Price Adjustment feature enables users to slide prices in 10% increments, from -100% to +100%. It offers a swift and flexible method for adjusting product prices, providing insights into expected profits with each change.
- There is a Product Metrics Selection list that lets you click and choose from Total Orders, Total Profit, Total Revenue, and Total Returns for the selected product. It's a quick way to view key performance metrics.

##Stores Information Page


