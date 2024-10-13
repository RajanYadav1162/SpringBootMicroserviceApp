# RESTful Microservices with Spring Boot and Spring Cloud

## Key Features:
- Microservices Basics: Learn how to create and run RESTful Microservices from scratch.
- Microservices Architecture: Understand the concepts of Eureka Discovery Server, Zuul API Gateway, Spring Cloud Config Server, and Load Balancer.
- Microservices Communication: Explore the use of Spring Cloud Bus and RabbitMQ for inter-service communication.
- Microservices Monitoring: Learn how to use Spring Boot Actuator for monitoring and managing your Microservices.
- User Authentication and Authorization: Implement user authentication and authorization using Spring Security and JWT.
- Data Persistence: Use Spring Data JPA to store user details in a database, including H2 in-memory database and MySQL.
- Distributed Tracing: Trace HTTP requests with Spring Cloud Sleuth and Zipkin.
- Centralized Logging: Aggregate log files in one place using the ELK stack (Logstash, Elasticsearch, Kibana).
- Docker and AWS Deployment: Learn how to run Microservices in Docker containers on multiple EC2 Linux machines in the Amazon AWS Cloud.
## Project Structure

The project is organized into the following modules:

- Microservices: Contains the individual Microservices, such as the User Service, Product Service, and Order Service.
- Discovery Server: Implements the Eureka Discovery Server, both as a standalone server and a cluster.
- API Gateway: Provides the Zuul API Gateway and Spring Cloud API Gateway.
- Config Server: Hosts the centralized configuration for the Microservices.
- Monitoring: Includes the Spring Boot Actuator and the Distributed Tracing (Sleuth and Zipkin) components.
- Security: Handles user authentication and authorization using Spring Security and JWT.
- Persistence: Manages the data persistence layer using Spring Data JPA, H2, and MySQL.
- Logging: Implements the centralized logging solution using the ELK stack.
- Docker and AWS: Provides the necessary configurations and scripts for running the Microservices in Docker containers on AWS EC2 Linux machines.
