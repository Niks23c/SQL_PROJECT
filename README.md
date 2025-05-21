# 🛒 Amazon Sales Data Analysis (SQL Project)

This project showcases a comprehensive analysis of Amazon sales transaction data using **SQL**. 
It involves **feature engineering**, **data cleaning**, and **exploratory data analysis (EDA)** to uncover key insights into sales trends,
customer behavior, and product performance.

---

## 📁 Dataset Description

- **Source**: Simulated sales transaction data.
- **Columns Include**:
  - Invoice ID
  - Branch & City
  - Customer Type & Gender
  - Product Line
  - Unit Price, Quantity, Total, COGS, Tax5
  - Date & Time of Purchase
  - Payment Method
  - Rating

---

## 🧰 Tools Used

- **MySQL / SQL**
- SQL Features: `JOIN`, `GROUP BY`, `CASE`, `RANK()`, `ALTER`, `UPDATE`, `WITH (CTEs)`, `Aggregate Functions`, and `Window Functions`

---

## 🔧 Key Steps & Features

### 🗂️ 1. Database & Table Setup
- Created `Amazon` database.
- Renamed columns for clarity.
- Checked for nulls and cleaned the data.

### 🧠 2. Feature Engineering
- Extracted:
  - `TimeOfDay`: Morning / Afternoon / Evening
  - `DayName`: Day of the week from date
  - `MonthName`: Month from date
- Created a column `Rating_Sales` based on average sales performance.

### 📊 3. Exploratory Data Analysis
- Total number of cities and branches
- Product line with highest revenue
- Best-performing months and customer types
- Gender distribution across branches
- Payment method trends
- Time and day-based sales and ratings patterns
- VAT contribution analysis

### 🏆 4. Advanced Insights
- Branches performing above average in product sales
- Gender-product preferences using `RANK()`
- Highest average ratings by day and branch

---

## 📌 Insights & Observations

- **Most Revenue-Generating Product Line**: Identified using total sales.
- **Top Revenue City**: Determined through aggregated sales.
- **Customer Behavior**:
  - Preferred Payment Methods
  - Peak Hours and Days for Ratings
  - Gender preferences per branch
- **VAT & COGS Patterns** by month and city

---

## 📂 Project Structure

---

## 🙋‍♂️ Author
  
SQL Analysis by **Nikhil**  
🔗 www.linkedin.com/in/nikhil-c-993548151
