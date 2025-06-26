# 🚴‍♂️ Bike Store Data Analysis

This project explores and analyzes the **Bike Store Relational Database** (originally published on Kaggle by Dillon Myrick) using **SQLite**, **Pandas**, and **Matplotlib** in Python. The goal is to uncover insights from a simulated retail bike store's sales and customer data through data cleaning, transformation, and visualization.

## 📊 Technologies Used

- **Python 3.x**
- **SQLite** – for relational database queries
- **Pandas** – for data manipulation and analysis
- **Matplotlib** – for data visualization

## 📁 Dataset

The dataset includes 9 CSV files representing tables such as:

- `customers`
- `products`
- `orders`
- `order_items`
- `staffs`
- `stores`
- `brands`
- `categories`
- `stocks`

These are loaded into an SQLite database and used to simulate realistic retail sales and operations data.

> Source: [Bike Store Database on Kaggle](https://www.kaggle.com/datasets/dillonmyrick/bike-store-database)

## 📌 Objectives

- Build an SQLite database from normalized CSV files.
- Explore relationships across customers, sales, products, staff, and stores.
- Analyze KPIs such as:
  - Best-selling products and categories
  - Monthly/yearly sales trends
  - Sales performance by store and staff
  - Customer purchasing behavior
- Visualize key insights with Matplotlib charts.

## 📊 Example Insights

- Top 5 best-selling bikes by revenue
- Monthly revenue trends per store
- Sales distribution across categories
- Performance comparison between staff members

## 🚀 How to Run

```bash
git clone https://github.com/yazdan0101/bike-store-analysis.git
cd bike-store-analysis
pip install requirements.text
jupyter notebook
