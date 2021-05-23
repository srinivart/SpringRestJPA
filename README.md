# SpringRestJPA


Create Project
------------
https://start.spring.io/



------------------------------------
Project: Maven
Language: Java



Spring Boot : 2.5.0

Project Metadata : 

Group : com.payroll
Artifact: PayrollApplication
Name: PayrollApplication
Description : Demo project for Spring Boot
Pacakge name: payroll

Pacakging : jar



Dependencies: Spring Web
			  Spring Reactive Web
			  Spring Data JPA
			  H2 Database

------------------------------------			  
			  
 
 
 
 
 Check the Port running on :
 
 sof -i :8085 | grep LISTEN
 
 
 
 
 
 Run Application:
 --------------------
 
 $ ./mvnw clean spring-boot
 
 $ mvn clean spring-boot:run
 
 
 
 
 
$ curl -v localhost:8085/employees


$ curl -v localhost:8085/employees/1

$ curl -X DELETE localhost:8080/employees/3


$ curl -X POST localhost:8085/employees -H 'Content-type:application/json' -d '{"name": "Indira", "role": "QA"}'









Resources : https://spring.io/guides/tutorials/rest/



 
 
 
 
 
 
