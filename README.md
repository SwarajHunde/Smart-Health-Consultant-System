# Smart Clinic Management System

This project focuses on building a robust, secure, and scalable **Smart Clinic Management System**. It encompasses both frontend (HTML, CSS, JavaScript) and backend (Java with Spring Boot) development, database design, API implementation, authentication, containerization, and continuous integration.

## Project Overview

The Smart Clinic Management System aims to transform outpatient clinic operations by providing an intuitive online portal for doctors and patients to manage schedules and health information seamlessly. It addresses the need for modern software solutions in small and mid-sized clinics that still rely on outdated tools for appointments, patient records, and administrative tasks.

## Key Features & Modules

### 1. Architecture Design
- **Three-Tier Web Architecture**: Separates the system into Presentation, Application, and Data layers.
- **Hybrid Data Storage**: Utilizes MySQL for relational data and MongoDB for flexible document-based data.
- **Backend Frameworks**: Leverages Spring MVC with Thymeleaf for admin/doctor dashboards and REST APIs for other modules.
- **Data Flow**: Traces the flow of data and control through controllers, services, and repositories.

### 2. User Stories
- **Administrators**: Manage system access and functionality.
- **Patients**: Book and manage appointments, view details.
- **Doctors**: Manage availability, appointments, and patient details.

### 3. Database Management
- **MySQL & MongoDB Initialization**
- **Schema Design** (SQL tables + MongoDB collections)
- **Data Insertion**
- **Stored Procedures** for automated reports

### 4. Backend Development (Spring Boot)
- **Model Building with Validations** (JPA, Hibernate, Spring Data MongoDB)
- **Data Integrity** using annotations
- **Service Layer** encapsulating business logic
- **REST Endpoints** with validation and error handling
- **MVC for Login** with JWT-based authentication

### 5. Frontend Development
- Structured files, responsive UI, reusable components
- Dynamic interactions with pure JavaScript
- Role-Based Login storing JWT in `localStorage`
- Dynamic data loading for dashboards

### 6. Containerization (Docker)
- Multi-stage Dockerfile
- Image building & execution
- Container registry push
- Docker Compose (optional)

### 7. Continuous Integration (GitHub Actions)
- Automated workflows for linting (HTML/CSS/JS, Java Checkstyle, Hadolint)
- Maven compilation
- Triggers on `push` and `pull_request`

## Technologies Used

- **Backend**: Java, Spring Boot, Spring Data JPA, Spring Data MongoDB
- **Databases**: MySQL, MongoDB
- **Frontend**: HTML, CSS, JavaScript, Thymeleaf
- **Containerization**: Docker, Docker Compose
- **CI/CD**: GitHub Actions, Maven, Checkstyle, Hadolint
- **Authentication**: JWT
- **Version Control**: Git, GitHub

## Setup and Installation

### 1. Clone the Repository
```bash
git clone https://github.com/SwarajHunde/Smart-Health-Consultant-System.git
cd Smart-Health-Consultant-System