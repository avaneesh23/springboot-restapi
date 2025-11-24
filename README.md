# SpringBoot application with REST APIs, validation, pagination, JWT token

 Use the below SQL database to create the MySQL database:
 ```sql
 mvn clean install
 ```
 ```sql
 create database myblog
 ```
 ```
 SOURCE myblog-ddl-script.sql
 ```
 ```
 INSERT INTO `roles` VALUES (1,'ROLE_ADMIN'),(2,'ROLE_USER');
 ```
 ```
 mvn spring-boot:run
 ```
