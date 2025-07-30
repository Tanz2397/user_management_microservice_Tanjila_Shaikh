# user_management_microservice_Tanjila_Shaikh

A simple User Management Microservice built with **Spring Boot**, featuring:
- User registration and login
- JWT-based authentication
- Role-based authorization (ROLE_USER, ROLE_ADMIN)
- Global exception handling

---

##Features
Register new users (`/register`)  
Login and get JWT token (`/login`)  
View users (Admin only)  
View user by ID (Admin or User)  
Delete user by ID (Admin only)

---

##Tech Stack
- Java 17
- Spring Boot
- Spring Security
- JSON Web Token (JWT)
- Spring Data JPA
- H2 Database
- Maven
- Lombok

---

##How to Run

```bash
git clone https://github.com/yourusername/user-management-service.git
cd user-management-service
mvn clean install
mvn spring-boot:run
