# This project simulates a MySQL database and includes the following functionalities:

## Create Database user
Creates a system user called "oracle" by default.
Asks for a new admin user and adds them to a file called DB_admins.db.
Displays a message if the user already exists.
## Delete Database User
Only users in DB_admins.db can run this script.
Shows a list of users in DB_admins.db and deletes the selected user.
User "oracle" cannot be deleted.
## Create new Database
Only users in DB_admins.db can run this script.
Asks for a database name and creates a directory under MySQL/DataBases with that name.
Creates a file called owner.txt in the database directory with the user name of the creator.
Displays a message with the name of the created directory.
## Delete an existing Database
Only users in DB_admins.db can run this script.
Shows a list of available databases and deletes the selected one if the user is the owner.
## Create a new Table inside Database
Only users in DB_admins.db can run this script.
Shows a list of available databases and asks for the database name.
Asks for the table name and the number of columns to be created.
Asks for the column names and creates a file with the entered table name and columns.
## Insert a New Row in a Table
Only users in DB_admins.db can run this script.
Shows a list of available databases and asks for the database name.
Shows a list of available tables and asks for the table name.
Asks for the data to be inserted and inserts a new row into the selected table.
## Select Data from Table
Shows a list of available databases and asks for the database name.
Shows a list of available tables and asks for the table name.
Displays the content of the selected table or shows rows that contain a specific string.
## Delete Row from Table 
Deletes rows from the selected table that contain a specific string and displays the updated table.
