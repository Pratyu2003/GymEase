# GymEase

# Description

A Gym Management System Project for Gym owner. Gym owner have to Login using Admin credentials. 
Admin can Add, Update, Delete members data, see list of members, search for members using their unique ID.     
Admin can also Search for member's monthly payment status, previous months payments.


# TeckStack:

Java, JDBC, MySQL.


# How to Setup:

1. Open `src/project/ConnectionProvider.java` file and locate the following line:

    ```java
   Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/db_name", "root", "password");
    ```
   Create a MySQL database of desired name.
   Change `db_Name` to the desired name of your database. And replace `password` with your Database password.

# How to Run:

1. Run the command `javac login.java` to compile project 

2. Run the command `java login` to run the project.

# Authentication Credentials

Find Admin Authentication credentials within Project. If unable to find then can contact me at: skillbooster2003@gmail.com

