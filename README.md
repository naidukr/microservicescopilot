# microservicescopilot
Service Discovery → Use Spring Cloud Netflix Eureka.
Cloud Config → Use Spring Cloud Config Server.
Fallback Mechanism → Use Resilience4j Circuit Breaker.
Application Monitoring → Use Micrometer & Prometheus.
API Documentation → Use Springdoc OpenAPI (Swagger).

// Create a Spring Boot REST API that registers with Eureka Server
// - Use @EnableDiscoveryClient to enable service discovery
// - Expose a sample "/hello" endpoint returning "Hello from Microservice"
// - Use Spring Web for RESTful API


// Configure this service to fetch configurations from Spring Cloud Config Server
// - Use @RefreshScope to allow runtime refresh of properties
// - Read "message" property from config server and expose via an endpoint

// Implement Circuit Breaker for API calls using Resilience4j
// - Use @CircuitBreaker(name = "defaultService", fallbackMethod = "fallbackMethod")
// - Define a fallbackMethod to return a default response in case of failures
