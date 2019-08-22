# sample-springboot-app
A simple rest based application created using spring-boot

## Steps to build

### Clone
git clone https://github.com/nagendra547/springboot-app.git

### cd to sample-springboot-app folder
```cd sample-springboot-app```

### Build the java project using maven
```mvn clean install```

### Run the application
```java -jar target/spring-boot-web-0.0.1-SNAPSHOT.jar```

Once this app is running, you should see a notification in console
```
2019-08-22 11:57:17.815  INFO 41375 --- [           main] com.nagendra.SpringBootWebApplication    : Started SpringBootWebApplication in 11.621 seconds (JVM running for 12.421)
```

## Access from Browser
http://localhost:8080/swagger-ui.html#/product-controller

Feel free to explore the productController API





