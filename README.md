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
   *Tools*: Gmail limited to 100 emails a day.

---

## Additional Components

1. **API Gateway**  
   Acts as the entry point for all client requests, routing them to the appropriate microservice.  
   *Examples*: Kong, Traefik, or NGINX.

2. **Service Discovery**  
   Automatically detects and manages service instances.  
   *Examples*: Consul or Eureka.

3. **Centralized Logging**  
   Aggregates logs from all microservices for easy monitoring and debugging.  
   *Tools*: ELK stack (Elasticsearch, Logstash, Kibana).

4. **Docker & Docker Compose**  
   Each microservice is containerized for better orchestration, networking, and scaling.  
   *Tools*: Docker Compose can define and manage multi-container applications.

5. **CI/CD Pipeline**  
   Automates the build, test, and deployment process for each microservice.  
   *Examples*: GitHub Actions.

