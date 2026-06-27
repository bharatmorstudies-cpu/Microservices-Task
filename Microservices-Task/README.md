# Microservices Application Containerization

## Setup Instructions
1. Navigate to the root directory where `docker-compose.yml` is located.
2. Build and start all microservices locally:
   ```bash
   docker-compose up --build -d
   ```
3. Verify that all 4 containers are online and active:
   ```bash
   docker compose ps
   ```

## Local Port Accessibility
* **User Service**: http://localhost:3000
* **Product Service**: http://localhost:3001
* **Order Service**: http://localhost:3002
* **Gateway Service**: http://localhost:3003
