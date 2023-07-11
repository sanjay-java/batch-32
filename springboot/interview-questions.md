#### What do you know about RESTful Web Services?
  - REST stands for Representational State Transfer. REST is defined as the stateless client-server architectural style for developing applications accessed over the web.
  - When web services use HTTP methods to implement the concept of REST architecture, then it is known as RESTful Web services. In this architectural style, data and functionality are served as resources and are accessed by URI (Uniform Resource Identifiers).

#### Explain the advantages of RESTful web services?
  - Enlisted below are the advantages of RESTful web services:
    They are considered as language and platform-independent as these can be written in any programming language and can be executed on any platform. REST is a lightweight protocol and is considered as fast because of less consumption of bandwidth and resources.  It supports multiple technologies and different data formats like plain text, XML, JSON, etc. It has loosely coupled implementation and can be tested easily over browsers.

#### Explain different HTTP methods supported by RESTful web services?

  - Enlisted below are some common HTTP methods along with their functions that are supported by RESTful web services
    GET: Read-only access to the resource.
    PUT: Creation of new resources.
    DELETE: Removal of a resource.
    POST: Update of an existing resource.
    OPTIONS: Get supported operations on the resource.
    HEAD: Returns HTTP header only, nobody.

#### What is a resource in RESTful web service and how it is represented?

    - Resource is said to be a fundamental concept having a type and relationship with other resources. In REST architecture, each content is considered as the resource and they are identified by their URIs. Resources are represented with the help of XML, JSON, text, etc in RESTful architecture.

#### What are the core components of the HTTP request and HTTP response?

  HTTP request has following 5 major components:

  - Verb:	Indicate HTTP methods like GET, PUT, POST, etc
  - URI:	Identifies the resource on server
  - HTTP: Version	Indicates version.
  - Request Header	Contains metadata like client type, cache settings, message body format, etc for HTTP request message.
  - Request Body	Represents content of the message.

#### HTTP response has following 4 major components:

  - Status/Response code	Indicates the status of the server for requested resource.
  - HTTP version	Represents HTTP version.
  - Response Header	Consists of metadata like content length, content type, server length, etc for HTTP response message.
  - Response Body	Represents response message content.

#### What is Spring Boot?
    Spring Boot is an opinionated framework built on top of the Spring framework that aims to simplify the development of Java applications. It provides a convention-over-configuration approach, along with auto-configuration and starter dependencies, to streamline the setup and deployment of Spring-based applications.

#### How is Spring Boot different from the Spring framework?
    While the Spring framework provides various modules and libraries for building enterprise Java applications, Spring Boot focuses on simplifying the setup and configuration of these applications. Spring Boot eliminates much of the manual configuration required in traditional Spring applications by providing sensible defaults and automatic configuration based on classpath dependencies.

#### What are the advantages of using Spring Boot?
    Some advantages of using Spring Boot are:

    - Simplified configuration: Spring Boot reduces boilerplate code and provides default configurations, making it easier to set up and start a project.
    - Rapid development: It enables quick application prototyping and development by minimizing manual configuration.
    - Auto-configuration: Spring Boot automatically configures components based on the classpath, saving developers from writing explicit configuration code.
    - Embedded servers: It provides support for embedding servers like Tomcat or Jetty, allowing applications to be run as standalone JAR files.
    - Actuator: Spring Boot Actuator offers production-ready features, such as health checks, monitoring, and metrics, out of the box.

#### How does Spring Boot simplify the development of Java applications?
    - Spring Boot simplifies Java application development by providing:
    - Opinionated defaults: It uses sensible defaults for configuration and eliminates the need for explicit XML configuration.
    - Auto-configuration: Spring Boot automatically configures components based on dependencies, reducing the need for manual configuration.
    - Starter dependencies: It offers a wide range of pre-configured dependencies (starters) for common use cases, which can be easily included in projects.
    - Embedded servers: Spring Boot allows applications to be packaged as standalone JAR files with embedded servers, simplifying deployment.
#### How do you configure Spring Boot to start a web application?
    To configure Spring Boot for a web application, you need to:
    - Include the spring-boot-starter-web dependency in your project.
    - Create a class annotated with @SpringBootApplication to serve as the application's entry point.
    - Define your web-related components (controllers, services, etc.) within the application or in separate packages.

#### What is the purpose of the @SpringBootApplication annotation?
    The @SpringBootApplication annotation combines three commonly used Spring annotations: @Configuration, @EnableAutoConfiguration, and @ComponentScan. It marks a class as the entry point for Spring Boot applications and enables auto-configuration and component scanning.

#### How does Spring Boot handle dependency management?
    Spring Boot uses dependency management through its starter dependencies. Starter dependencies are curated collections of commonly used libraries for specific use cases, such as web applications, database access, testing, etc. By including a starter dependency, Spring Boot automatically manages the versions and configurations of the associated libraries, reducing the effort required for dependency management.

#### Explain the concept of "auto-configuration" in Spring Boot.
    Auto-configuration in Spring Boot automatically configures the Spring application based on the classpath dependencies and the beans defined in the application context. It leverages the @Conditional annotation to conditionally enable configuration if certain classes or conditions are present. Auto-configuration simplifies the setup by providing sensible defaults and reducing the amount of explicit configuration required.

#### How can you override the default configuration in Spring Boot?
    To override default configuration in Spring Boot, you can:

    Provide your own configuration by defining beans in the application context.
    Use properties or YAML files to override specific configuration properties.
    Exclude specific auto-configurations using the @EnableAutoConfiguration(exclude = ...) annotation.
    What is the role of the application.properties (or application.yml) file in Spring Boot?
    The application.properties (or application.yml) file is used to provide configuration properties for a Spring Boot application. It allows developers to customize various aspects of the application, such as server port, database configuration, logging, and more. Spring Boot automatically reads these files and applies the specified configuration during application startup.

#### What Basic Annotations Does Spring Boot Offer?
    The primary annotations that Spring Boot offers reside in its org.springframework.boot.autoconfigure and its sub-packages.
    Here are a couple of basic ones:
    @EnableAutoConfiguration – to make Spring Boot look for auto-configuration beans on its classpath and automatically apply them
    @SpringBootApplication – to denote the main class of a Boot Application. This annotation combines @Configuration @EnableAutoConfiguration  and @ComponentSca annotations with their default attributes.

#### What are Microservices
    Microservices is a variant of the service-oriented architecture (SOA) architectural style that structures an application as a collection of loosely coupled services. In a microservices architecture, services should be fine-grained and the protocols should be lightweight. The benefit of decomposing an application into different smaller services is that it improves modularity and makes the application easier to understand, develop and test. It also parallelizes development by enabling small autonomous teams to develop, deploy and scale their respective services independently. It also allows the architecture of an individual service to emerge through continuous refactoring. Microservices-based architectures enable continuous delivery and deployment.
