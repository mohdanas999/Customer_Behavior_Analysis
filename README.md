# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project focuses on analyzing **customer shopping behavior** using transactional data of 3,900 purchases across different product categories.

The main goal was to understand customer spending patterns, product preferences, discounts, subscriptions, customer segments, and purchase frequency, and then convert these findings into **business insights and actionable recommendations**.

The complete analysis was performed using **Python, MySQL, SQL, and Power BI**.

---

## 🎯 Business Problem

The company wants to better understand its customers and their purchasing behavior to improve:

* Customer engagement
* Sales performance
* Customer loyalty
* Marketing strategies
* Product strategies

The main business question was:

> **How can the company use consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

## 🛠️ Tools & Technologies

* **Python** – Data cleaning and feature engineering
* **Pandas** – Data manipulation and analysis
* **MySQL** – Database management
* **SQL** – Business analysis and customer segmentation
* **Power BI** – Interactive dashboard and visualization
* **GitHub** – Project documentation

---

## 📊 Dataset

**Rows:** 3,900
**Columns:** 18

### Key Data Includes

* Customer demographics – Age, Gender, Location
* Subscription status
* Product and category information
* Purchase amount
* Season and size
* Discount usage
* Previous purchases
* Purchase frequency
* Review ratings
* Shipping type

There were **37 missing values in the Review Rating column**, which were handled during the data cleaning process.

---

## 🔄 Project Workflow

**CSV > Python > MySQL > PowerBI**

### 1. Data Cleaning & Preparation – Python

I started by loading and exploring the raw dataset using Pandas.

Main steps:

* Loaded the dataset using Pandas
* Checked dataset structure using `info()`
* Used `describe()` for statistical understanding
* Checked missing values
* Filled missing Review Ratings using the **median rating of each product category**
* Standardized column names using **snake_case**
* Created an `age_group` column
* Created `purchase_frequency_days`
* Checked the relationship between `discount_applied` and `promo_code_used`
* Removed the redundant `promo_code_used` column
* Connected Python with MySQL and loaded the cleaned data

---

### 2. Business Analysis – MySQL & SQL

After cleaning the data, I loaded it into MySQL and used SQL queries to answer different business questions.

Some of the key analysis included:

* Revenue comparison by gender
* Identifying high-spending discount users
* Finding top-rated products
* Comparing Standard vs Express shipping
* Comparing subscribers vs non-subscribers
* Identifying discount-dependent products
* Customer segmentation into **New, Returning, and Loyal**
* Finding top products within each category
* Analyzing repeat buyers and subscription behavior
* Revenue contribution by age group

---

### 3. Dashboard – Power BI

I built an interactive Power BI dashboard to visualize the major customer behavior patterns and make the analysis easier for business stakeholders to understand.

The dashboard focuses on areas such as:

* Customer demographics
* Purchase behavior
* Product categories
* Discount usage
* Customer loyalty
* Subscription behavior
* Purchase frequency
* Revenue patterns

---

## 💡 Key Business Insights & Recommendations

### 1. Payment Preference

In the **Clothing & Accessories** category, Adult and Young Adult customers showed a higher preference for debit and credit card payments compared with Middle-aged and Senior customers.

**Recommendation:**
Use debit/credit card-based offers and targeted promotions for these customer groups to improve conversions and sales.

### 2. Customer Loyalty

Repeat buyers and subscribers represent an opportunity to increase long-term customer value.

**Recommendation:**
Introduce loyalty rewards and subscription benefits to encourage repeat purchases and move customers towards the **Loyal** segment.

### 3. Discount Dependency

The analysis showed that customers with subscriptions were highly dependent on discounts.

**Recommendation:**
Review the current discount strategy and margins to make sure discounts are driving profitable purchases instead of unnecessarily reducing margins.

### 4. Purchase Frequency

The average purchase frequency for **Clothing & Accessories** was around **90 days**, while the target was **80–85 days**.

**Recommendation:**
Promote new arrivals and relevant product campaigns every **6–8 weeks** to encourage customers to return and purchase sooner.

---

## 📈 Business Value

This project helped convert raw customer transaction data into useful business insights.

The analysis can help a business:

* Understand different customer segments
* Identify high-value and repeat customers
* Evaluate discount dependency
* Improve customer retention strategies
* Understand product preferences
* Optimize promotional campaigns
* Improve purchase frequency
* Make more data-driven marketing decisions

---

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├──Business Problem Statement.pdf
│
├──Report/Customer Shopping Behavior Analysis.pdf
│
├── data/
│   └── customer_shopping_data.csv
│
├── python/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── powerbi/
│   └── Customer Behavior Dashboard.pbix
│
├── presentation/
│   └── Customer Shopping Behavior Analysis.pptx
│
└── README.md
```

---

## 🚀 Project Outcome

This project demonstrates my ability to take a dataset from **raw data to business recommendations** using multiple analytics tools.

**Data Cleaning → SQL Analysis → Power BI Dashboard → Business Insights → Recommendations**

The main focus was on using customer data to answer **real business questions and support decision-making.**
