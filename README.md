# Spring boot CRUD example using JPA, MySQL Database
implement  CRUD operations with a Product entity.
Creates Product entity and save below product in Mysql database and perform CRUD operations on Product entity to add/update/delete products.
getProducts method will calculate the final price of each product based on discount and other charges table .


# What's inside
This project is based on the Spring Boot project and uses these packages :

Maven
Spring Core
Spring Data (Hibernate & MySQL)
Spring MVC (Tomcat)
Thymlea


# Installation

# 1. You can clone it from github by running following command
  $ git clone https://github.com/niteshsinghrajput/CRUD-Spring-Boot-JPA-MySQL.git
# 2. Import project into eclipse
  File -> open project from file system -> Directory ->  select Project folder from cloned location
# 3. Right click on project in eclipse and then Maven -> Update Projects
# 5. Update database credential and other configuration into application.properties available in src/main/java/resources# 
# 
#changing the server port
server.port=8088
#db specific properties
spring.datasource.url=jdbc:mysql://localhost:3306/product
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=root
#ORM s/w specific properties
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.mvc.pathmatch.matching-strategy = ANT_PATH_MATCHER



