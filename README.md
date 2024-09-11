# REST with Spring Boot

A simple Spring Boot project demonstrating a REST API implementation. This project uses Maven for dependency management and follows the Model-View-Controller (MVC) architecture.

## Features
- **RESTful API**: Supports basic CRUD operations.
- **Spring Boot**: Lightweight Java framework to build microservices.
- **Maven**: Project dependency management.
- **Java 17**: Modern Java features and enhancements.

## Prerequisites
- **Java 17** or later
- **Maven** 3.x
- **Spring Boot** 2.7.x

## Getting Started

### Clone the repository
```bash
git clone https://github.com/AhmedAmineDAOU/REST-with-Springboot.git
```

### Build and run the application
```bash
mvn clean install
mvn spring-boot:run
```
Alternatively, you can build the JAR file with
```bash
./mvnw clean package 
```
and then run the JAR file, as follows:
```bash
java -jar target/rest-service-0.0.1-SNAPSHOT.jar
```


## API Endpoints
| Method | Endpoint              | Description            |
|--------|-----------------------|------------------------|
| GET    | `/greeting?name=John` | Returns a greeting message, optionally using a provided name as a query parameter. If no name is provided, "World" is used by default. |

