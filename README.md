<h1>Udacity Data Modeling</h1>

<h1>SQL Database for Sparkify</h1>

<h2>Project Description</h2>

The goal of this project is to create a SQL database for a music streaming startup called Sparkify. Their analytics team would like to learn who their users are and what songs users are listening to. Creating this SQL database will provide the team with an easy way to query it's data. The data is stored in raw JSON logs with information on user activity, as well as a directory with JSON metadata on the songs that users have listened to.

<h2>Files and Instructions</h2>

The files included in this project are as follows:

<b><i>create_tables.py</b></i>: This Python file creates the Sparkify database, and drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts.

<b><i>etl.ipynb</b></i>: The code within this notebook reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.

<b><i>etl.py</i></b>: This Python file reads and processes files from song_data and log_data and loads them into your tables. This file is based on the work done in the "etl.ipynb" notebook.

<b><i>README.md</b></i>: provides discussion on this project.

<b><i>sql_queries.py</b></i>: This Python file contains all our sql queries, and is directly integrated with the "etl.py", "etl.ipynb", and "create_tables.py" files.

<b><i>test.ipynb</b></i>: displays the first few rows of each table to let us check on the database.

<b>How to Run:</b>

Open a new Terminal and run the following lines of code to accomplish to accompanying tasks.

Run <b><i>python create_tables.py</b></i> to create the database and tables.

Run <b><i> python etl.py</b></i> to process for loading, extracting and inserting the data.

Run the blocks of code within <b><i>test.ipynb</b></i> to confirm the creation of database and columns.
