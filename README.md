# Data Analysis with Python and Pandas

## Introduction
Pandas is one of the most powerful and widely used libraries for data analysis in Python. It provides flexible and efficient data structures for handling structured data, such as CSV files, Excel spreadsheets, and SQL databases.

## Installation
To install pandas, use the following command:
```python
pip install pandas
```

## Reading Data
### 1. Read a CSV file
```python
import pandas as pd
df = pd.read_csv("path/to/your/file.csv")
```

### 2. Read an Excel file
```python
df = pd.read_excel("path/to/your/file.xlsx")
```

### 3. Read a JSON file
```python
df = pd.read_json("path/to/your/file.json")
```

## Exploring Data
### 1. Display the first few rows
```python
df.head()
```

### 2. Display the last few rows
```python
df.tail()
```

### 3. Get basic information
```python
df.info()
```

### 4. Get summary statistics
```python
df.describe()
```

## Data Cleaning
### 1. Handling missing values
```python
df.dropna(inplace=True)  # Remove missing values
df.fillna(value="default_value", inplace=True)  # Fill missing values
```

### 2. Renaming columns
```python
df.rename(columns={'old_name': 'new_name'}, inplace=True)
```

### 3. Removing duplicates
```python
df.drop_duplicates(inplace=True)
```

## Data Manipulation
### 1. Selecting columns
```python
df["column_name"]
```

### 2. Filtering data
```python
df[df["column_name"] > value]
```

### 3. Sorting data
```python
df.sort_values(by="column_name", ascending=True)
```

### 4. Grouping data
```python
df.groupby("column_name").sum()
```

# Data Analysis with Python and Pandas

## Introduction
Pandas is one of the most powerful and widely used libraries for data analysis in Python. It provides flexible and efficient data structures for handling structured data, such as CSV files, Excel spreadsheets, and SQL databases.

## Installation
To install pandas, use the following command:
```python
pip install pandas
```

## Reading Data
### 1. Read a CSV file
```python
import pandas as pd
df = pd.read_csv("path/to/your/file.csv")
```

### 2. Read an Excel file
```python
df = pd.read_excel("path/to/your/file.xlsx")
```

### 3. Read a JSON file
```python
df = pd.read_json("path/to/your/file.json")
```

## Exploring Data
### 1. Display the first few rows
```python
df.head()
```

### 2. Display the last few rows
```python
df.tail()
```

### 3. Get basic information
```python
df.info()
```

### 4. Get summary statistics
```python
df.describe()
```

## Data Cleaning
### 1. Handling missing values
```python
df.dropna(inplace=True)  # Remove missing values
df.fillna(value="default_value", inplace=True)  # Fill missing values
```

### 2. Renaming columns
```python
df.rename(columns={'old_name': 'new_name'}, inplace=True)
```

### 3. Removing duplicates
```python
df.drop_duplicates(inplace=True)
```

## Data Manipulation
### 1. Selecting columns
```python
df["column_name"]
```

### 2. Filtering data
```python
df[df["column_name"] > value]
```

### 3. Sorting data
```python
df.sort_values(by="column_name", ascending=True)
```

### 4. Grouping data
```python
df.groupby("column_name").sum()
```

## Data Visualization
### 1. Plot a histogram
```python
import matplotlib.pyplot as plt
df["column_name"].hist()
plt.show()
```

### 2. Line plot
```python
df.plot(x="column_x", y="column_y", kind="line")
plt.show()
```

### 3. Scatter plot
```python
df.plot(kind='scatter', x='column_x', y='column_y')
plt.show()
```

### 4. Bar chart
```python
df["column_name"].value_counts().plot(kind='bar')
plt.show()
```

### 5. Box plot
```python
df.boxplot(column="column_name")
plt.show()
```

### 6. Pie chart
```python
df["column_name"].value_counts().plot(kind='pie', autopct='%1.1f%%')
plt.show()
```

### 7. Correlation heatmap
```python
import seaborn as sns
import matplotlib.pyplot as plt
sns.heatmap(df.corr(), annot=True, cmap="coolwarm")
plt.show()
```

## Saving Data
### 1. Save to CSV
```python
df.to_csv("output.csv", index=False)
```

### 2. Save to Excel
```python
df.to_excel("output.xlsx", index=False)
```

## Conclusion
Pandas is a powerful tool for data analysis and manipulation. By mastering these basic functions, you can efficiently analyze and process large datasets in Python.


