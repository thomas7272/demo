# Spring Boot User Registration API

## Requirements
- Java 17+
- Maven

## Running the Application
1. Clone the repository
2. Navigate to the project directory
3. Run `mvn spring-boot:run`

## API Endpoints

### Register User
`POST /api/user/register`
- Request Body: 
  ```json
  {
    "username": "john_doe",
    "email": "john@example.com",
    "password": "password123"
  }
