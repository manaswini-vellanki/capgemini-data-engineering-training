# Phase 5 –  Databricks + Olist: End-to-End Data Engineering Pipeline

## 🔹 Objective  
In this phase, I worked on a real-world dataset using Databricks and PySpark. The goal was to build a complete data pipeline starting from data ingestion and validation, followed by building a fact table, performing advanced analytics using window functions, and finally generating a reporting dataset.

---

## 🔹 Problem Summary  
The dataset used was the Olist e-commerce dataset, which consists of multiple related tables such as orders, customers, order_items, payments, and products.  

The main tasks included:
- Managing and loading data in Databricks  
- Combining multiple datasets  
- Performing aggregations and analysis  
- Applying window functions  
- Generating business insights and final reports  

---

## 🔹 Approach  

- Set up Databricks environment (cluster and notebook)  
- Uploaded dataset files into filestore under the olist schema  
- Loaded CSV files into PySpark DataFrames  
- Validated data using schema checks and sample queries  
- Created a unified dataset (`fact_orders`) using joins  
- Performed transformations and aggregations  
- Applied window functions for advanced analytics  
- Built the final reporting dataset  

---

## 🔹 Key Transformations Used  

- `join()` → to combine multiple tables  
- `groupBy()` → for aggregations  
- `agg()` → to calculate metrics like sum and count  
- `withColumn()` → to create or modify columns  
- `when()` → for segmentation logic  
- Window functions → for ranking and running totals  

---

## 🔹 Analytical Tasks Performed  

- Top 3 customers per city using ranking  
- Running total of daily sales  
- Top products per category using `dense_rank`  
- Customer Lifetime Value calculation  
- Customer segmentation (Gold, Silver, Bronze)  
- Final reporting table creation  

---

## 🔹 Output / Results  

- Customer-level spend and segmentation  
- Product-level sales insights  
- Daily and cumulative sales trends  
- Final combined reporting dataset  

---

## 🔹 Data Engineering Considerations  

- Ensured correct join conditions between tables  
- Avoided duplicate records during joins  
- Validated data using row counts and sample checks  
- Used proper data types for accurate calculations  

---

## 🔹 Challenges Faced  

- Understanding relationships between multiple tables  
- Handling missing columns like product category  
- Managing file paths in Databricks  
- Writing correct window functions  

---

## 🔹 Learnings  

- Worked with real-world datasets  
- Understood importance of fact tables  
- Gained hands-on experience with window functions  
- Built an end-to-end data pipeline  
- Applied business logic through segmentation  

---

## 🔹 Notebook Link

https://dbc-f8297b85-0c36.cloud.databricks.com/editor/notebooks/163268703148572?o=7474649877921584

## 🔹 Pipeline Overview  

Data Ingestion → Load CSV files  
Data Validation → Check schema and data quality  
Data Transformation → Join tables and create fact table  
Analytics → Apply aggregations and window functions  
Reporting → Generate final dataset  
