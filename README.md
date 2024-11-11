# API Gateway

Feature Tracker API Gateway application using Spring Cloud Gateway.

## Prerequisites
* JDK 21 or later
* Docker ([installation instructions](https://docs.docker.com/engine/install/))
* [IntelliJ IDEA](https://www.jetbrains.com/idea/)

## How to get started?

```shell
$ git clone https://github.com/feature-tracker/api-gateway.git
$ cd api-gateway

# Run tests
$ ./mvnw verify

# Format code
$ ./mvnw spotless:apply

# Run application
# Run/Debug ApiGatewayApplication.java from your IDE.
# You can also start the application using following command 
$ ./mvnw spring-boot:run  
```
