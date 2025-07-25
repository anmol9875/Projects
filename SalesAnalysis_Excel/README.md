# ☕ Coffee Shop Order Analysis

This project analyzes coffee shop order data to uncover sales trends, customer preferences, and order behavior across different products, days, and times. Visualizations were created using **Power BI** after cleaning and transforming the data for accurate insights.

---

## 📊 Dashboard Highlights

The following insights are visualized in the Power BI dashboard:

- **% of Sales by Coffee Category**  
  Breakdown of total sales based on categories like Latte, Cappuccino, Espresso, etc.

- **% of Sales by Coffee Size**  
  Analysis of which cup sizes (Small, Medium, Large) are most popular in terms of sales.

- **Daily Trend for Total Orders**  
  Time series trend showing the volume of orders per day.

- **Hourly Trend for Total Orders**  
  Distribution of order volume across different hours of the day.

- **Top 5 Best-Selling Coffees per Category**  
  Identifies the most frequently ordered coffee types within each category.

---

## 🧹 Data Cleaning Process

Before creating the dashboard, the dataset was cleaned and prepared for analysis using a combination of Excel and Power BI. The process included:

- **Populating missing fields using `XLOOKUP`**: Merged related tables and filled in missing data like product names, sizes, or categories by referencing master datasets.
- **Removing duplicate records** to ensure data accuracy.
- **Correcting data types** for numerical, text, and date/time columns.
- **Standardizing date and size formats**, ensuring consistency across all entries (e.g., converting date columns to proper formats, normalizing size labels like `Small`, `Med`, `Medium`, etc.).
- **Splitting and formatting columns** in Power Query for better analysis (e.g., extracting hour from timestamps for hourly trends).

---

## ❓ Business Questions Addressed

- Which coffee categories and sizes generate the highest revenue?
- What are the busiest hours and days for orders?
- Which specific coffee items are the most popular in each category?
- Are there any patterns in ordering behavior over time?

---

## 🛠 Tools Used

- **Excel** for initial data population (using `XLOOKUP`) and cleanup
- **Power BI** for advanced transformation and interactive dashboard creation

---

## 📁 File Structure

```bash
coffee-shop-order-analysis/
├── coffeeOrdersData.xlsx           # Source data file
├── Coffee_Shop_Dashboard.pbix     # Power BI dashboard (optional - add if shared)
└── README.md                       # Project documentation
