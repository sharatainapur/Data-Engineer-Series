# Data-Engineering

- This project deals with using psycopg2 library which is a POSTGRESQL Database adapter for python.
- Created table and connected to POSTGRES DB via Python.
- We need to create a connection to the database, have a cursor to execute queries and set autocommit as true. 
- Fetch the data from car sales and pushed it to DB by iterating over the rows in the excel file.
- Converted Python Series to a tuple and iterated over them to add to the database. 

- Used the [Car Sales](https://www.kaggle.com/datasets/sachinsachin/car-sales) dataset from Kaggle.
- Dataset consists of 20 different fields most of which are string type / VARCHAR and 4 are Integer type.
