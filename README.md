# 🍽️ Food Delivery Data Integration & Analysis

## Overview
This hackathon project integrates food delivery data from multiple sources into a single analytics-ready dataset, simulating a real-world data analytics workflow.

## Data Sources
- `orders.csv` – Transactional order data  
- `users.json` – User master data  
- `restaurants.sql` – Restaurant master data  

## Tools
Python, Pandas, SQLite, Jupyter Notebook

## Data Integration
- `orders.user_id` → `users.user_id`
- `orders.restaurant_id` → `restaurants.restaurant_id`
- Join type: LEFT JOIN

## Output
- `final_food_delivery_dataset.csv`

## How to Run
Open `Food_Delivery_Data_Integration.ipynb` and run all cells.

## Author
**Teja Kesarapu**
