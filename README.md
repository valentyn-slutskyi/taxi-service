# :taxi: Taxi-service :red_car:

## :pencil:Description
This is a simple project made to show my skills in Java, JDBC, WEB, OOP. You can use basic CRUD operations, such as:

- Registration
- Log in/Log out
- Add car, driver or manufacturer
- Display all cars, drivers or manufacturers
- Delete car, driver or manufacturer
- Add driver to car
- Display all drivers for current car

## :construction:Project structure
The project has 3-Tiers architecture and consists of:
- DAO tier - CRUD and others operation with database;
- Service tier - there happens all business logic with data
- Presentation tier - interaction between the user and the program via browser

## 	:computer: Technologies
- Java 11
- MySQL
- JDBC
- Servlet Api
- JSP
- JSTL
- TomCat


## :hourglass_flowing_sand: Quickstart
- Fork this repository
- Create new project from Version Control
- Create your database using the file `init_db.sql`
- Set your connection parameters in ConnectionUtil.class 
```java
private static final String URL = "URL_OF_DATABASE";
private static final String USERNAME = "USERNAME";
private static final String PASSWORD = "PASSWORD";
private static final String JDBC_DRIVER = "JDBC_DRIVER";
```
For example
```java
private static final String URL = "jdbc:mysql://localhost:3306/taxi?useUnicode=true&serverTimezone=UTC";
private static final String USERNAME = "root";
private static final String PASSWORD = "1234";
private static final String JDBC_DRIVER = "com.mysql.cj.jdbc.Driver";
```
- Add [Tomcat](https://tomcat.apache.org/download-90.cgi) server (tested in 9.0.50 version) and configure it.
- Run project

#### :warning: ***At first, you should register as a new driver. After registration, you can log in the service and use full functional.***

