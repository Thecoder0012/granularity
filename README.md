# granularity

I chose MySQL because of its ease of use, performance etc. 
I am aware of when it comes to specefic access control and granularity, MySQL might not be the most optimal choice, like PostgreSQL or Oracle. However I still chose MySQL for its simplicity. But for this exercise, making specific permissions to users, since I do not need, for instance, row-level access which MYSQL lacks the support of. 
MySQL can still be used to implement basic levels of granular access. 

For more complex projects/exercises that requires advanced granularity, MySQL would be a bad choice.

# Setup Connection.

1.
- Connect to the MySql server hosted on azure via terminal or workbench.
- hostname: mysqldbserv.mysql.database.azure.com
- username: admi
- password: Mysql1122


2. 
- User with read permission only to person table: 
- username: newuser, password: password

3. 
- User with insert permission only to person table:
- manager: newuser, password: manager


4. 
- User with insert and read permission only to food table:
- manager: foodadmin, password: foodadmin
