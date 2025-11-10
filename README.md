# 🎬 Sakila Data Analysis (SQL EDA)

### Exploring Movie Rentals, Revenue & Customer Insights with MySQL

---

## 📘 Project Overview
This project presents an **Exploratory Data Analysis (EDA)** on the **Sakila Movie Rental Database** using **MySQL**.  
It uncovers insights into **store revenue**, **movie performance**, **customer behavior**, and **inventory trends**, simulating a real-world movie rental business.

The **Sakila Database** is a publicly available sample dataset provided by MySQL, containing tables for films, rentals, payments, and customers.

---

## 🎯 Objectives
- Understand **customer loyalty** and **spending behavior**
- Study **rental durations**, **late returns**, and **staff performance**
- Analyze **store-wise revenue** and **seasonal patterns**  
- Identify **top-performing movie categories** and **ratings**   
- Review **inventory health** and stock distribution  

---

## 🧩 Dataset Overview

| Table | Description |
|--------|--------------|
| **film** | Movie details including title, category, and rating |
| **category** | Genre-level classification of movies |
| **rental** | Rental transactions and dates |
| **payment** | Payment details and revenue info |
| **customer** | Customer demographics and activity |
| **store** | Store locations and management data |
| **staff** | Employee information |
| **inventory** | Movie copies available per store |

📚 **Source:** [MySQL Sakila Sample Database](https://github.com/jOOQ/sakila)

---

## ⚙️ Tools & Technologies
- 🐬 **MySQL / MySQL Workbench** → Query execution & visualization  
- 🧮 **SQL** → Joins, subqueries, window functions, aggregations  
- 📊 **Excel / CSV** → Exporting and analyzing query outputs  

---

## 🧠 Analysis Workflow

| Step | SQL Script | Purpose |
|------|-------------|----------|
| 1️⃣ | `01_store_revenue.sql` | Analyze store-wise revenue & peak months |
| 2️⃣ | `02_movie_category.sql` | Evaluate top genres & movie ratings |
| 3️⃣ | `03_top_customers.sql` | Identify high-value customers |
| 4️⃣ | `04_rental_analysis.sql` | Study rental durations & late returns |
| 5️⃣ | `05_staff_performance.sql` | Assess staff efficiency |
| 6️⃣ | `06_geo_revenue.sql` | Analyze revenue by region |
| 7️⃣ | `07_inventory_status.sql` | Track stock availability |

---

## 📈 Key Insights

| Area | Insight |
|-------|----------|
| 💰 **Revenue** | Store 1 leads in revenue, peaking in mid-2005 |
| 🎬 **Top Genres** | Sports, Sci-Fi, and Drama generate the highest earnings |
| 👥 **Customers** | Top 10 customers contribute nearly 18% of total revenue |
| 🕒 **Returns** | Over 8,000 rentals were returned late |
| 🧑‍💼 **Staff** | Mike outperformed Jon in total transactions handled |
| 🌍 **Regions** | US stores lead in revenue, followed by Europe & Asia |
| 📦 **Inventory** | 2,178 items in stock, 92 out of stock |

---

## 💡 Recommendations
- Reward **top-performing staff** to boost engagement  
- Launch **customer loyalty programs** to retain repeat renters  
- Focus promotions on **high-revenue stores** and **peak months**  
- Highlight **top-performing genres** and **popular movie ratings**  
- Send **rental reminders** to reduce late returns  
- Maintain **adequate stock** for trending movies  

---

## 🗂️ Repository Structure

```
Sakila-data-analysis-SQL-EDA/
│
├── sql_scripts/ # SQL queries used for analysis
│ ├── 01_store_revenue.sql
│ ├── 02_movie_category.sql
│ ├── 03_top_customers.sql
│ ├── 04_rental_analysis.sql
│ ├── 05_staff_performance.sql
│ ├── 06_geo_revenue.sql
│ ├── 07_inventory_status.sql
│
├── reports/ # Analysis reports & visualizations
│ ├── sakila_eda_summary.xlsx
│ ├── key_insights.md
│
├── README.md # Project documentation
└── LICENSE # License information

```

---

## 👤 About Me
**A. Sai Arvind**  
📊 *Aspiring Data Analyst | SQL | Excel | Power BI | Python*  

Passionate about exploring data and deriving insights that help businesses make data-driven decisions.

📧 **Email:** saiarvind5081@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/saiarvindofficial/ 
🔗 **GitHub:** https://github.com/Sai-Arvind

---

⭐ *If you found this project insightful, please give it a star!* ⭐
