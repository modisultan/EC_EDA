# Product Sales for Electronic company


### Abstract:

The goal of this project is to analyze sales performance for improving sales for the future months. The used data in this project provided by <a href="https://www.kaggle.com/knightbearr/sales-product-data">Kaggle</a>.

### Design::

This project is one of the T5 Data Science Boot Camp requirements the data provided by <a href="https://www.kaggle.com/knightbearr/sales-product-data">Kaggle</a>. The problem is the electronic company wants to analyze sales performance to improve sales for the future months. To solve this problem, we need to answer three questions:

Q1. What product ordered the most?

Q2. At any day orders are increased?

Q3. what week have the highest earning in this month?


### Data:

Dataset is provided in .CSV format.it contains of 18383 rows and 6 columns, each order has 10 features after modifying the data as we need, the most relevant feature to this project is the product which contains the product name. Some other features are extracted from other feature like total price extracted from quantity order and price each. Also, we extracted date only from order date after that we can extract the week number based on the date.


### Algorithms:

1.	Convert data type of features 
2.	Adding four features 
3.	Data Cleaning 
4.	Using Group By and compute sum on specific column 
5.	Visualized data

### Tools:

•	NumPy and Pandas for data manipulation

•	Matplotlib for visualize the data

•	Datetime for working with dates


