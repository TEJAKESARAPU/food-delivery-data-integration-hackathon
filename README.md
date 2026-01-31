# 🍽️ Food Delivery Data Integration & Analysis – Hackathon Project

## 📌 Project Overview
This project is part of a data analytics hackathon focused on integrating data from multiple real-world sources into a single, analytics-ready dataset. The objective is to simulate how data analysts work with transactional and master data stored in different formats.

The project combines **CSV**, **JSON**, and **SQL** files using **Python and Pandas**, performs proper joins, and generates a final dataset for analysis.

---

## 📂 Datasets Used

### 1️⃣ orders.csv (Transactional Data)
Contains order-level information such as:
- order_id  
- user_id  
- restaurant_id  
- order_date  
- total_amount  

### 2️⃣ users.json (User Master Data)
Contains customer details:
- user_id  
- name  
- city  
- membership (Gold / Regular)  

### 3️⃣ restaurants.sql (Restaurant Master Data)
Contains restaurant information:
- restaurant_id  
- restaurant_name  
- cuisine  
- rating  

---

## 🔧 Tools & Technologies
- Python  
- Pandas  
- SQLite  
- Jupyter Notebook  

---

## 🔗 Data Integration Logic

- `orders.user_id` → `users.user_id`
- `orders.restaurant_id` → `restaurants.restaurant_id`
- Join type used: **LEFT JOIN**
  - Ensures all order records are retained even if user or restaurant data is missing.

---

## 📁 Final Output
- **final_food_delivery_dataset.csv**
- Fully integrated dataset containing:
  - Order details
  - User information
  - Restaurant information

---

## 📊 Sample Analysis Performed
- City-wise revenue analysis
- Membership-based order distribution
- Cuisine and rating-based insights

---

## ▶️ How to Run the Project
1. Clone the repository
2. Open `Food_Delivery_Data_Integration_Hackathon.ipynb`
3. Ensure all dataset files are in the same directory
4. Run the notebook cells sequentially

---

## ✅ Key Learnings
- Handling multi-format data sources
- Data modeling using fact and dimension tables
- Performing joins using Pandas
- Preparing analytics-ready datasets for EDA

---

## 👤 Author
**Teja Kesarapu**

---

## 📜 Note
This project is created for educational and hackathon submission purposes.
