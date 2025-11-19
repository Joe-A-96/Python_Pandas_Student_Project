# Python Pandas – Skills Overview

This document highlights the key **Pandas skills** demonstrated in the accompanying Jupyter Notebook. It provides a clean, GitHub-ready summary of the data manipulation techniques used.

## 1. Importing the Pandas Library
- Importing Pandas using `import pandas as pd`
- Understanding the requirement to load libraries before using them

## 2. Creating DataFrames Manually
- Creating DataFrames from dictionaries or lists
- Understanding DataFrame structure (rows, columns, indices)
- Practicing basic DataFrame construction to learn core concepts

## 3. Uploading External Data
- Loading CSV and Excel files using:
  - `pd.read_csv("file.csv")`
  - `pd.read_excel("file.xlsx")`
- Using notebook upload features to bring data into the environment

## 4. Exploring a Dataset
Common exploratory functions include:
- `df.head()`
- `df.tail()`
- `df.info()`
- `df.describe()`
- `df.shape`
- `df.columns`
<img width="210" height="248" alt="image" src="https://github.com/user-attachments/assets/2039ad84-d99f-4bfe-8194-3e84f9a27302" />

Key exploration skills:
- Understanding dataset structure
- Identifying missing data
- Interpreting summary statistics
- Reviewing data types

## 5. Selecting Data
### Column Selection
- Selecting a single column: `df["column"]`
- Selecting multiple columns: `df[["col1", "col2"]]`
<img width="380" height="271" alt="image" src="https://github.com/user-attachments/assets/7f8fe85d-bed3-4b8d-a7e3-52ff2ea726ed" />


### Row Selection
- Label-based selection with `.loc`
- Position-based selection with `.iloc`
<img width="325" height="281" alt="image" src="https://github.com/user-attachments/assets/2b29c3cd-d564-41cb-80b9-609a147dd137" />

## 6. Filtering and Conditional Selection
- Filtering using boolean expressions, e.g., `df[df["age"] > 30]`
- Combining multiple conditions using:
  - `&` for AND
  - `|` for OR
  - `~` for NOT
- Building more advanced filtering logic using chained comparisons
  <img width="326" height="311" alt="image" src="https://github.com/user-attachments/assets/f71551c9-823f-4e29-aab1-18ee3a414c5c" />


## 7. Sorting Data
- Sorting by one column with `df.sort_values("column")`
- Sorting by multiple columns with `df.sort_values(["col1", "col2"])`
- Choosing ascending
<img width="336" height="351" alt="image" src="https://github.com/user-attachments/assets/61b00fbb-8276-48c8-b7a4-860560ff9222" />

