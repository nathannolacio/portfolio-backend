# Portfolio Backend

Backend application for my personal developer portfolio.

The project aims to provide a custom CMS experience for managing portfolio content dynamically, while also handling communication features such as the contact email service.

Built to practice modular architecture, scalability, security, and real-world backend concepts.

---

## 🚀 Technologies

- Java
- Spring Boot
- Spring Security
- JWT Authentication
- PostgreSQL
- Docker
- Maven

---

## ✨ Features

### Current Features
- Contact email service
- RESTful API structure
- Environment-based configuration
- Dockerized setup

### Planned Features
- JWT authentication and authorization
- CMS dashboard
- Portfolio project management
- Portfolio content management

---

## 🧠 Project Goals

This project was created to:

- Practice backend architecture and best practices
- Build a real-world CMS-style application
- Improve knowledge of authentication and security
- Integrate email communication workflows
- Create a scalable backend for future portfolio expansions

---

## 🏗️ Architecture

The project follows a **modular monolith architecture**, organizing the application by business domains instead of only technical layers.

Each module is developed independently while remaining part of the same Spring Boot application.

Example structure:

```txt
src/main/java/com/yourname/portfolio
│
├── common
│   ├── config
│   ├── security
│   ├── exceptions
│   └── utils
│
├── modules
│   │
│   ├── email
│   ├── auth
│   └── cms
│
└── PortfolioApplication.java
```

This architecture improves:

- scalability
- maintainability
- feature isolation
- code organization
- long-term project evolution

---

## 📂 Main Modules

### Email Module
Responsible for handling:

- contact form submissions
- email delivery
- validation

### Authentication Module
Responsible for:

- JWT authentication
- admin authorization
- route protection

### CMS Module
Responsible for managing portfolio content dynamically.

Features include:

- project management
- technology management
- content editing

---

## 🔐 Security

Implemented and planned security features include:

- JWT-based authentication
- protected admin routes
- password encryption
- request validation
- environment variable protection
- rate limiting for contact requests

---

## ⚙️ Running the Project

```bash
# Clone the repository
git clone https://github.com/nathannolacio/portofolio-backend.git

# Navigate to the project
cd portfolio-backend

# Run with Docker
docker compose up

# Or run locally
./mvnw spring-boot:run
```

---

## 🚧 Project Status

Currently in planning and initial development phase.

---

## 📫 Contact

If you'd like to connect or discuss opportunities, feel free to reach out through the portfolio contact section.
