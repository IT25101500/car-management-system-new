# Car Service

Full-stack car service application.

## Tech Stack

- **Backend**: Spring Boot 3.4.3 (Java 17)
- **Database**: MongoDB Atlas
- **Frontend**: TBD

## Project Structure

```
carservice/
├── backend/      # Spring Boot REST API
├── frontend/     # Frontend (TBD)
└── README.md
```

## Getting Started

### Prerequisites

- Java 17+
- Maven 3.9+
- MongoDB Atlas account

### Backend

1. Update MongoDB Atlas connection string in `backend/src/main/resources/application.yml`
2. Run the application:

```bash
cd backend
./mvnw spring-boot:run
```

The API will be available at `http://localhost:8080`.
