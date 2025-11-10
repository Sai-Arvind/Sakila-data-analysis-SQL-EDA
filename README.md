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

## 🧭 Entity Relationship Diagram (ERD)

The diagram below represents the structure of the **Sakila Movie Rental Database**, 
showing how various entities such as films, customers, stores, staff, and payments are interconnected.

It provides a clear view of **primary–foreign key relationships**, helping understand 
how queries join multiple tables during analysis.

<img width="799" height="521" alt="Sakila - ERD" src="https://github.com/user-attachments/assets/4ffc3c2f-1090-4a1a-88f1-1b94ca97054d" />



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

## 📊 Power BI Dashboard

To visualize the findings from the Sakila SQL analysis, an interactive **Power BI dashboard** was created.  
It highlights key business metrics such as **store-wise revenue**, **top genres**, **rental patterns**, and **customer performance**.

### 🔹 Dashboard Highlights:
- 💰 Total Revenue by Store & Month  
- 🎬 Top Movie Categories and Ratings  
- 👥 Customer Activity & High-Value Segments  
- 🕒 Rental Duration Trends and Late Returns  
- 🌍 Regional Revenue Distribution  

📷 **Dashboard Preview:**
<img width="804" height="459" alt="dvd_dashboard" src="https://github.com/user-attachments/assets/47a21175-d7d7-405e-aad0-c83d2c132566" />

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
Sakila-Data-Analysis-SQL-EDA/
│
├── 📜 README.md                     # Full project documentation (you already wrote)
│
├── 🗄️ SQL_Scripts/                  # Folder for SQL analysis queries
│   ├── 01_store_revenue.sql
│   ├── 02_movie_category.sql
│   ├── 03_top_customers.sql
│   ├── 04_rental_analysis.sql
│   ├── 05_staff_performance.sql
│   ├── 06_geo_revenue.sql
│   ├── 07_inventory_status.sql
│
├── 📊 PowerBI_Dashboard/            # Folder for dashboards & visuals
│   ├── Sakila_Dashboard.pbix        # Power BI file
│   ├── Dashboard_Screenshot.png     # Screenshot of dashboard (for README preview)
│
├── 📁 ER_Diagram/                   # Database schema visualization
│   ├── Sakila_ERD.png
│
├── 📄 Data_Samples/                 # Optional: sample tables (CSV exports)
│   ├── top_customers.csv
│   ├── store_revenue.csv
│
└── 📘 Docs/                         # Optional: supporting notes or queries
    ├── project_notes.txt
    └── insights_summary.txt


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
