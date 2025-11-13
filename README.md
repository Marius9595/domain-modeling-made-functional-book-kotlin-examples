# Domain Modeling Made Functional - Kotlin Examples

This is a basic Kotlin Spring Boot project created to develop examples from the book "Domain Modeling Made Functional".

## Technologies

- **Kotlin** 2.0.0
- **Spring Boot** 3.2.0
- **Gradle** 8.5
- **Java** 17

## Dependencies

The project includes minimal Spring Boot dependencies:
- `spring-boot-starter` - Core Spring Boot functionality
- `spring-boot-starter-web` - Web application support with embedded Tomcat
- `kotlin-reflect` - Kotlin reflection library
- `spring-boot-starter-test` - Testing support

## Building the Project

```bash
./gradlew clean build
```

## Running the Application

```bash
./gradlew bootRun
```

The application will start on `http://localhost:8080`

## Project Structure

```
src/
├── main/
│   ├── kotlin/
│   │   └── com/domain/modeling/
│   │       └── DomainModelingApplication.kt
│   └── resources/
│       └── application.properties
└── test/
    └── kotlin/
        └── com/domain/modeling/
            └── DomainModelingApplicationTests.kt
```