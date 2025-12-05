# Data Dictionary

## Overview
This document provides a detailed description of the datasets used in the Sales Performance Dashboard. The data is normalized into two main tables: **Orders** and **Details**.

## 1. Orders Table (`Orders.csv`)
Contains high-level information about each sales transaction, focusing on the customer and location.

| Column Name  | Data Type | Description |
| :--- | :--- | :--- |
| `Order ID` | String | Unique identifier for each sales order. Primary key linking to the Details table. |
| `Order Date` | Date | The date when the order was placed. Used for time-series analysis (MoM, YoY). |
| `CustomerName` | String | Name of the customer who placed the order. |
| `State` | String | The state where the order was delivered. |
| `City` | String | The city where the order was delivered. |

## 2. Details Table (`Details.csv`)
Contains granular line-item details for each order, including financial metrics and product classification.

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `Order ID` | String | Foreign key linking to the Orders table. |
| `Amount` | Integer | The total revenue generated from the specific line item. |
| `Profit` | Integer | The profit margin earned on the specific line item. |
| `Quantity` | Integer | The number of units sold. |
| `Category` | String | High-level product classification (e.g., Electronics, Furniture). |
| `Sub-Category` | String | Specific product type (e.g., Chairs, Printers, Phones). |
| `PaymentMode` | String | The method of payment used (e.g., COD, EMI, Credit Card). |
