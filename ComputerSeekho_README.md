# ComputerSeekho

A full-stack web-based system developed for a computer institute that conducts various computer courses for all age groups. The platform handles course management, student enrollments, batch scheduling, and administrative operations.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js |
| Backend (Java) | Spring 6, Spring Boot 3, Maven 3, JPA, REST API |
| Backend (.NET) | DotNet Web API Core, Entity Core |
| Database | MySQL 8, SQL Server |
| Auth | JWT (JSON Web Tokens) |
| DevOps | Docker |

## Features

- Course catalog with detailed descriptions and scheduling
- Student registration and enrollment management
- Batch management for organizing classes
- Admin dashboard for institute management
- JWT-based authentication and role-based access control
- RESTful APIs for seamless frontend-backend communication
- Dockerized deployment for consistent environments

## Getting Started

### Prerequisites

- Node.js (v16+)
- Java 17+
- .NET 6+
- MySQL 8
- Docker (optional)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Rajshingade7/ComputerSeekho.git
   cd ComputerSeekho
   ```

2. Set up the database and update connection strings in the configuration files.

3. Run the backend:
   ```bash
   # Java backend
   cd backend-java
   mvn spring-boot:run

   # .NET backend
   cd backend-dotnet
   dotnet run
   ```

4. Run the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

## Author

**Raj Shingade** — [GitHub](https://github.com/Rajshingade7)
