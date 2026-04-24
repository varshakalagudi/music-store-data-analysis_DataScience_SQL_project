# 🎵 Music Store Data Analysis (SQL Project)

## 📌 Project Overview

This project focuses on analyzing a digital music store database using SQL.
The goal is to extract meaningful insights related to customer behavior, sales trends, and business performance.

---

## 🎯 Objectives

* Identify top customers based on spending
* Analyze revenue distribution across countries
* Find most popular music genres
* Understand sales performance of artists and tracks
* Derive business insights using SQL queries

---

## 🛠️ Tools & Technologies Used

* PostgreSQL
* SQL

---

## 📂 Dataset Information

The dataset is provided as a SQL dump file:

* `Music_Store_database.sql`

This file contains:

* Database schema (tables, relationships)
* Data inserted using SQL queries

To use the dataset:

1. Create a database in PostgreSQL
2. Run the SQL file
3. All tables and data will be created automatically

---

## 🗂️ Project Structure

```
music-store-data-analysis/
│
├── dataset/                # Contains SQL dump file
├── sql/                    # SQL queries used for analysis
├── schema/                 # ER diagram of database
├── output_screenshots/     # Query outputs
└── README.md               # Project documentation
```

---

## 🧩 Database Schema

The database consists of multiple related tables such as:

* customer
* invoice
* invoice_line
* track
* album
* artist
* genre

### 🔗 Key Relationships:

* A customer can have multiple invoices
* Each invoice contains multiple invoice_line entries
* Each invoice_line represents a track purchase
* Tracks belong to albums and artists

(Refer to the schema diagram in the `schema/` folder)

---

## 🧠 Key Analysis Performed

Some important questions solved in this project:

* Who are the top spending customers?
* Which country generates the highest revenue?
* What are the most popular genres?
* Which artists contribute most to sales?
* What are the top-selling tracks?

All queries are available in the `sql/` folder.

---

## 📊 Sample Outputs

Below are some sample query results:

Quer1(output_screenshots/q1.png)
Query2(output_screenshots/q2.png)

(More screenshots available in the `output_screenshots/` folder)

---

## 💡 Key Insights

* Certain countries contribute significantly more revenue than others
* A small group of customers drives a large portion of sales
* Popular genres dominate overall sales trends
* Some artists consistently perform better across regions

---

## 🚀 Conclusion

This project demonstrates how SQL can be used to analyze relational databases and extract actionable business insights.

---

## 📌 Future Improvements

* Add visualizations using Power BI or Tableau
* Perform advanced analytics using Python
* Build a dashboard for real-time insights

---

## 🙌 Author

Created as part of a data analysis learning project.
