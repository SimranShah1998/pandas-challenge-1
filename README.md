# Pandas Challenge 1: Wholesale Data Analysis 

## Project Overview 

This project involves analyzing a dataset from a wholesale client to extract insights and transform the data for easier analysis. The project is divided into four main parts:

## Exploring the Data: 

Initial exploration to understand the structure and contents of the dataset.

## Transforming the Data:

Creating new columns to facilitate analysis, including calculations for subtotals, shipping prices, total prices, line costs, and profits.

## Confirming Calculations:

Verifying the accuracy of calculations against provided data.

## Summarizing and Analyzing: 

Extracting and presenting key insights from the transformed data.


# Part 1: Explore the Data
## Steps:

Column Names and Basic Statistics: Used Pandas to view column names and descriptive statistics of the dataset.

## Top Categories:

Identified the three item categories with the most entries: Consumables, Furniture, and Software.
Within the top category Consumables, identified Bathroom Supplies as the subcategory with the most entries.

## Top Clients:
Identified the top 5 clients by the number of entries and calculated the total units ordered by the top client.


# Part 2: Transform the Data

## Transformations:
Subtotal: Calculated as unit_price * qty.

## Shipping Price:
$7 per pound for orders over 50 pounds.
$10 per pound for orders 50 pounds or under.

## Total Price: 
Calculated as subtotal + shipping price, with an additional 9.25% sales tax.

## Line Cost: 
Calculated as unit_cost * qty + shipping price.

## Profit: 

Calculated as total price - line_cost.


# Part 3: Confirm Your Work

## Verification:

Order Totals: Calculated the total prices for three specified orders. 


# Part 4: Summarize and Analyze

## Summary and Insights:
This part includes calculating the total revenue for the top 5 clients, summarizing key metrics like total units purchased, total shipping price, total revenue, and total profit.
A function to format the data in millions of dollars and sort by total profits.
