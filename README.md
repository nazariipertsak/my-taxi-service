# Taxi Service :oncoming_taxi:
# Project description
Simple web-app that supports authentication, registration and other CRUD operations, using SOLID principles and Dependency Injection.
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
https://nazarii-pertsak-taxi-service.herokuapp.com/
# Project structure
Project uses 3-tier architecture:
1. Data access tier -> handled by DAO;
<img src="taxi_models_diagram.jpeg">
2. Business logic tier -> handled by Service;
3. Presentation tier -> handled by Controllers and JSP pages.
# Technologies
- Maven
- Java programming language (JDK 1.8)
- JDBC
- Java Servlet
- JSP and CSS
- Tomcat 9.0.50
- MySQL 8.0
# Instructions to run my project
1. Initialize database <br/>
   Go to
> [src/main/resources/init_db.sql]

Copy content of it and then paste it to your DBMS query. I am using mySQL. <br/>
2. Configure connection to your database in
> [src/main/java/taxi/util/ConnectionUtil.java]

By changing url to your database, username and password. <br/>
3. Run in console [mvn clean package] for project to build up. <br/>
4. Run this in server. I am using Tomcat 9.0.50. <br/>
