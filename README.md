# Big Data Revenue Analysis using PySpark

## 📌 Project Overview
This project demonstrates scalable big data analysis using PySpark.  
A synthetic dataset containing 1,000,000 transaction records is generated and analyzed to extract meaningful business insights such as:

- Revenue statistics
- Product performance
- Regional sales analysis
- Customer spending behavior
- Daily and weekly sales trends

The project showcases how Apache Spark can efficiently process and analyze large-scale datasets using distributed computing techniques.

---

# ⚙️ Technologies Used

- Python
- Apache Spark (PySpark)
- Spark SQL Functions
- CSV File Output
- Distributed Data Processing

---

# 📂 Dataset Description

This project generates a synthetic dataset instead of using an external file.

## Dataset Columns

| Column Name | Description |
|-------------|-------------|
| id | Unique transaction identifier |
| product | Product category |
| price | Product price |
| quantity | Quantity purchased |
| region | Sales region |
| customer_id | Unique customer identifier |
| transaction_date | Date of transaction |
| revenue | Total revenue generated |

---

# 🛒 Product Categories

- Laptop
- Mouse
- Keyboard
- Monitor
- Headphones

---

# 🌍 Regions

- East
- West
- North
- South

---

# 🔄 Workflow

## 1. Spark Session Initialization
A Spark session is created to start distributed data processing.

```python
spark = SparkSession.builder \
    .appName("BigDataScalableAnalysis") \
    .getOrCreate()bigdata_revenue_analysis.py
