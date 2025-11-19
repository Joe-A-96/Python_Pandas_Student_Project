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

Key exploration skills:
- Understanding dataset structure
- Identifying missing data
- Interpreting summary statistics
- Reviewing data types

## 5. Selecting Data
### Column Selection
- Selecting a single column: `df["column"]`
- Selecting multiple columns: `df[["col1", "col2"]]`

### Row Selection
- Label-based selection with `.loc`
- Position-based selection with `.iloc`

## 6. Filtering and Conditional Selection
- Filtering using boolean expressions, e.g., `df[df["age"] > 30]`
- Combining multiple conditions using:
  - `&` for AND
  - `|` for OR
  - `~` for NOT
- Building more advanced filtering logic using chained comparisons

## 7. Sorting Data
- Sorting by one column with `df.sort_values("column")`
- Sorting by multiple columns with `df.sort_values(["col1", "col2"])`
- Choosing ascendi
