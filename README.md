# Employee Management System
A simple Java Swing + JDBC based desktop application to manage employee records.
This is a Java Swing application for managing employee information. This project was created using JDK 17 and Eclipse 2022-12.

It has the following functionalities:

Add employee: Allows you to add a new employee to the system by entering their personal and employment details.
Delete employee: Allows you to delete an existing employee from the system.
Update employee: Allows you to update the personal and employment details of an existing employee.
Display employee: Shows a list of all employees in a JTable, with their personal and employment details

Classes :
The application consists of the following classes:

CreateConnection: This class is responsible for establishing a connection with a database using JDBC. Edit the CreateConnection.java file to provide your database details.
Operations: This class contains methods for inserting, deleting, and updating employee records in the database.
Query: This class contains methods for retrieving employee records from the database.
Windows: This is the main GUI class, which handles user interactions and displays the employee information in a JTable.
Employee: This class stores the personal and employment details of a single employee.

Prerequisites
MySQL database: The application uses a MySQL database to store employee records. The employee.sql file contains the SQL query to create the necessary database and tables.

MySQL Connector library: Add the mysql-connector-java-8.0.22.jar file to your classpath. This library is required to establish a connection with the MySQL database using JDBC.

How to run the application :
Clone the repository to your local machine.
Open the project in an IDE such as Eclipse or IntelliJ.
Build and run the project run window.java file.
The application will open in a new window. Follow the prompts to add, delete, update, or display employees

Demo :
Demo Of this Project is Uploaded on Youtube.
Click Here 👉 Youtube Link
