# Data-Analysis-with-Python-Udemy-Courses-Data
It is a project of Data Analysis with Python or you can say, Data Science with Python on the "Udemy Courses" Data set.



The commands that we used in this project :

* import pandas as pd -- To import Pandas library.
* pd.read_csv - To import the CSV file in Jupyter notebook.
* head() - It shows the first N rows in the data (by default, N=5).
* unique( ) - It shows the all unique values of the column.
* value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.
* df.sort_values(‘Col_name' ,  ascending=False ) - To sort the dataframe wrt any column values in descending order.
* df[ (df.Col1 = = ‘Element1’) & (df.Col2 == ‘Element2’) ] - Multilevel filtering - And Filter – Filtering the data with two & more items.
* str.contains('Value_to_match’) - To find the records that contains a particular string.
* dtypes - To show datatypes of each column.
* pd.to_datetime(df.Date_Time_Col) - To convert the data-type of Date-Time Column into datetime[ns] datatype.
* dt.year - Creating a new column with only year values.
* df.groupby(‘Col_1’)['Col_2'].max() - Using groupby with two different columns.

.......................................................................

Q. 1) What are all different subjects for which Udemy is offering courses ?
Q. 2) Which subject has the maximum number of courses.
Q. 3) Show all the courses which are Free of Cost.
Q. 4) Show all the courses which are Paid.
Q. 5) Which are Top Selling Courses ?
Q. 6) Which are Least Selling Courses ?
Q. 7) Show all courses of Graphic Design where the price is below 100 ?
Q. 8) List out all the courses that are related to 'Python'.
Q. 9) What are courses that were published in the year 2015 ?
Q. 10) What is the Max. Number of Subscribers for Each Level of courses ?
