# Run the application

```shell
$ mvn package && java -jar target/gs-spring-boot-0.1.0.jar
```

Then access http://localhost:8080 from the browser.

# Note

The main() method uses Spring Boot’s SpringApplication.run() method to launch an application. There isn't a single line of XML. No web.xml file either. This web application is 100% pure Java and you didn’t have to deal with configuring any plumbing or infrastructure.

# pom.xml

## Spring Boot Maven plugin

* It collects all the jars on the classpath and builds a single, runnable "über-jar", which makes it more convenient to execute and transport your service.

* It searches for the public static void main() method to flag as a runnable class.

* It provides a built-in dependency resolver that sets the version number to match Spring Boot dependencies. You can override any version you wish, but it will default to Boot’s chosen set of versions.

# References:

* https://spring.io/guides/gs/spring-boot/
* https://docs.spring.io/spring-boot/docs/1.5.8.RELEASE/maven-plugin/