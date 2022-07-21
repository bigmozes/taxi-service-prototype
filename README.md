# Taxi Service Prototype
This project is a prototype or a skeleton for real taxi service management application. It's been 
created during the completion of Java course. Feel free to download, test and contribute.
### Features
- Store data about cars, manufacturers and drivers.
- Add drivers to a car.
- Register a new driver and login as a Driver with ability to view info about your cars.
- Delete drivers, cars or manufacturers.
### How To Use
- Clone the repo.
- Create Database using SQL script from resources/init_db.sql file.
- Edit your database connection credentials and JDBC driver information in util/ConnectionUtil 
  class. Replace YOUR DATABASE URL with URL like jdbc:mysql://localhost:3306/taxi.
- Compile and build running command `mvn clean package`, make sure the build is successful.
- Now you can run the application directly from IDE ([IntelliJ IDEA](https://www.jetbrains.
  com/idea/) for example) with configured
[Tomcat](https://tomcat.apache.org/).
### Used Technologies
- Apache Tomcat
- MySQL
- JDBC
- Servlet
- JSTL
- JSP
- HTML
- Maven Checkstyle Plugin
