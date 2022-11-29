In this project MySQL database is used to store all the data.
 
Its dependecy is added into the 'pom.xml' file and all the properties required to 
the connection of database are return in 'JDBCConnection.java' file.

If you want to use another database, add relevant dependency in 'pom.xml' file 
and do respectiive changes in 'JDBCConnection.java' file.

'App.java' file contains main method, to run project execute this file.
before execution create database schema for this project using the sql queries which are
provided in 'SQL queries.txt' file and then run 'app.java' file.
