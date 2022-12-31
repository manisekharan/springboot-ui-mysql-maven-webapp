Steps to run the application:


1. Install JDK 1.8
2. Install Apache Maven 4.0.0-alpha-3
3. Install Eclipse IDE for Enterprise Java and Web Developers Version: 2022-12 (4.26.0)
4. Clone the project
   - git clone https://github.com/manisekharan/springboot-ui-mysql-maven-webapp.git
5. Open the project as Maven project in Eclipse
6. Install MySQL Community Server 8.0.31
    - Create database "demo"
    - Update MySQL url, username & password in /src/main/resources/application.properties
        spring.datasource.url=jdbc:mysql://localhost:3306/demo?useSSL=false&serverTimezone=UTC&useLegacyDatetimeCode=false
        spring.datasource.username=X
        spring.datasource.password=X

7. Start the application
    cd springboot-ui-mysql-maven-webapp
    mvn spring-boot:run

8. To access the web application : http://localhost:8080


Learning concepts:

What is REST? 
https://medium.com/extend/what-is-rest-a-simple-explanation-for-beginners-part-1-introduction-b4a072f8740f

What is Microservices?
https://spring.io/microservices
https://medium.com/omarelgabrys-blog/microservices-with-spring-boot-intro-to-microservices-part-1-c0d24cd422c3

What is Spring Framework?
https://www.bmc.com/blogs/spring-framework/

What is Spring Boot?
https://spring.io/projects/spring-boot
https://www.ibm.com/topics/java-spring-boot
https://www.javaguides.net/2022/01/spring-boot-and-microservices-roadmap.html
https://www.javaguides.net/2021/07/spring-boot-tutorial-for-beginners.html
https://www.geeksforgeeks.org/difference-between-spring-and-spring-boot/


Design Concepts

https://12factor.net/
https://www.baeldung.com/spring-boot-12-factor
https://dilankam.medium.com/restful-api-design-best-practices-principles-ded471f573f3
https://www.freecodecamp.org/news/rest-api-best-practices-rest-endpoint-design-examples/
https://www.upgrad.com/blog/spring-boot-annotations/