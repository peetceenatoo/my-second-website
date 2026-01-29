# CodeKataBattle

## Description 

This repository contains the deliverables and a prototype implementation for an online coding battles platform. The work focuses on the full lifecycle: **requirements elicitation and specification**, **architectural/design decisions**, and a **demo-oriented implementation** that prioritizes adherence to the designed architecture and requirements over UI polish. **CodeKataBattle (CKB)** is a platform that helps students improve their software development skills by training with peers on *code katas*. Educators create **tournaments** composed of **battles**, where teams of students compete by submitting solutions that are automatically evaluated and scored.

## Documentation Provided

The repository includes deliverables for the main project documents:
- **RASD** — Requirements Analysis and Specification Document (`RASD/`, `RASD_latex/`)
- **DD** — Design Document (`DD/`, `DD_latex/`)
- **ITD** — Implementation and Testing Document (`ITD/`)
- **ATD** — Acceptance Test Deliverable (provided by another group) (`ATD/`)

## Architecture and Main Features

- **Three-tier architecture**
  - **Frontend:** React single-page application served as static assets via Nginx
  - **Backend:** Spring Boot application exposing RESTful, stateless APIs
  - **Data layer:** relational database accessed via JPA Hibernate hosted on cloud
- **Distributed MVC**
- **Security:** JWT-based authentication and authorization, consistent with stateless REST
- **Scheduling:** deadlines managed via Spring Task Scheduler
- **GitHub integration:** interaction with GitHub Actions workflows
- **E-mail verification:** implemented through Jakarta Mail

## Technology Stack

- **Java SE 21**
- **Spring Boot 3.2.1**: Backend.
- **React** and **Nginx**: Frontend.
- **JPA Hibernate**: Data layer.
- **JWT**: Security.
- **JUnit 5** and **Postman**: Testing.
- **Apache Maven**: Build automation and dependency management.
- **DigitalOcean**: Deployment.
- **LaTeX**: Documentation.

## Acknowledgments

I thank my colleagues and friends [Jacopo Piazzalunga](https://github.com/Jacopopiazza) and [Gabriele Puglisi](https://github.com/GabP404) who worked with me on this project.
