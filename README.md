# crispy-train
Project Management Software


Resources for Week 1

https://spring.io/guides/gs/gradle/
https://spring.io/guides/gs/rest-service/#scratch




MySQL Resources

Installation Guide: https://dev.mysql.com/doc/refman/8.0/en/installing.html
Starting the Server for the First Time: https://dev.mysql.com/doc/refman/8.0/en/starting-server.html
Testing the Server: https://dev.mysql.com/doc/refman/8.0/en/testing-server.html

1) Install
2) Add to Path
3) Start the Server: https://dev.mysql.com/doc/refman/8.0/en/starting-server.html
4) Test: https://dev.mysql.com/doc/refman/8.0/en/testing-server.html

To use certain commands use syntax:

your_command_here -u root -p

Notes

Problem Point: If none of the commands work at all, check your path. 


Spring Connection to DB 

1) https://spring.io/guides/gs/accessing-data-mysql/
    a) "It is good security practice that after your database is in production state, you make this none and revoke all privileges from the MySQL user connected to the Spring application, then give him only SELECT, UPDATE, INSERT, DELETE."
2) What's a Data Access Layer?
    a) "For example, the DAL might return a reference to an object (in terms of object-oriented programming) complete with its attributes instead of a row of fields from a database table. This allows the client (or user) modules to be created with a higher level of abstraction."