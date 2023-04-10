# ![Alt text](images/taxi_left.jpg) Taxi-Service  ![Alt text](images/taxi_right.jpg)

[![My Skills](https://skills.thijs.gg/icons?i=java&theme=light)](https://skills.thijs.gg)

In this simple taxi service implemented CRUD operations.It uses Java Servlet and SQL.

-----------------------------------------

## Features
* Add and Delete cars
* Add and Delete drivers
* Add and delete manufacturers of cars
* Authentication
* Display car/manufacturer/driver
-------------------------------------------

## First steps to run app


1. Clone the repository
2. Open database environment and run SQL script located in following directory 
   src/main/resources/init_db.sql
3. Build the project using Maven
```
mvn clean install
```
4. Deploy WAR file to a servlet container such as Tomcat
   (you can use version 9.0.73)

## Usage

After configuration you have to run your app localy and open in your browser url http://localhost:8080