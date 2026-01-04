# Virtual Thread Demo

This is a demo project for Spring Boot that showcases the use of virtual threads in Java.

## Prerequisites

- Java 25 or later
- Maven 3.6+

## Building and Running

1. Clone the repository
2. Navigate to the project directory
3. Run the application:

```bash
./mvnw spring-boot:run
```

Or using Maven directly:

```bash
mvn spring-boot:run
```

The application will start on port 8080 by default.

## Endpoints

- `GET /thread/name`: Returns the name of the current thread, demonstrating virtual thread usage.

## Configuration

Virtual threads are enabled in `application.yml`:

```yaml
spring:
  threads:
    virtual:
      enabled: true
```

## Technologies Used

- Spring Boot 4.0.0
- Java 25
- Maven