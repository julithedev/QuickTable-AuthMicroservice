# Authentication Service

The Authentication Service is a microservice responsible for handling user authentication and authorization. It ensures secure user registration and login, token-based authentication, and protection against brute-force attacks. This service is built using Python with the FastAPI framework for high performance and scalability.

## Key Features

### User Authentication & Authorization:
- User registration and login for both customers and employees.
- Secure password hashing with bcrypt.
- JWT-based authentication for session management.

### Security & Rate Limiting:
- Implements rate limiting to prevent brute-force attacks.
- Token validation endpoint to verify user sessions.

## Tech Stack

- **Language**: Python
- **Framework**: FastAPI (Fast and asynchronous web framework)
- **Database**: PostgreSQL (via SQLAlchemy for ORM)
- **Security**: bcrypt for password hashing
- **Rate Limiting**: slowapi or custom middleware

## Endpoints

### REST API

- **POST /register** – Register a new user.
- **POST /login** – Authenticate and obtain a JWT token.
- **GET /validate-token** – Validate an existing JWT token.

![image](https://github.com/user-attachments/assets/24e87744-74ef-4741-a54d-3dfca787bcaa)
