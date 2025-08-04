# Blinkit Sales Performance Analysis (Power BI Dashboard)

Blinkit is a leading quick-commerce platforms, specializing in delivering groceries and everyday essentials to customers in minutes. The company operates through a network of partnered outlets and fulfillment centers, offering a wide range of products — from fresh produce to packaged goods — via its mobile app and website. The business model focuses on fast delivery, product variety, and convenience, making it a competitive player in the on-demand grocery delivery market.
This project analyzes Blinkit's sales performance, customer satisfaction, and inventory distribution to uncover actionable insights and opportunities for optimization. This analysis was developed in Power BI using Blinkit’s grocery sales dataset, transforming raw data into meaningful business intelligence through KPIs and visual dashboards.

---

## Business Requirement

To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution in order to identify key insights and optimization opportunities. The goal is to visualize these findings through various KPIs and charts for data-driven decision-making.

---

## Dataset Description

The dataset contains transactional-level sales and customer information for various grocery items sold through Blinkit outlets.  

**Key Columns:**
- **Item Identifier** – Unique code for each product  
- **Item Weight** – Weight of the product in kilograms  
- **Item Fat Content** – Fat classification of the product (Low Fat, Regular)  
- **Item Visibility** – % of total display area given to the product in the store  
- **Item Type** – Category of the product (Fruits, Snack Foods, Dairy, etc.)   
- **Outlet Identifier** – Unique code for each outlet/store  
- **Outlet Establishment Year** – Year the outlet was established  
- **Outlet Size** – Store size category (Small, Medium, High)  
- **Outlet Location Type** – City tier classification (Tier 1, Tier 2, Tier 3)  
- **Outlet Type** – Type of store (Grocery Store, Supermarket Type1, etc.)  
- **Sales** – Sales revenue generated for the product in that outlet  
- **Rating** – Average customer rating for the product  

---

## KPI Requirements

1. **Total Sales** – Overall revenue generated from all items sold.  
2. **Average Sales** – Average revenue per sale.  
3. **Number of Items** – Total count of different items sold.  
4. **Average Rating** – Average customer rating for items sold.  

---

## Charts & Business Objectives

### 1. Total Sales by Fat Content  
- **Objective:** Analyze the impact of fat content on total sales.  
- **Additional Metrics:** Average Sales, Number of Items, Average Rating by fat content.  
- **Chart Type:** Donut Chart  

### 2. Total Sales by Item Type  
- **Objective:** Identify performance of different item types in terms of total sales.  
- **Additional Metrics:** Average Sales, Number of Items, Average Rating by item type.  
- **Chart Type:** Bar Chart  

### 3. Fat Content by Outlet for Total Sales  
- **Objective:** Compare total sales across outlets segmented by fat content.  
- **Additional Metrics:** Average Sales, Number of Items, Average Rating by fat content and outlet.  
- **Chart Type:** Stacked Column Chart  

### 4. Total Sales by Outlet Establishment  
- **Objective:** Evaluate how the age/type of outlet establishment influences total sales.  
- **Chart Type:** Line Chart  

### 5. Sales by Outlet Size  
- **Objective:** Analyze correlation between outlet size and total sales.  
- **Chart Type:** Donut/Pie Chart  

### 6. Sales by Outlet Location  
- **Objective:** Assess geographic distribution of sales across locations.  
- **Chart Type:** Funnel Map  

### 7. All Metrics by Outlet Type  
- **Objective:** Provide a complete view of KPIs (Total Sales, Average Sales, Number of Items, Average Rating) by outlet type.  
- **Chart Type:** Matrix Card  

---

## Data Preparation

Before building the dashboard in Power BI, the dataset underwent a data cleaning and transformation process:
- Removed duplicate entries  
- Handled missing values in `Item Weight` and other relevant columns  
- Standardized categorical values (e.g., consistent spelling for Fat Content)  
- Converted columns to correct data types (e.g., numeric for sales, date for establishment year)  
- Created calculated columns for additional insights  
