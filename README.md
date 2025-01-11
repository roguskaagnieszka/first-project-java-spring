# First Java Spring Project

## Overview
This is a simple Spring Boot application showcasing the basics of web development with Spring. It includes a controller for serving static and dynamic content using Thymeleaf.

## Features
1. **Default Endpoint (`/`)**
    - Displays a greeting message: `Hello Vistula, it is my first Spring Controller!`

2. **Greeting Endpoint (`/greeting`)**
    - Accepts a `name` parameter (e.g., `/greeting?name=John`) and displays: `Hello, John!`
    - Defaults to `Hello, World!` if no name is provided.

## How It Works
- The `HelloController` handles two routes:
    - `/` – Returns a plain text response.
    - `/greeting` – Passes the `name` parameter to a Thymeleaf template (`greeting.html`).
- The Thymeleaf template dynamically renders the greeting and includes a placeholder image.

## Run the Application
1. Start the app:
```bash
   ./mvnw spring-boot:run
```
2. Access endpoints:
- Default: http://localhost:8080/
- Greeting: http://localhost:8080/greeting?name=YourName

## Technologies
- Spring Boot
- Thymeleaf
- Maven

## Additional Resources
- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [Thymeleaf Documentation](https://www.thymeleaf.org/)

