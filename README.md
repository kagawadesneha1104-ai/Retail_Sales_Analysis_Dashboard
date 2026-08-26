# 📊 Retail Sales Analysis Dashboard

**Retail Sales Analysis Dashboard** is a Power BI-based data analytics and business intelligence project focused on analyzing retail sales data across products, categories, customers, regions, order dates, quantities, sales amounts, and profitability.

The project uses **Power BI** to transform a cleaned retail sales dataset into an interactive dashboard that helps users understand sales performance, product trends, customer contribution, regional performance, order volume, quantity sold, and profitability.

The analysis focuses on variables such as **sales, sales amount, profit, quantity, category, sub-category, product name, customer name, region, country, segment, outlet type, city type, order date, and year**, converting raw retail transaction data into meaningful business insights.

---
![alt text](<screenshots/Retail Sales Analysis Dashboard.png>)

## 🚀 Core Features

The project implements a complete retail sales analytics workflow:

### 1. **Data Cleaning & Transformation**

- Loaded the raw retail sales dataset.
- Prepared the dataset for Power BI analysis.
- Used the cleaned retail sales dataset as the source for dashboard development.
- Standardized the data structure required for analysis.
- Prepared sales, quantity, profit, product, customer, geographic, and date-related fields.
- Created a separate cleaned dataset for reporting and visualization.

### 2. **Exploratory Data Analysis**

The project analyzes retail sales information across multiple business dimensions.

The analysis focuses on:

- Total sales amount
- Total sales
- Total profit
- Total quantity
- Order count
- Product performance
- Category performance
- Sub-category performance
- Customer contribution
- Regional performance
- Country-wise sales
- Year-wise sales
- Quantity trends
- Segment performance
- Outlet type
- City type

### 3. **Sales Performance Analysis**

Sales performance is analyzed using different business dimensions including:

- Category
- Sub-category
- Product
- Customer
- Region
- Country
- Year

This helps identify high-performing products and categories and understand how sales change across different business segments.

### 4. **Profitability Analysis**

Profit is analyzed alongside sales and quantity to understand business performance.

The dashboard includes a **Total Profit** KPI and visualizations that allow users to compare profitability across categories, products, customers, regions, and time periods.

### 5. **Quantity & Order Analysis**

The project analyzes the number of products sold and order volume.

Key measures include:

- Total Quantity
- Count of Orders
- Quantity by Product
- Quantity by Year
- Sales and Order Count by Year

### 6. **Interactive Power BI Dashboard**

The final dashboard provides interactive reporting capabilities through:

- Year filters
- Region filters
- Category analysis
- Sub-category analysis
- Customer analysis
- Product analysis
- Geographic analysis
- KPI cards
- Interactive charts

Users can apply filters and explore different parts of the retail sales dataset dynamically.

---

## 📈 Key Analysis Areas

| Analysis Area | Description |
| :--- | :--- |
| **Sales Analysis** | Analyzed total sales and sales amount across different business dimensions |
| **Profit Analysis** | Examined total profit and profitability patterns |
| **Quantity Analysis** | Analyzed the quantity of products sold |
| **Order Analysis** | Examined order volume and order trends |
| **Category Analysis** | Compared sales performance across product categories |
| **Sub-Category Analysis** | Identified sales performance across sub-categories |
| **Product Analysis** | Analyzed sales and quantity by product |
| **Customer Analysis** | Examined sales contribution by customer |
| **Regional Analysis** | Compared sales performance across regions |
| **Country Analysis** | Analyzed sales across countries |
| **Year Analysis** | Examined sales, quantity, and order trends over time |
| **Segment Analysis** | Analyzed sales based on customer segments |
| **Outlet Type** | Examined sales based on outlet type |
| **City Type** | Analyzed retail performance based on city type |

---

## 🛠️ Technology Stack

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Data Visualization** | **Power BI** | Interactive dashboard and business intelligence reporting |
| **Data Preparation** | **Power Query / Power BI** | Data loading, cleaning, and transformation |
| **Dataset** | **Retail Sales Data** | Product, customer, sales, quantity, profit, and geographic information |
| **File Format** | **CSV** | Raw and cleaned retail sales datasets |
| **Dashboard** | **Power BI (.pbix)** | Interactive retail sales analysis dashboard |

---

## 📂 Project Structure

```text
Retail_Sales_Analysis_Dashboard/
│
├── data/
│   ├── raw dataset/
│   │      └── store_sales_data.csv
│   │
│   └── cleaned dataset/
│          └── cleaned_store_sales_data.csv
│
├── documentation/
│          └── Project_Report.pdf
│
│
├── powerbi/
│   └── Retail_Sales_Analysis_Dashbord.pbix
│
├── screenshots/
│   ├── Retail Dashboard.png
│   ├── Retail Sales Analysis Dashboard.png
│   ├── Sales Dashboard.png
│   └── Sales Store Dashboard.png
│
└── README.md
```

---

## 🔄 Data Analytics Workflow

```text
Raw Retail Sales Dataset
        ↓
Data Loading
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Cleaned Retail Sales Dataset
        ↓
Power BI Data Modeling
        ↓
Measures & Aggregations
        ↓
Exploratory Analysis
        ↓
Data Visualization
        ↓
Interactive Dashboard
        ↓
Retail Sales Insights
```

