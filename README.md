# Taxi Service Prototype
This project is a prototype or a skeleton for real taxi service management application. Feel free to download, test and contribute.
### Features
- Store data about cars, manufacturers and drivers.
- Add drivers to a car.
- Register a new driver and login as a Driver with ability to view info about your cars.
- Delete drivers, cars or manufacturers.
### Used Technologies
- Apache Tomcat
- MySQL
- JDBC
- Servlet
- JSTL
- JSP
- HTML
- Maven Checkstyle Plugin
### How To Use
- Clone the repo.
- Create Database using SQL script from resources/init_db.sql file.
- In ConnectionUtil class set up connection credentials to your database: replace YOUR DATABASE URL with URL like jdbc:mysql://localhost:3306/taxi, put in your database username and password and assign JDBC driver you use, for example, com.mysql.cj.jdbc.Driver.
- Compile and build running command `mvn clean package`, make sure the build is successful.
- Now you can run the application directly from IDE ([IntelliJ IDEA](https://www.jetbrains.com/idea/) for example) with configured [Tomcat](https://tomcat.apache.org/).
