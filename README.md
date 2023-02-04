# Bikes-Store-Data-Exploration

INTRODUCTION

This repository contains a database for a bike store, with three tables: brands, categories, and products. 
The products table holds information about the various bikes, including their product ID, product name, brand ID, category ID, model year, and price. The categories table contains information about the categories of bikes, including their category ID and category name. The brands table contains information about the brands of bikes, including their brand ID and brand name.

DATASET

The dataset was created for the purpose of exploratory data analysis and database management for the bike store. 
It contains information about the different bikes and their associated brands and categories. The tables in the database are related through their ID columns, with the products table referencing the categories and brands tables.

STRUCTURE OF THE TABLES

Products Table

product_id: Unique identifier for each bike

product_name: The name of the bike

brand_id: The ID of the brand associated with the bike

category_id: The ID of the category associated with the bike

model_year: The year the bike was manufactured

list_price: The price of the bike


Categories Table

category_id: Unique identifier for each category

category_name: The name of the category


Brands Table

brand_id: Unique identifier for each brand
brand_name: The name of the brand


SQL FILE

The SQL file in this repository contains various SQL queries used to explore and manipulate the data in the database. The queries include:

> Selecting specific columns from one or more tables

> Filtering the data based on specific conditions

> Grouping the data and aggregating it based on certain columns

> Joining the tables to combine data from multiple tables

RESULTS

The results of the exploration show insights into the bikes, brands, and categories in the store. The data can be used to answer questions such as:

> Which brands have the most bikes in a specific category?

> What is the average price for bikes in a specific category?

> Which bikes are the most expensive in a specific category?

FUTURE WORK

In the future, additional data could be added to the tables and further exploration could be done to gain more insights into the data. Additionally, the database could be used to support a larger application or analysis project for the bike store.


INSTRUCTIONS

Make sure you have a SQL database management system installed on your computer.

Create an empty database and import the SQL file into it.

Connect to the database using your SQL client and run the queries.




