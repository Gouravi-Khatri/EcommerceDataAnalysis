# Ecommerce Data Analysis with SQL & Python

## Project Overview

In today’s digital world, e-commerce generates massive volumes of transactional data every second. Analyzing this data is essential to uncover patterns, track customer behavior, and generate business insights that drive growth.

This project focuses on **end-to-end e-commerce data analysis** using **PostgreSQL (NeonDB)** for database operations and **Python (Google Colab)** for integration, cleaning, and visualization. The dataset used is `data.csv`, which contains detailed transaction-level information such as product IDs, quantities, prices, and customer records.

By combining **SQL for structured queries** and **Python for data handling**, this project highlights how data can be turned into **actionable business intelligence**.

---

## 🎯 Objectives

The project was built with the following goals:

* ✅ Load raw e-commerce transactional data into a **PostgreSQL database (NeonDB)**.
* ✅ Perform **data cleaning and transformation** using Python.
* ✅ Write and execute **SQL queries** to answer important business questions.
* ✅ Calculate **key metrics** like Total Revenue, Sales by Country, and Top Customers.
* ✅ Blend **Python + SQL** for smooth analysis, making results easily reproducible.
* ✅ Showcase how **data-driven insights** can support decision-making in e-commerce.

---

## ⚙️ Tech Stack

* **Python** → Data cleaning, preprocessing, integration with SQL
* **Pandas** → Data manipulation
* **SQLAlchemy** → Connecting Python with NeonDB PostgreSQL
* **PostgreSQL (NeonDB)** → Running SQL queries at scale
* **Google Colab** → Notebook environment for coding and analysis

---

## 📊 Analysis Performed

Here are some of the business insights explored in this project:

1. **Total Revenue Calculation**

   * Derived by multiplying `Quantity × UnitPrice` across all transactions.
   * Helps understand overall sales trends.

2. **Top 10 Best-Selling Products**

   * Identified products that contribute the most revenue.
   * Useful for inventory planning and promotional strategies.

3. **Top Customers by Revenue**

   * Pinpointed loyal and high-value customers.
   * Supports CRM (Customer Relationship Management).

4. **Sales by Country**

   * Revenue breakdown per country.
   * Assists in market expansion decisions.

5. **Monthly Sales Trends**

   * Time-series analysis of sales growth.
   * Detects seasonality and demand cycles.

---

## 🚀 Why This Project Matters

This project is not just about running SQL queries—it is about showing how **a Product Manager or Analyst can leverage data to drive business strategy**.

* 📦 **For E-commerce Companies**: It demonstrates how simple SQL-based analysis can generate high-value insights.
* 👩‍💼 **For Product Managers**: It shows the link between customer behavior and revenue.
* 📊 **For Data Enthusiasts**: It bridges raw data → cleaned database → SQL queries → actionable insights.

---

## 📂 Project Structure

```
EcommerceDataAnalysis/
│── data.csv                # Dataset
│── SQL.ipynb               # Main Jupyter Notebook (SQL + Python analysis)
│── README.md               # Project documentation (this file)
```

---

## 🧭 How to Run This Project

1. Clone this repo:

   ```bash
   git clone https://github.com/Gouravi-Khatri/EcommerceDataAnalysis.git
   cd EcommerceDataAnalysis
   ```

2. Install dependencies (in Google Colab or locally):

   ```bash
   pip install pandas sqlalchemy psycopg2
   ```

3. Update your NeonDB PostgreSQL connection string in the notebook.

4. Run `SQL.ipynb` step by step to reproduce the analysis.

---

## 🌟 Future Work

* Add **interactive dashboards** (Streamlit / Power BI).
* Expand analysis to include **customer lifetime value**.
* Use **predictive models** for demand forecasting.

---

## ✨ Author

👩‍💻 **Gouravi Khatri**

* 📖 BS Economics with Minor in Data Science & Engineering
* 🔍 Passionate about Product Management, Business Analytics, and Data-Driven Decision Making
* 🌏 Loves traveling, exploring cultures, Sudoku & chess
---
