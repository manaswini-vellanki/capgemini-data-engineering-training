🚀 Phase 6 – SQL Joins, Aggregations & Data Analysis
---
📌 Objective

Develop a strong understanding of SQL joins, grouping, and data analysis techniques by working with multiple related datasets.

This phase focuses on:

Combining data from multiple tables
Applying aggregations using GROUP BY
Solving real-world SQL problems
Understanding relationships between datasets

📊 Problem Summary

Worked with multiple relational tables such as:

employees
departments
projects
salary (optional dataset)

🎯 Goals:

Perform different types of joins
Apply grouping and aggregation operations
Solve multiple SQL practice problems
Handle missing and inconsistent data

⚙️ Approach

🔹 Data Understanding
Analyzed table structures and relationships
Identified primary and foreign keys

🔹 Joins Implementation

Applied appropriate join types based on use case

🔹 Aggregation
Used GROUP BY for summarization
Applied aggregate functions like SUM, COUNT, AVG

🔹 Filtering

Used WHERE for row-level filtering
Used HAVING for aggregated results

🔹 Data Cleaning

Handled NULL values
Removed duplicates
Fixed inconsistent data
Ensured correct data types

🔹 Validation

Verified outputs using sample data
Cross-checked results for accuracy

🛠️ Key Concepts & Transformations

🔗 Joins

INNER JOIN → only matching records
LEFT JOIN → all left + matching right
RIGHT JOIN → all right + matching left
FULL OUTER JOIN → all records from both tables
SELF JOIN → table joined with itself (e.g., employee-manager)

📊 GROUP BY & Aggregations

GROUP BY → groups rows
COUNT(*) → total records
SUM() → total values
AVG() → average values

💻 Example:
SELECT department, COUNT(*) AS emp_count
FROM employees
GROUP BY department;

🔍 Filtering

WHERE → before grouping
HAVING → after aggregation

🧹 Data Cleaning

Removed NULL values
Handled missing relationships
Removed duplicates
Fixed inconsistent data
Ensured correct data types

📈 Outputs / Results

Employee–Manager hierarchy
Employees with/without departments
Projects with/without assigned employees
Department-wise employee counts
Salary aggregation insights
Employees without projects or departments

🧩 Data Engineering Considerations

Used correct join types to avoid data loss
Handled NULL values carefully
Avoided duplicate records during joins
Applied aggregations accurately
Validated results using sample datasets

⚠️ Challenges Faced

Choosing correct join types
Handling NULL values in joins and aggregations
Understanding WHERE vs HAVING
Writing queries for real-world scenarios
Implementing self joins correctly

🎯 Key Learnings

Strong understanding of SQL joins and relationships
Practical knowledge of GROUP BY and aggregations
Ability to solve real-world SQL problems
Clear understanding of filtering techniques
Importance of data cleaning before analysis
Introduction to window functions

🔮 Future Improvements

Add advanced queries (window functions, CTEs)
Optimize query performance
Work with larger datasets
Integrate SQL with PySpark pipelines
