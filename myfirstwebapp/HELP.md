# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.5/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.5/reference/htmlsingle/index.html#web)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/3.1.5/reference/htmlsingle/index.html#using.devtools)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

##Login jsp
/login => com.dev21.springboot.myfirstwebapp.hello.LoginController => login.jsp


##
localhost:8080/login

B1: Identifies correct Controller method
/login => LoginContrller.gotoLoginPage

B2: Executes Controller Method
=> puts data into model
=>returns view name=> login

B3: Identifies correct view 
/WEB-INF/jas/login.jsp

B4: Executes view

## Todo
-Id
-Username
-description
-targetDate
-done

TodoController
listTodos.jsp



/META-INF/resources/webjars/bootstrap/5.1.3/css/bootstrap.min.css
/META-INF/resources/webjars/bootstrap/5.1.3/js/bootstrap.min.js
/META-INF/resources/webjars/jquery/3.6.0/jquery.min.js