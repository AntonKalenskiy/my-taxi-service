# Taxi-Service

---
![markdown_logo](https://www.pngall.com/wp-content/uploads/13/Taxi-Nyc-PNG-Pic.png)

### Project description:
This is a simple application, which supports authentication and *CRUD* operations. 
### Features:

---
- authentication like a driver;
- create/update/remove a manufacturer;
- create/update/remove a car;
- create/update/remove a driver;
- display list of manufacturers/cars/drivers;
- add driver to a car;
- display all driver`s cars;

### Project structure (3-layer architecture):

---
1. *DAO* - Data access layer
2. *Service* - Application logic layer
3. *Controllers* - Presentation layer

### Used technologies and libraries:

---
- Java 11
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- JDBC
- Javax Servlet
- JSP
- Dependency Injection
- JSTL
- HTML/CSS
- Checkstyle plugin
- Apache Log4j 2

### Instructions to run the project:

---
- Install [IDE](https://www.jetbrains.com/help/idea/installation-guide.html);
- Install [MySQL](https://dev.mysql.com/downloads/installer/);
- Install [Apache Tomcat version: 9.0.xx](https://tomcat.apache.org/download-90.cgi);
- Clone the repo: [https://github.com/AntonKalenskiy/my-taxi-service](https://github.com/AntonKalenskiy/my-taxi-service);
- Configure Apache Tomcat version: 9.0.xx;
- Copy and run SQL script [/src/main/resources/init_db.sql](./src/main/resources/init_db.sql) to creating a schema and tables for the project;
- Configure [/src/main/java/taxi/util/ConnectionUtil.java](./src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
- Configure [/src/main/resources/log4j2.xml](./src/main/resources/log4j2.xml) at line 7 with your ABSOLUTE_PATH to this project;
- Enjoy the application.




