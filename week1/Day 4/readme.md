# ------------------------------
# 🔹 Objective
# ------------------------------
# In this phase, the goal is to perform data cleaning, transformation,
# and pattern extraction using PySpark and Regular Expressions (Regex).
# Focus is on handling inconsistent formats, NULL values, and extracting patterns.

# ------------------------------
# 🔹 Problem Summary
# ------------------------------
# Dataset contains:
# - Mixed text patterns (alphabets + numbers)
# - Email, phone, and ID columns needing extraction
# - Missing (NULL) values
# - Inconsistent categorical formats

# Tasks:
# - Clean and standardize data
# - Extract patterns using Regex
# - Handle NULL values
# - Perform PySpark transformations

# ------------------------------
# 🔹 Approach
# ------------------------------
# 1. Load dataset into PySpark DataFrame
# 2. Inspect for NULLs and inconsistencies
# 3. Apply filters to extract required data
# 4. Perform column transformations
# 5. Use Regex for pattern extraction
# 6. Apply sorting and deduplication
# 7. Generate final structured dataset

# ------------------------------
# 🔹 Key Transformations
# ------------------------------

# 🔸 Regex (Regular Expressions)
# - Extract numbers from strings
# - Identify start/end patterns
# - Extract email username/domain
# - Extract phone country codes
# - Separate alphabets and numbers
# Importance: Helps extract structured info from unstructured text

# 🔸 Data Filtering
# - Apply conditions on columns
# - Use AND (&), OR (|)
# Importance: Keeps only relevant data

# 🔸 Column Transformations
# - Rename columns
# - Create new columns
# - Standardize values
# Importance: Improves data consistency

# 🔸 Conditional Logic
# - Use CASE / when conditions
# - Categorize data
# Importance: Applies business rules

# 🔸 NULL Handling
# - Identify missing values
# - Replace using default values or COALESCE
# Importance: Avoids errors and incorrect results

# 🔸 Sorting & Deduplication
# - Sort using columns
# - Remove duplicate rows
# Importance: Clean and organized data

# 🔸 Date Functions
# - Use current date
# - Calculate date differences
# Importance: Time-based analysis

# 🔸 String Operations
# - Convert case (upper, lower, initcap)
# - Split and extract text
# Importance: Improves readability

# ------------------------------
# 🔹 Output / Results
# ------------------------------
# - Cleaned dataset
# - Extracted:
#   * Email parts
#   * Phone country codes
#   * Numeric & alphabetic values
# - Handled NULL values
# - Sorted and deduplicated data

# ------------------------------
# 🔹 Data Engineering Considerations
# ------------------------------
# - Proper NULL handling
# - Correct regex usage
# - Maintain data consistency
# - Validate output at each step

# ------------------------------
# 🔹 Challenges Faced
# ------------------------------
# - Understanding complex regex
# - Extracting exact patterns
# - Handling mixed data types
# - Managing NULL values

# ------------------------------
# 🔹 Learnings
# ------------------------------
# - Regex for pattern extraction
# - Importance of data cleaning
# - PySpark transformations
# - NULL handling techniques
# - Conditional logic usage

# ------------------------------
# 🔹 Topics Covered
# ------------------------------
# - Regex (pattern matching)
# - Data filtering
# - Transformations
# - NULL handling
# - String manipulation
# - Date functions
# - Sorting & deduplication

