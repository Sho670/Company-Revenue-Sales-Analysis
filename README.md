# Company-Revenue-Sales-Analysis



## Project Overview

This project focuses on analyzing company sales and revenue data using **MongoDB**, a NoSQL document-oriented database. The system is designed to store, process, and analyze large volumes of business transaction data efficiently. By using MongoDB aggregation pipelines along with Python-based data analysis tools, the project generates valuable business insights such as revenue trends, product performance, customer behavior, and regional sales analysis.

The primary goal of this project is to demonstrate how MongoDB can be used for real-world business analytics and decision-making processes. The project combines database management, data preprocessing, analytical querying, and visualization techniques to create a complete sales analytics solution.

---

# Objectives

The major objectives of this project are:

- Store company sales data in MongoDB collections.
- Perform data cleaning and preprocessing.
- Analyze revenue, profit, and sales performance.
- Generate business insights using MongoDB aggregation.
- Visualize trends and key performance indicators (KPIs).
- Integrate MongoDB with Python for advanced analysis.

---

# Technologies Used

| Technology | Purpose |
|---|---|
| MongoDB | NoSQL database storage |
| Python | Data analysis and scripting |
| PyMongo | MongoDB-Python connectivity |
| Pandas | Data manipulation |
| Matplotlib / Seaborn | Data visualization |
| Jupyter Notebook | Development environment |

---



# Dataset Description

The dataset used in this project contains company sales transaction records. Each record represents an individual sales order and includes detailed information related to customers, products, pricing, and revenue generation.

## Dataset Fields

| Field Name | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Order Date | Date of transaction |
| Customer Name | Name of customer |
| Product Category | Category of product |
| Product Name | Product purchased |
| Quantity Sold | Number of units sold |
| Unit Price | Price per unit |
| Revenue | Total revenue generated |
| Cost | Product cost |
| Profit | Revenue minus cost |
| Region | Sales region/location |
| Salesperson | Employee responsible for sale |

---


# System Workflow

The project follows the below workflow:

```text
Dataset Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Import Data into MongoDB
        ↓
MongoDB Aggregation Queries
        ↓
Python-Based Analysis
        ↓
Data Visualization
        ↓
Business Insights & Reporting
```

---

# MongoDB Database Structure

The project uses a MongoDB database named:

```bash
companyDB
```

Main collection:

```bash
sales
```

Example MongoDB document:

```json
{
  "order_id": 101,
  "date": "2025-01-15",
  "customer": "ABC Pvt Ltd",
  "region": "South",
  "product": "Laptop",
  "quantity": 5,
  "unit_price": 50000,
  "revenue": 250000,
  "profit": 40000
}
```

---

