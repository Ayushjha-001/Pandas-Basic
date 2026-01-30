This repository contains my Pandas assignment where I explored and analyzed the Iris flower dataset using Python and Pandas.

The goal of this assignment was to practice:

- Loading datasets

- Exploring structure and statistics

- Filtering data

- Grouping and aggregation

- Creating new derived columns

 ### Files in this Repository

Assignment_pandas.ipynb – Jupyter Notebook containing all solutions

IRIS.csv – Dataset file

README.md – Project description

### Dataset Source

The dataset was taken from Kaggle:

https://www.kaggle.com/datasets/arshid/iris-flower-dataset

###Part A – Dataset Exploration

Displayed first 10 rows

Checked dataset shape

Inspected column data types

Generated summary statistics (mean, std, min, max)

### Part B – Row Filtering

Filtered rows based on:

petal_length > 4.5

species == "Iris-virginica"

Used both boolean indexing and the query() method.

### Part C – Group By & Aggregations

Grouped data by species and calculated:

Average sepal_length

Maximum petal_width

Standard deviation of sepal_width

### Part D – Feature Engineering

Created a new column:

petal_ratio = petal_length / petal_width

Computed the average petal_ratio for each species.

### What I Learned

Through this assignment, I strengthened my understanding of:

Pandas DataFrames and Series

Boolean indexing

query() usage

groupby() and aggregation functions

Creating new columns using vectorized operations

Organizing notebooks for clear analysis

I also learned the importance of:

Writing readable code

Solving tasks step-by-step

Structuring notebooks for GitHub submissions
