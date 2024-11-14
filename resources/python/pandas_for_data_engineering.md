# 🐍 Pandas for Data Engineering

Using Pandas for data manipulation in data engineering.

## Overview
Pandas is a powerful Python library for data manipulation and analysis. It provides data structures and functions to efficiently manipulate large datasets, making it essential for data engineering tasks.

## Key Features
- **DataFrames**: Two-dimensional, size-mutable, and potentially heterogeneous tabular data.
- **Data Manipulation**: Functions for cleaning, merging, reshaping, and aggregating data.
- **Data Analysis**: Tools for performing data analysis and processing.
  
## Learning Resources

- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/): Official documentation for Pandas.
- [Pandas for Data Engineering - YouTube](https://www.youtube.com/watch?v=2uvysYbKdjM): Video tutorial on using Pandas for data engineering.

⬅️ [Back to Python Overview](../../README.md#-python-for-data-engineering)

## Example Code
Here's an example of reading a CSV and performing a basic data manipulation:

```python
import pandas as pd

# Read a CSV file
df = pd.read_csv('data.csv')

# Basic data manipulation
df['new_column'] = df['existing_column'] * 2
print(df.head())

