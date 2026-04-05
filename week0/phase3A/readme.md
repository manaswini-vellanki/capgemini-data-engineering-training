🔹 Objective

In this phase, the goal is to work with messy data and apply data cleaning techniques using PySpark. This ensures that the dataset becomes reliable and ready for further processing and analysis.

🔹 Problem Summary

We were given a dataset containing multiple data quality issues such as missing values, duplicate records, and invalid entries. The task was to:

Identify data quality issues
Clean the dataset
Validate the cleaned data
Perform basic aggregation
🔹 Approach

Loaded the dataset into a PySpark DataFrame and analyzed it to identify issues like null values, duplicates, and invalid records.

Performed data cleaning by:

Removing records with missing key values
Handling null values in important columns
Removing duplicate records
Filtering out invalid data

Validated the cleaned dataset by comparing before and after results, and then performed aggregation to generate insights.

🔹 Key Transformations Used
dropna() → to handle missing values
dropDuplicates() → to remove duplicate records
filter() → to remove invalid data
groupBy() → for aggregation
🔹 Output / Results

The following outputs were generated:

A cleaned dataset with no invalid or duplicate records
Aggregated results showing distribution across categories

Screenshots of outputs are available in the outputs/ folder.

🔹 Data Engineering Considerations
Removed invalid and inconsistent data to improve accuracy
Ensured duplicate records do not impact results
Validated the dataset before performing aggregation
🔹 Challenges Faced
Handling multiple types of data issues within the same dataset
Deciding how to handle missing values without losing important information
🔹 Learnings
Understood the importance of data cleaning in real-world scenarios
Learned different techniques to handle missing and invalid data
Realized how poor data quality can directly impact final results
