# 📊 BlinkIT Power BI Dashboard

### 🚀 Project Overview

The **BlinkIT Power BI Dashboard** is an interactive business intelligence solution designed to analyze and visualize the company’s key performance indicators (KPIs) across sales, customer behavior, and product performance. The dashboard offers a comprehensive view of operations — enabling management to make data-driven decisions related to revenue trends, inventory management, and profitability.

This project demonstrates the application of **data cleaning, modeling, and visualization techniques** in Power BI, turning raw business data into meaningful insights for strategic planning.


<img width="1301" height="717" alt="image" src="https://github.com/user-attachments/assets/f8ae9f83-904e-46e5-b753-f630de3f638c" />
---

## 🎯 Objectives

The primary goals of this project were:

* To develop an **end-to-end data visualization dashboard** highlighting business performance.
* To identify **key revenue drivers, top-performing products, and customer trends**.
* To analyze **sales distribution by outlet type, category, location, and time period**.
* To provide actionable insights that support **data-driven decision-making** for business growth.

---

## 🧩 Dataset Description

The dataset used for this analysis contains detailed transactional and categorical data about BlinkIT’s operations, including:

| **Feature**                 | **Description**                                       |
| --------------------------- | ----------------------------------------------------- |
| `Item_Identifier`           | Unique product ID                                     |
| `Item_Weight`               | Weight of the product                                 |
| `Item_Fat_Content`          | Product nutrition type (Low Fat, Regular, etc.)       |
| `Item_Visibility`           | Share of total display area allocated to the product  |
| `Item_Type`                 | Category of product (Fruits, Dairy, Snacks, etc.)     |
| `Item_MRP`                  | Maximum Retail Price of the product                   |
| `Outlet_Identifier`         | Unique ID for the store                               |
| `Outlet_Establishment_Year` | Year of store establishment                           |
| `Outlet_Size`               | Size classification (Small/Medium/Large)              |
| `Outlet_Location_Type`      | Tier location (Tier 1 / Tier 2 / Tier 3)              |
| `Outlet_Type`               | Type of outlet (Grocery Store, Supermarket, etc.)     |
| `Item_Outlet_Sales`         | Total sales for each product at the respective outlet |

---

## ⚙️ Data Preparation and Modeling

The dataset was imported and transformed using **Power Query Editor** in Power BI. Key steps included:

1. **Data Cleaning:**

   * Replaced null values in `Item_Weight` and `Outlet_Size` columns.
   * Standardized inconsistent labels in `Item_Fat_Content`.
   * Removed duplicates and handled outliers.

2. **Data Transformation:**

   * Created new calculated columns (e.g., *Outlet Age*, *Revenue per Item*).
   * Applied DAX measures for aggregations like Total Sales, Average Sales, and Sales Contribution.
   * Established relationships between **Fact Table (Sales Data)** and **Dimension Tables (Items, Outlets)** using a **Star Schema** model.

3. **Data Modeling Techniques:**

   * **Fact Table:** Sales data
   * **Dimensions:** Item details, outlet information, and time
   * Relationships built on Outlet IDs and Item Identifiers

---

## 📈 Dashboard Features

The Power BI dashboard is divided into multiple interactive pages that provide a 360° business overview:

### 🏪 **Sales Overview**

* Total Sales, Average Sales, and Total Items Sold
* Top-performing Outlets and Products
* Yearly and Monthly Sales Trends
* Dynamic filters for Outlet Type, Item Category, and Location Tier

### 🍱 **Product Analysis**

* Category-wise and Fat Content-wise sales distribution
* Product price range and margin comparison
* Identification of high-selling vs. underperforming products

### 🏙️ **Outlet Performance**

* Comparison of different outlet types (Grocery vs. Supermarket)
* Sales by Location Type (Tier 1 / Tier 2 / Tier 3)
* Impact of Outlet Age on Sales
* Visual maps and heatmaps for geographic insights

### 💰 **Profitability Insights**

* Top 10 contributing items and stores
* Correlation between MRP and Sales
* Average revenue by outlet type and category

---

## 🧠 Key Insights

* **Supermarket Type 3 outlets** generated the highest overall revenue.
* **Medium-sized outlets** had better sales consistency compared to small or large outlets.
* **Regular fat content items** performed slightly better than low-fat variants.
* **Tier 3 locations** contributed the most to overall revenue.
* A clear **positive correlation** exists between MRP and total sales.

---

## 🛠️ Tools & Technologies

| **Tool**                            | **Purpose**                              |
| ----------------------------------- | ---------------------------------------- |
| **Microsoft Power BI**              | Dashboard design and interactivity       |
| **Power Query**                     | Data transformation and cleaning         |
| **DAX (Data Analysis Expressions)** | Custom calculations and KPIs             |
| **Excel/CSV Data Source**           | Raw data import                          |
| **Power BI Service (optional)**     | Publishing and sharing dashboard reports |

---

## 🧾 KPI Metrics Used

* **Total Sales** = SUM(`Item_Outlet_Sales`)
* **Average Sales per Outlet**
* **Total Items Sold**
* **Sales by Category**
* **Sales by Outlet Type**
* **Yearly Sales Growth %**

---

## 📊 Visualizations Used

* Clustered Bar and Column Charts
* Donut and Pie Charts
* Line and Area Graphs
* Tree Map
* Cards and KPIs
* Matrix and Table Views
* Filters and Slicers for dynamic exploration

---

## 🔍 Conclusions

The BlinkIT Power BI dashboard effectively highlights performance gaps, key revenue channels, and customer preferences. By leveraging these insights, BlinkIT can:

* Optimize inventory distribution
* Focus on high-performing product categories
* Expand successful outlet formats
* Adjust pricing strategies for higher-margin products

---

## 🚧 Future Improvements

* Integrate real-time sales data from SQL or API sources.
* Add forecasting visuals using Power BI’s **Analytics pane**.
* Include customer demographics for deeper segmentation.
* Automate report refresh using **Power BI Gateway**.

---

## 👨‍💻 Author

**Puneeth Vijay Krishna Samarla**
📍 M.S. in Information Science (Machine Learning) — University of Arizona
🔗 [LinkedIn](https://www.linkedin.com/in/puneeth-samarla)
📧 [puneethvks9@email.com](mailto:puneethvks9@email.com)


