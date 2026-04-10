# User Service

User management service for the ecommerce platform.

## Port
- **8081**

## Description
Handles user registration, authentication, and profile management.

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/users/register | Register new user |
| POST | /api/users/login | User login |
| GET | /api/users | Get all users |
| GET | /api/users/{id} | Get user by ID |
| GET | /api/users/username/{username} | Get user by username |
| PUT | /api/users/{id} | Update user |
| DELETE | /api/users/{id} | Delete user |

## Running the Service

```bash
mvn spring-boot:run
```

## Dependencies
- MySQL Database: `ecommerce_user`
- Eureka Server: http://localhost:8761
