# Project : Restaurant Sales Analysis


## Introduction
In this project, we explore a comprehensive dataset that integrates restaurant menu information with detailed order data.This dataset offers a rich source of insights into the operations and customer preferences within a diverse range of cuisine categories. The primary objective is to analyze and interpret this data to uncover trends, preferences, and operational patterns that can aid in optimizing restaurant performance and enhancing customer satisfaction.

Key objectives of this analysis include:

* `Data Analysis` : To analyze menu data and order patterns to identify trends and preferences within each culinary category.
* `Performance Insights` : To assess the performance of different menu items and categories based on order frequency and sales data.
* `Customer Behavior` : To understand customer ordering behavior and preferences, and how they correlate with different menu categories.
* `Optimization` : To provide recommendations for menu adjustments, promotional strategies, and inventory management based on the insights derived from the data.

## Datasets
Table : Menu_Items
* menu_item_id	(Unique ID of a menu item)
* item_name	(Name of a menu item)
* category	(Category or type of cuisine of the menu item)
* price	(Price of the menu item (US Dollars $))

Table : Order_Details
* order_details_id	(Unique ID of an item in an order)
* order_id	(ID of an order)
* order_date	(Date an order was put in (MM/DD/YY))
* order_time	(Time an order was put in (HH:MM:SS AM/PM))
* item_id	(Item ID)



## Entity- Relationship Diagram
![Restaurant Sales Analysis](https://github.com/user-attachments/assets/399cdb87-eb8c-400c-aced-21d867afbaa1)


## Technologies
Python

## Application
Anaconda - Jupyter

## Library Used
- Pandas for Analysis
- Numpy - Mathematical functions
- Matplotlib -  Visualisation


## Code
- Dataset >> Dataset/menu_items.csv ,order_details.csv
- ipynb File >> code/Restaurant Sales Analysis.ipynb
- Output & Conclusion >> Output/Restaurant Sales Analysis.pdf


## Reference
Dataset Reference : https://mavenanalytics.io/data-playground?page=5&pageSize=5
