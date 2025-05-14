#  Superstore Sales Analysis Dashboard (Power BI)

This project presents an interactive Power BI dashboard built using the **Sample - Superstore** dataset. The objective is to derive key business insights through visual storytelling, enabling better understanding of sales, profit trends, and product performance across regions.

---

##  Page 1: Executive Overview

### 📌 Visual 1: Total Sales, Profit, Orders (KPI Cards)
- **Visual Type**: Card
- **Metrics Displayed**:
  - Total Sales
  - Total Profit
  - Total Orders (count of Order ID)

---

### 📌 Visual 2: Sales by Region
- **Visual Type**: Map or Stacked Bar Chart
- **Fields Used**:
  - Axis: `Region`
  - Values: `Sales`, `Profit`

---

### 📌 Visual 3: Sales and Profit by Category
- **Visual Type**: Clustered Column Chart
- **Fields Used**:
  - Axis: `Category`
  - Values: `Sales`, `Profit`

---

### 📌 Visual 4: Monthly Sales Trend
- **Visual Type**: Line Chart
- **Fields Used**:
  - Axis: `Order Month Name` (sorted by `Order Month Number`)
  - Legend: `Order Year`
  - Values: `Sales`

---

##  Page 2: Product Performance

### 📌 Visual 1: Top 10 Sub-Categories by Sales
- **Visual Type**: Bar Chart
- **Fields Used**:
  - Axis: `Sub-Category`
  - Values: `Sales`
- **Filter**: Top 10

---

### 📌 Visual 2: Profit by Sub-Category
- **Visual Type**: Bar Chart
- **Fields Used**:
  - Axis: `Sub-Category`
  - Values: `Profit`
- **Enhancement**: Conditional formatting to highlight negative profits

---

### 📌 Visual 3: Sales by Category and Segment
- **Visual Type**: Stacked Column Chart
- **Fields Used**:
  - Axis: `Category`
  - Legend: `Segment`
  - Values: `Sales`

---

### 📌 Slicers (Page-Level Filters)
- `Region`
- `Order Year`
- `Segment`

---

##  Outcome
This Power BI dashboard demonstrates effective data visualization and storytelling by:
- Highlighting trends in sales and profitability
- Comparing regional and category-wise performance
- Enabling dynamic filtering for deeper insights

---

##  Tools Used
- **Power BI Desktop**
- **DAX** (for calculated columns like Year, Month)
- **Power Query** (for date conversion and calculated fields)

---

## 📁 Dataset
- `Sample - Superstore.csv`


