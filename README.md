# Magic Item E-Comerce
[RoadMap.sh](https://roadmap.sh/projects/scalable-ecommerce-platform)

## Core Microservices

Here are the core microservices implemented for the platform:

1. **User Service**  
   Handles all the wizards and mages registration, authentication, and profile management.

2. **Product Catalog Service**  
   Manages product listings, categories, and inventory.

3. **Shopping Cart Service**  
   Manages users’ shopping carts, including adding/removing items and updating quantities.

4. **Order Service**  
   Processes orders, including placing orders, tracking order status, and managing order history.

5. **Notification Service**  
   Sends email notifications for various events (e.g., order confirmation, shipping updates).  

---

## Additional Components

1. **API Gateway**  
   Acts as the entry point for all client requests, routing them to the appropriate microservice.  

2. **Service Discovery**  
   Automatically detects and manages service instances.  

3. **Centralized Logging**  
   Aggregates logs from all microservices for easy monitoring and debugging.  

4. **Docker & Docker Compose**  
   Each microservice is containerized for better orchestration, networking, and scaling.  

5. **CI/CD Pipeline**  
   Automates the build, test, and deployment process for each microservice.  

---

## Tech Stack

| Component               | Tool/Framework           |
|-------------------------|--------------------------|
| Language                | Java                    |
| Microservice Framework  | Spring Boot             |
| API Gateway             | Spring Cloud Gateway |
| Service Discovery       | Eureka          |
| Databases               | PostgreSQL, Redis |
| Containerization        | Docker, Docker Compose  |
| CI/CD                   | GitHub Actions  |
| Monitoring              | Prometheus, Grafana     |
| Logging                 | ELK Stack              |
| Notification Service    | Gmail       |


