## Udacity Tournament

* The **tournament.py** file contains the functions that provide access to the tournament database.
* The **tournament.sql** file contains the definitions of the tables from the tournament database.
* The **tournament_test.py** file contains the functionality tests for this project.

# Creating the database:
Create a PostgreSQL database, called **tournament** with the following psql command:
  *create database tournament;*
Connect to it with the following psql command:
  *\connect tournament;*
Define the tables **players** and **matches** by pasting their definition from **tournament.sql** in psql, or use the following command:
  *\i tournament.sql;*
  
# Run the tests against the files:
Run the tests file, using Python 2.7 with the following terminal command, when in the file's directory:
  *python tournament_test.py*
