# Seasonsforce

<div style="display:flex; flex-direction: row; justify-content: center; align-items: center; width: 100vw">
  <a target="_blank" href="https://github.com/lorenzo-italiano/Seasonsforce">
  <img alt="github link" src="https://img.shields.io/badge/SEASONFORCE-global-green?logo=github&style=for-the-badge">
</a>
<a target="_blank" href="https://github.com/lorenzo-italiano/seasonsforce-docs">
  <img alt="github link" src="https://img.shields.io/badge/SEASONFORCE-docs-blue?logo=github&style=for-the-badge">
</a>
<a target="_blank" href="https://github.com/lorenzo-italiano/seasonsforce-frontend">
  <img alt="github link" src="https://img.shields.io/badge/SEASONFORCE-frontend-blue?logo=github&style=for-the-badge">
</a>
<a target="_blank" href="https://github.com/lorenzo-italiano/seasonsforce-microservices">
  <img alt="github link" src="https://img.shields.io/badge/SEASONFORCE-microservices-blue?logo=github&style=for-the-badge">
</a>
</div>

---

## Context

This project is a school project for the 5th year of engineering school at [Polytech Montpellier](https://www.polytech.umontpellier.fr/). The purpose of the project was to introduce the concept of microservices and to implement a project with this principle. This project was made by a team of two people. It was made in 2 months out of the classroom.

## Project Summary: Seasonal Job Recruitment Application

The project aims to develop a comprehensive application for seasonal job recruiters and administrators. The application will include the following key features:

### Recruiter Management:

CRUD operations for recruiters with detailed information including personal details, establishment information, subscription plans (Platinum, Gold, Silver, Free), and subscription durations.
Admin notification and approval for recruiter account deletion.

### Job Offers Management:

CRUD operations for seasonal job offers, including employment details, periods, establishment association, salary, and benefits.
Ability for recruiters to manage multiple establishments.

### Candidate Matching:

Integration with an external service (API specified separately) for candidate matching.
Varying levels of candidate information access based on subscription plans.

### Communication and Recruitment:

- Validation of candidate selection for a job.

### Review and Rating:

- CRUD operations for reviews on candidates at the end of their assignments.



## Tech Stack

### Frontend:

- Developed in React Native using Expo.
- Global state management with React Context & TanStack Query.
- I18n Friendly (English & French).
- Testing on a preferred platform (iOS & Web).

### Backend:

- Microservices architecture with services for user management, job offers, references, reviews, availability, addresses, invoices, notifications, company, payment & experiences  in Spring Boot or Spring Webflux.
- API Gateway for backend accessibility (Spring Cloud Gateway).
- PostgreSQL or MongoDB databases for each microservice.
- Kafka message broker for some of the inter-microservice communication.
- Zookeeper for Kafka cluster management.
- Eureka for service discovery.
- Config Server for configuration management.
- Kotlin on one of the microservices.

### Security:

- Keycloak for authentication and authorization.
- Spring security for securing the microservices with Keycloak.

### Testing and Build:

- Spring Mock MVC for testing.
- Maven for build and dependency management.

### Version Control and Deployment:

- Git submodules for backend.
- Git flow.
- Containerization with Docker-compose.

### CI/CD:

- Implementation of CI/CD using GitHub Actions.

---

@ Romain Frezier & Lorenzo Italiano - IG5 Polytech Montpellier - 2023
