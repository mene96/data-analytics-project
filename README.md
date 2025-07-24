
Exploratory data analysis using Python and SQL
# Simple EDA script
import pandas as pd

df = pd.read_csv(r"data-analytics-project/data/2025-07-20-20-20-59.csv")
print(df.head())
# Simple EDA script
import pandas as pd

# Load data
df = pd.read_csv(r"data-analytics-project/data/2025-07-20-20-20-59.csv")

# Display first 5 rows
print("Preview of Data:")
print(df.head())

# Summary statistics
print("\nSummary Statistics:")
print(df.describe())

# Missing values
print("\nMissing Values:")
print(df.isnull().sum())
df = pd.read_csv(r"data\2025-07-20-20-20-59.csv")
import os