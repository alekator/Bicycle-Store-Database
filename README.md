# Project - Bicycle Store Database

## Description
This project represents the development of a database for storing and managing information about bicycles. The database includes tables for storing data about bicycles, suppliers, manufacturers, and other reference data. It supports data entry, editing, and viewing, and provides role-based access control for users: operator, user, and administrator.

## Key Features
**The project implements the following functionalities:**
- Data entry, editing, and viewing for bicycles.
- Use of reference tables and related tables.
- Support for user roles: operator, user, and administrator.
- Execution of various queries for data analysis about bicycles.

## Queries
**The project implements the following database queries:**
- **Bicycle Information**  
  Retrieves information about bicycles (name, release year, place of manufacture, price, supplier, manufacturer, etc.) for each type of bicycle (mountain, road, children's, tandem, etc.).

- **Bicycle Sorting**  
  Displays a list of bicycles sorted by release year, supplier, or price.

- **Price Analysis**  
  Finds the most expensive and cheapest bicycle and calculates the average bicycle price.

- **High-Cost Bicycles**  
  Finds all bicycles priced above a specified amount (e.g., 10,000 RUB), with an option to enter the price manually.

- **Bicycle Analysis by Period**  
  Finds bicycles released in a specific period (month, 3 months, 6 months), with calculations for average price, the most expensive, and the cheapest bicycle.

- **Bicycle Share by City**  
  Finds the share of bicycles that arrived from a specified city, relative to the total number of bicycles.

- **Bicycles by Release Date**  
  Finds all bicycles released on a specified date.

- **Bicycles by Supplier and Price**  
  Finds all bicycles from a specified supplier, whose price falls within a specified range.

- **Bicycle Share by Supplier**  
  Finds the share of bicycles delivered by a specified supplier relative to the total number of suppliers.

- **Bicycles by Year and Price**  
  Finds all bicycles released in a specified year, whose price exceeds the specified value.

- **Bicycles by Manufacturer**  
  Finds all bicycles from a specific manufacturer.

- **Bicycle Sales Share by Period**  
  Finds the share of bicycles sold during a specified period relative to the total sales time.

- **Price Comparison by Country**  
  Finds all bicycles from a specified supplier whose price exceeds the average bicycle price delivered from a specified country.

- **Share of Low-Cost Bicycles**  
  Finds the share of low-cost bicycles (priced below a specified value) sold to a specified client and overall.

- **Average Price of Sold Bicycles**  
  Calculates the average price of bicycles sold during a specified time period.

- **Bicycles Priced Above Manufacturer’s Average**  
  Finds all bicycles whose price is higher than the average price of bicycles from a specified manufacturer.

## Technologies
- PostgreSQL for database creation.
- C# for database interaction.
- Entity Framework for data management.
- User roles: operator, user, administrator.

## Installation and Launch
- Install PostgreSQL.
- Set up the database using the provided SQL script.
- Run the project in Visual Studio.
- Configure the connection strings in the configuration file.
- Log in using one of the roles (operator, user, administrator).
- Manage the database using the provided queries.
