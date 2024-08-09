# CashCard Spring Boot Application

This is a Spring Boot application for managing CashCards. The application exposes a RESTful API for creating, retrieving, updating, and deleting CashCards. It also includes a basic security configuration.

## Features

- Create, retrieve, update, and delete CashCards.
- Basic authentication and authorization using Spring Security.
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

### Running Tests

To run the unit and integration tests:

```bash
./gradlew test
```

### API Documentation

API endpoints and their usage are documented in the source code comments. You can access the API via tools like Postman or curl.

## Project Structure

- **src/main/java/example/cashcard**: Contains the main application code.
- **src/test/java/example/cashcard**: Contains the test cases.
- **src/main/resources**: Contains application configuration files and SQL scripts.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
