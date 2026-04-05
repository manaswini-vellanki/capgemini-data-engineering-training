🔹 Objective

In this phase, the goal is to work with a real-world dataset using Databricks and PySpark. This includes data ingestion, validation, building a fact table, performing advanced analytics using window functions, and generating a final reporting dataset.

🔹 Problem Summary

We were given the Olist e-commerce dataset consisting of multiple tables such as orders, customers, order_items, payments, and products.

The task was to:

Upload and manage data in Databricks
Combine multiple datasets
Perform aggregations and analytics
Apply window functions
Generate business insights and final reports

🔹 Approach

Set up the Databricks environment including cluster and notebook.

Uploaded dataset files into the catalog named filestore and schema named olist.

Loaded CSV files into PySpark DataFrames and validated data using schema checks and sample queries.

Created a unified dataset called fact_orders by joining multiple tables.

Performed transformations and aggregations to prepare data for analysis.

Applied window functions for advanced analytics and built the final reporting dataset.


🔹Key Transformations Used

join() → to combine multiple tables
groupBy() → for aggregations
agg() → to calculate metrics like sum and count
withColumn() → to create or modify columns
when() → for segmentation logic
window functions → for ranking and running totals

🔹 Analytical Tasks Performed

Top 3 customers per city using ranking
Running total of daily sales
Top products per category using dense_rank
Customer Lifetime Value calculation
Customer segmentation into Gold, Silver, and Bronze
Final reporting table creation

🔹 Output / Results

The following outputs were generated:

Customer-level spend and segmentation
Product-level sales insights
Daily and cumulative sales trends
Final combined reporting dataset for analysis

🔹 Data Engineering Considerations
Ensured correct join conditions between tables
Avoided duplicate records during joins
Validated data using row counts and sample checks
Used appropriate data types for accurate calculations

🔹 Challenges Faced
Understanding relationships between multiple tables
Handling missing columns like product category
Managing file paths and data access in Databricks
Writing correct window functions for different use cases

🔹 Learnings
Gained experience working with real-world datasets
Understood the importance of building a fact table
Learned how to use window functions for analysis
Built an end-to-end data pipeline
Applied business logic through customer segmentation

🔹 Pipeline Overview

Data Ingestion → Load CSV files
Data Validation → Check schema and data quality
Data Transformation → Join tables and create fact table
Analytics → Apply aggregations and window functions
Reporting → Generate final dataset
