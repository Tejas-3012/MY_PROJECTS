# MARVELLOUS FULL STACK PROJECT

## Project Title

MarvellousFullStack

## Project Description

MarvellousFullStack is a Spring Boot application that demonstrates a RESTful backend integrated with MongoDB. The project is built using Maven and follows a layered architecture consisting of Controller, Service, Repository, and Entity packages.

The application manages Batch Entry records and provides REST APIs for performing operations on the MongoDB database.

---

## Technologies Used

* Java 17
* Spring Boot 3.4.12
* Spring Web
* Spring Data MongoDB
* MongoDB
* Maven
* Lombok

---

## Project Structure

MarvellousFullStack/

├── src/

│   ├── main/

│   │   ├── java/

│   │   │   └── com.marvellous.MarvellousFullStack/

│   │   │       ├── Controller/

│   │   │       ├── Service/

│   │   │       ├── Repository/

│   │   │       ├── Entity/

│   │   │       └── MarvellousFullStackApplication.java

│   │

│   └── resources/

│       └── application.properties

│

├── pom.xml

├── mvnw

├── mvnw.cmd

└── README.txt

---

## Features

* REST API using Spring Boot
* MongoDB database connectivity
* Layered architecture
* Maven project structure
* Health Check API
* Batch Entry management

---

## Dependencies

* spring-boot-starter-web
* spring-boot-starter-data-mongodb
* lombok
* spring-boot-starter-test

---

## Database Configuration

Database : MongoDB

Host : localhost

Port : 27017

Database Name : MarvellousFullStackX

The database configuration is stored in:

src/main/resources/application.properties

---

## Requirements

* Java JDK 17 or above
* Apache Maven
* MongoDB Server
* IntelliJ IDEA / Eclipse / VS Code

---

## How to Run

1. Install Java JDK 17.

2. Install MongoDB and start the MongoDB service.

3. Clone or download the project.

4. Open the project in your preferred IDE.

5. Build the project using Maven.

6. Run:

MarvellousFullStackApplication.java

or execute:

mvn spring-boot:run

---

## Package Description

Controller

* Contains REST API endpoints.
* Handles HTTP requests and responses.

Service

* Contains business logic.

Repository

* Provides database operations using Spring Data MongoDB.

Entity

* Defines MongoDB document models.

---

## Project Architecture

Client

↓

Controller

↓

Service

↓

Repository

↓

MongoDB Database

---

## Main Components

* MarvellousFullStackApplication
  Main Spring Boot application.

* BatchEntryController
  Handles Batch Entry API requests.

* BatchEntryService
  Implements business logic.

* BatchEntryRepository
  Performs MongoDB operations.

* BatchEntry
  Entity representing batch information.

* HealthCheck
  Provides application health status endpoint.

---

## Build Command

mvn clean install

---

## Run Command

mvn spring-boot:run

---

## Future Enhancements

* User Authentication
* JWT Security
* Swagger API Documentation
* Exception Handling
* Validation
* Logging
* Pagination
* Docker Support
* Unit and Integration Testing

---

## Learning Outcomes

This project demonstrates:

* Spring Boot application development
* REST API creation
* MongoDB integration
* Maven project management
* Layered architecture
* Dependency Injection
* Spring Data Repository

---

## Author

Project Name : MarvellousFullStack

Framework : Spring Boot

Database : MongoDB

Language : Java 17

Build Tool : Maven
