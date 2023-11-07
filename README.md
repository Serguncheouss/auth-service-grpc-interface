### Authentication service gRPC interface

## Description
This project contains only proto files for [the Authentication service project](https://github.com/Serguncheouss/auth-service). 
You can use it for creating a service that will be work with the Authentication service.

## Build
```
mvn clean
mvn install
```
Then you can import a library to your service `pom.xml` file:

```
<dependency>
    <groupId>dev.serguncheouss</groupId>
    <artifactId>auth-service-grpc-interface</artifactId>
    <version>1.0.0</version>
</dependency>
```