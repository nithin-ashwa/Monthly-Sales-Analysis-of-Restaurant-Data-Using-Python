# Monthly Restaurant Sales Insights Using Pandas & Seaborn

This project performs an in-depth analysis of restaurant sales data stored in a CSV file. It leverages powerful Python libraries including `pandas`, `matplotlib`, and `seaborn` to generate insights into monthly performance, item popularity, and customer behavior.

---

## 📊 Project Objectives

- Load restaurant sales data from a CSV file.
- Identify the date with the highest average final total.
- Count the total number of unique invoices.
- Find the most sold item in September 2023.
- Identify the least popular product categories in July 2023.
- Visualize:
  - Low-selling categories in July with bar charts.
  - Sales distribution across categories using a pie chart.
- Calculate the average bill amount across all transactions.

---

## 📁 Dataset Features

The dataset (`Data.csv`) contains the following key columns:
- `Date`
- `Invoice No.`
- `Item Name`
- `Category`
- `Qty.` (Quantity)
- `Final Total`

---

## 📌 Key Findings

- 📅 **Date with Highest Average Final Total** – Identified and sorted.
- 🧾 **Total Unique Invoices** – Counted using `nunique()`.
- 🥇 **Top-Selling Item in September** – Based on total quantity sold.
- 📉 **Lowest Performing Categories in July** – Sorted by total quantity.
- 💰 **Average Bill Amount** – Calculated by dividing total sales by number of bills.

---

## 📈 Visualizations

- **Bar Plot** – For the least performing categories in July.
- **Pie Chart** – Showing the share of total revenue by category.

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🚀 How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/restaurant-monthly-analysis.git
   cd restaurant-monthly-analysis
