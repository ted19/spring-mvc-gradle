Spring MVC (Gradle, JSP)
===============================
_P.S This tutorial is NOT a Spring Boot application, just pure Spring Web MVC!_

## 1. Technologies and tools used:
* Java 17
* Spring 5.3.25
* JSP
* JSTL 1.2
* Servlet API 4.0.1
* Bootstrap 5.2.3 (webjars)
* Spring Tool Suite 4
* Gradle 8.0.1
* Gradle Gretty plugin 3.0.9 for embedded servlet containers (Tomcat 9 and Jetty 9.4)
* Spring Test 5.2.3
* Hamcrest 2.2
* JUnit 5.9.2

## 2. How to run this project?
```shell
$ git clone https://github.com/mkyong/spring-mvc-gradle/

$ cd spring-mvc-gradle

$ gradle tomcatRunWar

or

$ gradle jettyRunWar

# visit http://localhost:8080/

# visit http://localhost:8080/hello/vgam
```
