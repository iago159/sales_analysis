# Sales Analysis

## About

In this project is used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

## Technologies 

- Python (Jupyter Notebook)
- Pandas library
- Matplotlib library

## Clean up the data

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

## Business questions related to the data

### Questions
- What was the best month for sales? How much was earned that month?
- What city had the highest number of sales?
- What time should we display advertisements to maximize likelihood of customer's buying product?
- What products are most often sold together?
- What product sold the most?
- Why do you think it sold the most?

### Methods used to answer the questions:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
