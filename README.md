Backend (Java Spring Boot 3):
  •	Developed an ERP project using Java 17 and PostgreSQL based on a microservice architecture.
  •	Set up the Eureka Discovery Server for service discovery to enable microservices to locate and communicate with each other.
  •	Managed configuration files (.yml) centrally using Spring Cloud Config and accessed them via Git using an SSH key.
  •	Implemented Spring Cloud Gateway to manage incoming requests and ensure their security.
  •	Developed a middleware system using GlobalFilter to perform logging, JWT verification, and authorization checks before reaching the controller in each microservice.
  •	Developed a Security-Service to validate incoming requests through the gateway and implemented JWT token-based authentication for managing authorization and secure session handling.
  •	Designed a cardinality (Many-to-Many) relationship for User-Role-Permission management and assigned roles and special permissions to users.
  •	Hibernate and JPA were used for effective database access.
  •	Enabled communication between microservices via HTTP protocol using Feign Client annotation.
  •	Secured sensitive user information by implementing a JWT (JSON Web Token) structure.
  •	Build Docker images for each microservice and used Docker-Compose to set up containers, enabling a streamlined development environment to deploy necessary services with a single command
  •	Implemented Aspect Oriented Programming (AOP) for method-level logging, using pointcuts and join points to execute around, before, after, and throwing advice for enhanced monitoring and debugging.
  •	Utilized Log4j2 to maintain daily logs, ensuring detailed records of application behavior and error tracking for each log level. (ELK stack integration planned for future implementation
Frontend (React.js - PrimeReact):
  •	Developed the frontend infrastructure using React.js for a Single Page Application (SPA) architecture.
  •	Strengthened various React design patterns, including component structure, hooks, state management, and prop usage.

