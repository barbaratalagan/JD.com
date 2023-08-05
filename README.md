# JD.com Capstone Project 
Completing this project was a requirement to graduate from Cornell's Masters in Business Analytics program. 

This project aims to optimize JD.com's inventory to improve their fufillment and delivery times. 

# Inventory Optimization Model Calculates the following:
- Safety Stock
- Expected Lost Sales
- Expected Sales
- Expected Excess Inventory
- Mean Lead Time Demand
- Order-Up-To-Level
- Cost of Excess Inventory
- Cost of Lost Sales
- Total Costs

# Languages
- R-Studio: Model building and exploratory analysis
- Python: Exploratory Analysis 

# R Packages Used for Modeling
- library(readxl)
- library(openxlsx)
- library(tidyverse)
- library(tidyr)
- library(dplyr)
- library(lubridate)

# Data
One month time series data on customers, orders, deliveries, networks, inventory. 
*Many data limitations including:*
**Time Series**
- Limited to one month of time series data (March 2018)
**Inventory Management:**
- Inventory holding costs and the quantities of available inventory
- Inventory order lead time and transportation costs 
**Warehouse capacities:**
- Information on most 3P (Third Party) products  
- Order Fulfillment and logistics:
- Order shipping costs
- Identity or type of products purchased by customers  
- Location of regional warehouses and local warehouses
- Distances between warehouses and/or customers
- Customer addresses

# Assumptions Made to Deal with Data Constraints
- **Inventory Reorder Lead Time:** set to 7 days
- **Service Rate:** Set at 95% to reflect JD's commitment to sufficient stock
- **Standard Deviation of Lead Time:** 0 days as an industry leader with steady reorder lead times
- **Profit Margin:** Set at 13% on goods sold (source).
- **Inventory Holding Costs:** Set at 30% of product cost
- **Goodwill (Penalty) Costs:** Inventory shortage cost is assumed to be 50% of product cost
