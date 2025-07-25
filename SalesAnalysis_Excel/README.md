# Coffee Shop Order Analysis (Excel Dashboard)

This project focuses on analyzing coffee shop order data using Microsoft Excel. It includes end-to-end data cleaning and the creation of an interactive dashboard using Excel features such as pivot tables, slicers, and charts.

---

## Dashboard Highlights

The Excel dashboard provides the following interactive insights:

- **Order Trends Over Time**  
  A timeline showing how orders fluctuate by date.

- **Interactive Slicers** to Filter Data by:
  - **Cup Size** (e.g., 0.2 Kg, 0.5 Kg, 1.0 Kg, 2.5 Kg)
  - **Roast Type** (e.g., Light, Medium, Dark)
  - **Loyalty Card Usage** (Yes/No)
  - **Order Date** (via timeline)

- **Pivot Charts & Tables** for summarizing:
  - Order frequency by different categories
  - Customer preferences by size and roast
  - Visual filtering and comparative analysis using slicers

---

## Data Cleaning Process

The raw data was cleaned and structured in Excel prior to dashboard development:

- Used `XLOOKUP` to populate missing fields by referencing external tables (e.g., product details or customer info)
- Removed duplicate entries
- Standardized data types, especially for dates and text
- Formatted columns (e.g., date, size, roast type) to ensure consistency
- Created calculated columns where necessary to enable proper filtering and visualization

---

## Business Questions Addressed

- How do coffee orders vary over time?
- What are the most preferred coffee sizes and roast types?
- How does loyalty card usage impact ordering behavior?
- How can filters (size, roast, loyalty) refine customer insights?

---

## Tools Used

- Microsoft Excel for:
  - Data Cleaning
  - Data Transformation
  - Dashboard Design (using Pivot Tables, Slicers, and Charts)
