# 🎬 Movies Data Analysis (Sakila SQL EDA Project)

> **Exploring Movie Rentals, Revenue & Customer Behavior using MySQL**

---

## 📘 Overview

This project performs an **Exploratory Data Analysis (EDA)** on the **Sakila Movie Rental Database** using **MySQL**.  
It aims to uncover insights about **store revenue**, **movie category performance**, **customer spending patterns**, and **inventory management**.  

The **Sakila Database** is a sample dataset provided by MySQL, designed to replicate a real-world **movie rental business** with tables like `film`, `rental`, `customer`, and `payment`.

---

## 🎯 Objectives

- Identify **top-performing stores** and **revenue trends**  
- Find **best-selling movie categories & ratings**  
- Analyze **customer loyalty** and **spending behavior**  
- Track **rental durations**, **late returns**, and **staff efficiency**  
- Evaluate **inventory status** across stores  

---

## 🧩 Dataset Overview

| Table | Description |
|--------|-------------|
| `film` | Details of movies including category & rating |
| `category` | List of movie genres |
| `rental` | Rental transaction details |
| `payment` | Payment and amount per transaction |
| `customer` | Customer demographics and activity |
| `store` | Store location & management info |
| `staff` | Employee details |
| `inventory` | Movie copies available per store |

📚 **Source:** MySQL Sakila Sample Database

---

## ⚙️ Tools & Tech Stack

- 🐬 **MySQL / MySQL Workbench** → Query execution & visualization  
- 🧮 **SQL** → Joins, subqueries, window functions, and aggregates  
- 📊 **Excel / CSV (optional)** → Exporting and analyzing query results  

---

## 🧠 Analysis Workflow

| Step | SQL Script | Purpose |
|------|-------------|----------|
| 1️⃣ | `01_store_revenue.sql` | Store-wise revenue and peak months |
| 2️⃣ | `02_movie_category.sql` | Revenue by genre & movie rating |
| 3️⃣ | `03_top_customers.sql` | Identify top 10 paying customers |
| 4️⃣ | `04_rental_analysis.sql` | Rental duration & late returns |
| 5️⃣ | `05_staff_performance.sql` | Analyze staff efficiency & payments |
| 6️⃣ | `06_geo_revenue.sql` | Revenue by city/country |
| 7️⃣ | `07_inventory_status.sql` | Stock availability & out-of-stock movies |

---

## 📈 Key Insights

| Area | Observation |
|------|--------------|
| 💰 **Revenue** | Store 1 leads in total revenue, with peaks in **July–August 2005** |
| 🎬 **Top Categories** | **Sports**, **Sci-Fi**, and **Drama** are the highest-earning genres |
| 👥 **Customers** | Top 10 customers account for **~18% of total revenue** |
| 🕒 **Late Returns** | Around **8,000+ rentals** were returned late |
| 🧑‍💼 **Staff** | **Mike** handled more payments than **Jon**, showing strong performance |
| 🌍 **Geography** | Highest revenue from **US stores**, emerging growth in **Europe & Asia** |
| 📦 **Inventory** | **2,178 items in stock**, only **92 out-of-stock** |

---

## 💡 Recommendations

- Focus marketing on **top-performing stores** & **peak months**  
- Promote **profitable movie categories** & **popular ratings**  
- Launch **customer loyalty programs** for top spenders  
- Send **rental reminders** to reduce late returns  
- Maintain **inventory balance** for high-demand titles  
- Reward **high-performing staff** to boost motivation  