---

## 🔍 Data Cleaning & Transformation

The retail sales dataset was prepared for dashboard development through data preparation and transformation.

The workflow includes:

- Loading the raw retail sales dataset.
- Inspecting the available sales fields.
- Preparing the cleaned dataset.
- Standardizing fields required for reporting.
- Preparing date-related fields for time-based analysis.
- Preparing product and category fields.
- Preparing customer and geographic fields.
- Preparing sales, quantity, and profit fields.
- Validating the cleaned dataset before importing it into the Power BI dashboard.

The cleaned dataset is stored separately from the raw dataset to maintain a clear distinction between source data and analysis-ready data.

---

## 📊 Power BI Dashboard

The Power BI dashboard contains multiple visualizations and KPI cards designed to provide an overview of retail sales performance.

### KPI Analysis

The dashboard includes key business metrics such as:

- **Total Sales Amount**
- **Total Profit**
- **Total Quantity**
- **Total Orders**

These KPIs provide a quick overview of overall retail business performance.

### Sales by Category

A category-level visualization is used to compare sales performance across different categories of goods.

### Sales by Sub-Category

A sub-category analysis helps identify which sub-categories contribute more to overall sales.

### Sales by Product Name

Product-level analysis is used to identify products generating higher sales.

### Sales by Customer Name

Customer-level analysis helps identify customers contributing significantly to total sales.

### Sales and Order Count by Year

A time-based visualization compares sales performance and order count across different years.

### Sales Amount and Quantity by Year

This visualization compares sales amount and quantity sold over time.

### Quantity by Product Name

A product-level quantity visualization shows the number of units sold for different products.

### Sales Amount by Category

Category-level sales amount analysis helps compare the contribution of each category.

### Sales Amount by Sub-Category

Sub-category-level sales amount analysis provides a more detailed view of product-group performance.

### Geographic Analysis

The dashboard includes geographic fields such as:

- Country
- Region
- City Type

These fields can be used to analyze geographic differences in retail performance.

---

## 📌 Dashboard Interactivity

The dashboard provides interactive filtering capabilities.

Users can analyze the data by applying filters such as:

- **Year**
- **Region**
- **Category**
- **Sub-Category**
- **Product**
- **Customer**
- **Country**

The interactive filters allow users to move from a high-level overview to detailed sales analysis.

---

## 📉 Data Visualization

The project uses Power BI visualizations to communicate retail sales insights effectively.

The dashboard includes visual analysis such as:

- KPI cards
- Bar charts
- Column charts
- Line charts
- Sales trend charts
- Category comparisons
- Sub-category comparisons
- Product-level analysis
- Customer-level analysis
- Quantity analysis
- Geographic analysis
- Time-based analysis

The visualizations are designed to make retail sales performance understandable to both technical and non-technical users.

---

## 💡 Key Outcomes

The project successfully transforms retail sales data into an interactive business intelligence dashboard.

### Major outcomes:

- Built a complete **Retail Sales Analysis Dashboard** using Power BI.
- Used separate **raw and cleaned datasets**.
- Prepared retail sales data for business intelligence analysis.
- Analyzed **sales amount, sales, profit, quantity, and orders**.
- Compared performance across **categories and sub-categories**.
- Analyzed individual **products and customers**.
- Examined sales performance across **regions and countries**.
- Analyzed sales and order trends by **year**.
- Compared sales amount with quantity sold.
- Created KPI cards for important business metrics.
- Added interactive filters for detailed analysis.
- Created multiple Power BI visualizations.
- Prepared dashboard screenshots for documentation and presentation.
- Developed a reusable Power BI report for retail sales analysis.

---

## 📦 Requirements

```text
Power BI Desktop
Retail Sales Dataset
CSV Dataset
```

No Python installation is required to open and interact with the `.pbix` dashboard if Power BI Desktop is available.

---

## ▶️ Running the Project

### 1️⃣ Open the Project

Open:

```text
powerbi/Retail_Sales_Analysis_Dashbord.pbix
```

using **Microsoft Power BI Desktop**.

### 2️⃣ Verify the Dataset

The cleaned dataset is available at:

```text
data/cleaned dataset/cleaned_store_sales_data.csv
```

### 3️⃣ Refresh the Dashboard

If required, use:

```text
Home → Refresh
```

to refresh the report data.

### 4️⃣ Explore the Dashboard

Use the available filters and visualizations to analyze:

- Sales
- Profit
- Quantity
- Orders
- Categories
- Sub-categories
- Products
- Customers
- Regions
- Countries
- Years

---

## 🎯 Project Objective

The primary objective of this project is to demonstrate a complete **retail sales analytics and business intelligence workflow**, starting from raw sales data and progressing through **data cleaning, transformation, analysis, visualization, and interactive dashboard development**.

The project demonstrates how Power BI can be used to transform retail transaction data into meaningful business insights and support **data-driven decision-making**.

The final dashboard provides a consolidated view of **sales performance, profitability, order volume, product performance, customer contribution, geographic performance, and time-based sales trends**.
