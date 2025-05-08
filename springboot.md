Spring Boot Basics
What is Spring Boot?
Spring Boot is an open-source, Java-based framework designed to simplify the development of stand-alone, production-grade Spring-based applications. It builds on the Spring Framework by providing prebuilt configurations and embedded servers, enabling faster and more efficient application development.
Spring Boot = Spring Framework + Prebuilt Configuration + Embedded Servers
Components of Spring Boot

Spring Boot Starters: Pre-configured dependency templates that simplify build configuration for specific functionalities (e.g., web, data, security).
Auto Configuration: Automatically configures the application based on dependencies and properties, reducing manual setup.
Spring Boot Actuator: Provides production-ready features like monitoring, metrics, and health checks.
Embedded Server: Includes built-in servers (e.g., Tomcat, Jetty) for running applications without external server setup.
Spring Boot DevTools: Enhances development by enabling features like automatic restarts and live reload.

Advantages of Spring Boot

Stand-alone Applications: Runs independently without requiring external server deployment.
Quick Start: Simplifies setup with starters and default configurations.
Minimal Configuration: Reduces boilerplate code and manual configuration.
Faster Development: Accelerates application development, reducing time and cost.

Spring Boot Architecture
Spring Boot follows a layered architecture where each layer communicates with the next, ensuring modularity and maintainability.
Layers

Presentation Layer: Handles user interaction and presents data. Contains controller classes that manage HTTP requests and responses.
Service Layer: Encapsulates business logic and processes data between the presentation and data access layers.
Data Access Layer: Manages data persistence and retrieval. Contains repository classes for database operations.

First Hello World API
Below is an example of a simple Spring Boot REST API that returns a "Hello Spring" message.
package com.project.first.spring;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class HelloController {

    @GetMapping("/hello")
    public String sayHello() {
        return "Hello Spring";
    }
}

Explanation

@RestController: Marks the class as a REST controller, handling HTTP requests and returning data directly in the response body.
@GetMapping("/hello"): Maps HTTP GET requests to the /hello endpoint, invoking the sayHello method.

Application Properties File
The application.properties file (or application.yml) is used to configure Spring Boot applications. It allows customization of settings such as server port, database connections, and application behavior.
Example:
server.port=8080
spring.application.name=FirstSpringApp

Key Annotations

@PathVariable: Used in Spring MVC to extract template variables from the request URL and pass them as method parameters.

Example:
@GetMapping("/user/{id}")
public String getUser(@PathVariable Long id) {
    return "User ID: " + id;
}

