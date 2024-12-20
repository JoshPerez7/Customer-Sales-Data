# Customer-Sales-Data

## Project Overview

This repository contains SQL queries designed to analyze and manage data from a fictional sales database. The database consists of three main tables: Sales, Customers, and Products. Each table stores essential data about sales transactions, customers, and products, respectively.

## Tables Schema

### Sales
Column	Data Type	Description
sales_id	INT	Unique identifier for sales
customer_id	INT	Unique identifier for customers
product_id	INT	Unique identifier for products
sale_date	DATE	Date of the sale
quantity	INT	Number of products sold
total_amount	DECIMAL	Total amount of the sale

### Customers
Column	Data Type	Description
customer_id	INT	Unique identifier for customers
customer_name	VARCHAR	Name of the customer
sales_region	VARCHAR	Region where the sale was made
sign_up_date	DATE	Date the customer signed up

### Products

Column	Data Type	Description
product_id	INT	Unique identifier for products
product_name	VARCHAR	Name of the product
category	VARCHAR	Category of the product
price	DECIMAL	Price of the product

## Instructions

Write SQL queries for each of the following questions. Assuming that all tables follow typical database conventions.
