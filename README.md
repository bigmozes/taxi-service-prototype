# Taxi Service Prototype
## A prototype for Taxi Service Java Web Application
### Features
- Store data about Cars, Cars Manufacturers and Drivers
- Bind multiple Drivers to a Car
- Registering and authenticating as a Driver with ability to view info about 
  current Driver's Cars
- Deletion of Driver, Car or Manufacturer
### How To Use
- Taxi Service Prototype is a Tomcat-based Java Web Application.
- Clone the repo.
- Create Database using SQL scripts from resources/init_db.sql file.
- Edit your database connection credentials in util/ConnectionUtil class. Replace YOUR DATABASE 
  URL with URL like jdbc:mysql://localhost:3306/taxi.
- JDBC driver, used in development:
[com.mysql.cj.jdbc.Driver](https://dev.mysql.com/doc/connector-j/8.0/en/connector-j-usagenotes-connect-drivermanager.html).
- Compile and build running command `mvn clean package`, make sure the build is successful.
- Now you can run the application directly from
IDE ([IntelliJ IDEA](https://www.jetbrains.com/idea/) for example) with configured
[Tomcat](https://tomcat.apache.org/).
- To run locally or to deploy follow instructions on
[Heroku](https://devcenter.heroku.com/articles/java-webapp-runner).
### Technologies
- Model-View-Controller Architectural Pattern.
- Dependency Injection.
- JDBC.
- Java Web.
- [MySQL](https://www.mysql.com/) DBMS.
- JSP with HTML and JSTL markup.
### Credits
- [Bohdan Chupika](https://github.com/boroda4436)
- [Daria Maliuk](https://github.com/MaliukDaria)
- [Mykyta Arkhanhelskyi](https://github.com/Nick97-git)

