# Run the application

```shell
$ mvn package && java -jar target/gs-spring-boot-0.1.0.jar
```

# Note

The main() method uses Spring Boot’s SpringApplication.run() method to launch an application. There isn't a single line of XML. No web.xml file either. This web application is 100% pure Java and you didn’t have to deal with configuring any plumbing or infrastructure.

# References:

* https://spring.io/guides/gs/spring-boot/