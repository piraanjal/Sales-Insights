
# Sales Insights Dashboard 

## Overview
This project focuses on analyzing sales data using Tableau. The primary goal is to derive actionable insights from the data to understand revenue and profit trends across different years, months, and markets.

## Data Integration
The analysis is based on five CSV files:
- *Transactions*
- *Date*
- *Market*
- *Products*
- *Customers*

These files were imported into a PostgreSQL database for seamless integration with Tableau, enabling efficient data querying and visualization.

## Dashboards

### 1. Revenue Analysis Dashboard
The Revenue Analysis Dashboard provides a comprehensive view of revenue trends over the years and months. Key features include:
- *Revenue by Markets*: Displays normalized revenue for different markets.
- *Sales Quantity by Market*: Shows the number of sales transactions in each market.
- *Revenue by Year*: Highlights the annual revenue trends, aiding in identifying high-performing years.
- *Top 5 Customers and Products*: Lists the most profitable customers and best-selling products.

![Revenue Analysis Dashboard](images/ss1.png)

### 2. Profit Analysis Dashboard
The Profit Analysis Dashboard focuses on profit margins and trends. Key features include:
- *Total Revenue and Profit*: Provides an overview of total revenue and profit for the selected time period.
- *Profit Margin by Markets*: Displays profit margins for each market, helping identify the most profitable regions.
- *Profit Trend*: Highlights changes in profit over time.
- *Customer Table*: Lists detailed information about customers, including profit margins and normalized amounts.
- *Revenue Distribution by Market*: Shows the percentage split between E-Commerce and Brick & Mortar sales.

![Profit Analysis Dashboard](Screenshot%202024-12-21%20143715.png)

## Technology Stack
- *PostgreSQL*: Used to store and manage the integrated data from the CSV files.
- *Tableau*: For creating interactive dashboards and visualizations.


## Screenshots
### Revenue Analysis Dashboard
![Revenue Analysis Screenshot](Screenshot%202024-12-21%20143751.png)

### Profit Analysis Dashboard
![Profit Analysis Screenshot](Screenshot%202024-12-21%20143715.png)

