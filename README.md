# Taxi Service :oncoming_taxi:
# Project description
Simple web-app that supports authentication, registration and other CRUD operations.
# Features
- registration like a driver
- authentication like a driver
- create/update/remove a manufacturer
- create/update/remove a car
- create/update/remove a driver
- display list of all manufacturers
- display list of all cars
- display list of all drivers
- adding driver to a car
- driver logging out
- display list of all cars connected to current driver
# Deployed project link

# Project structure
Project uses 3-tier architecture:
1. Data access tier -> handled by DAO;
2. Business logic tier -> handled by Service;
3. Presentation tier -> handled by Controllers and JSP pages.

# Technologies
- Maven
- Java programming language
- JDBC
- SOLID principles
- Dependency injection
- Java Servlet
- JSP
- HTML
- CSS
- Tomcat 9.0.50
- MySQL 8.0

# Instructions to run my project
1. Initialize database <br/>
Go to [src/main/resources/init_db.sql] and copy content of it and then paste it to your DBMS query. I recommend using mySQL.
2. Configure connection to your database in [src/main/java/taxi/util/ConnectionUtil.java] by changing url to your database, username and password.
3. Run in console [mvn clean package] for project to build up.
4. Run this in server. I am using Tomcat 9.0.50, but you can use which you want.
