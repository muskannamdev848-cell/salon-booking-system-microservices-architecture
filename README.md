# 💇 Salon Booking System – Microservices Architecture

A web-based application designed to simplify salon appointment booking and service management using a microservices-based architecture.

## 📌 Project Overview

The Salon Booking System aims to make salon appointment management easier and more organized. It uses a microservices architecture to separate different business functionalities into independent services.

The project uses Java, Spring Boot, React.js, and MySQL to build a modular web application.

## 🎯 Objectives

- Simplify salon appointment booking and management.
- Organize salon details and service offerings.
- Develop REST APIs for application communication.
- Apply microservices architecture for modular development.
- Improve application maintainability and extensibility.

## ✨ Key Modules

- **User Service:** User-related operations.
- **Salon Service:** Salon information management.
- **Booking Service:** Appointment management.
- **Service Offering:** Salon service management.
- **Category Service:** Service categorization.
- **Payment Service:** Payment-related operations.
- **Review Service:** Customer reviews and feedback.
- **Notification Service:** Booking-related notifications.

## 🛠️ Technology Stack

**Backend**
- Java
- Spring Boot
- REST APIs
- Maven

**Frontend**
- React.js
- JavaScript
- HTML5
- CSS3

**Database and Infrastructure**
- MySQL
- Eureka Service Discovery
- API Gateway
- RabbitMQ
- Docker and Docker Compose

**Development Tools**
- IntelliJ IDEA
- Git and GitHub
- MySQL Workbench

*Note: Keep only those technologies and modules that are actually implemented in the repository.*

## 🏗️ System Architecture

The application follows a microservices-based architecture in which different services handle specific business responsibilities.

A typical request flow includes:

1. Users interact with the React.js frontend.
2. The frontend communicates with backend APIs.
3. The API Gateway routes requests to the appropriate services, if configured.
4. Backend services process business logic.
5. The configured database stores and retrieves application data.
6. Service discovery and asynchronous messaging support service communication where configured.

## ⚙️ Getting Started

### Prerequisites

- Java Development Kit (JDK)
- Maven
- Node.js and npm
- MySQL Server
- Git
- Docker Desktop, if required

### Clone the Repository

```bash
git clone https://github.com/muskannamdev848-cell/salon-booking-system-microservices-architecture.git
```

### Backend Setup

1. Open the project in IntelliJ IDEA.
2. Configure the database connection and required environment variables.
3. Start the required backend services using their Maven configurations.

Example:

```bash
mvn spring-boot:run
```

Run the command from the relevant service directory.

### Frontend Setup

Navigate to the frontend directory:

```bash
cd frontend
npm install
npm run dev
```

Use the actual frontend directory name if it differs from `frontend`.

### Verification

- Verify that the required backend services start successfully.
- Test REST API endpoints using Postman.
- Check frontend-to-backend integration.
- Test booking operations and database connectivity.

## 🔐 Security

Use appropriate authentication, authorization, input validation, and secure database credential management according to the project implementation.

## 🚀 Future Enhancements

- Online payment integration.
- Real-time appointment availability.
- Email and SMS notifications.
- Improved customer and salon dashboards.
- Booking analytics and reporting.
- Automated testing and deployment.

## 📚 Project Purpose

This project is developed as a major academic project to apply software engineering concepts, backend development, REST API design, database integration, and microservices architecture.
