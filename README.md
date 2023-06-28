# Capstoneprj-Part3

To execute the task of building an Extract Load (EL) pipeline in Python to migrate the World Port Index data from an Access database to PostgreSQL, the following steps were taken:
1.	Install the necessary Python libraries: Ensure that the required Python libraries was installed, such as pyodbc for connecting to the Access database and psycopg2 for connecting to PostgreSQL. 
2.	Set up database connections: Create connections to both the Access database and the PostgreSQL database.
3.	For example, to connect to the Access database, you can use the pyodbc library with a connection string like "Driver={Microsoft Access Driver (*.mdb, *.accdb)};Dbq=path/to/access_database.accdb;". For the PostgreSQL database, you can use the psycopg2 library and provide the necessary connection details such as host, port, database name, username, and password.
4.	Extract data from the Access database: Use SQL queries or other methods to retrieve the required data from the Access database. Write a Python script to execute the queries and fetch the data.
5.	Transform the data (if needed): Perform any necessary transformations on the extracted data, such as filtering, cleaning, or formatting, according to the specific requirements of each question.
6.	Load the data into PostgreSQL: Create tables in the PostgreSQL database that correspond to the questions. Use the psycopg2 library to establish a connection to the PostgreSQL database and execute SQL commands to create the tables. Then, insert the transformed data into the respective tables.
7.	In this case the access database was first saved on my local as a csv file and futher converted to a panda DataFrame for easy readability. The csv was connected to to postgresSQL to insert columns in the tables already created.
9.	separate Python scripts were expected to be written for each question that create the required table in the PostgreSQL database and execute the necessary SQL queries to answer the question. However, time would not enable me proceed with the queries.
I have attched in the repo, scripts that was written to pull the accessdata and converted to my local as csv. tables in the file was also verified to have insights into the data.
