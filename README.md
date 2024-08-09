# CashCard Spring Boot Application

This is a Spring Boot application for managing CashCards. The application exposes a RESTful API for creating, retrieving, updating, and deleting CashCards. It also includes basic security configuration and API documentation with Swagger.

## Features

- Create, retrieve, update, and delete CashCards.
- Basic authentication and authorization using Spring Security.
- API documentation with Swagger.
- Unit and integration tests included.

## Prerequisites

- Java 17 or higher
- Gradle 7.x or higher

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/elnaddar/cashcard-spring-boot.git
cd cashcard-spring-boot
```

### Build and Run the Application

You can build and run the application using Gradle.

```bash
./gradlew build
./gradlew bootRun
```

The application will start on `http://localhost:8080`.

### API Documentation

The application uses Swagger for API documentation. Once the application is running, you can access the Swagger UI at:

```
http://localhost:8080/swagger-ui/index.html
```

This will give you an interactive interface to explore and test the API endpoints.

### Running Tests

To run the unit and integration tests:

```bash
./gradlew test
```

## Project Structure

- **src/main/java/example/cashcard**: Contains the main application code.
- **src/test/java/example/cashcard**: Contains the test cases.
- **src/main/resources**: Contains application configuration files and SQL scripts.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
