# Exam-mtgo

Team Members:
- Thomas - cph-ta181
- Markus - cph-ma587
- Rasmus - cph-rd92

## Table of Contents
- [Setup](#setup)
- [Microservices](#microservices)
- [Design](#design)
  - [User Stories](#user-stories)
  - [Use Case Diagram](#usecase-diagram)
  - [Domain Model](#domain-model)
  - [Subdomains](#subdomains)
  - [Architecture](#architecture)
  - [Other Diagrams](#other)
- [Legacy System](#legacy-system)
- [Pipeline](#pipeline)
  - [Dockerhub](#dockerhub)
- [Project Solution](#project-solution)

# Setup

1. Clone this project or download it as a zip and use it as the parent directory.

2. Clone the following projects into the parent directory.

3. Run the `docker-compose up -d` command from the parent directory.

# Microservices

- [Discovery Server](https://github.com/MRT-exam/exam-discovery-server)
- [API Gateway](https://github.com/MRT-exam/exam-api-gateway)
- [Order Service](https://github.com/MRT-exam/exam-order-service)
- [Restaurant Service](https://github.com/MRT-exam/exam-restaurant-service)
- [Delivery Service](https://github.com/MRT-exam/exam-delivery-service)
- [Notification Service](https://github.com/MRT-exam/exam-notification-service)

# Design

### User Stories  

### Use Case Diagram  

### Domain Model  
![Domain Model](DomainModel.png)
#### Subdomains
![Subdomains](Subdomains.png)
### Architecture  
![Architecture_Diagram](ArchitectureDiagram.png)
### Other Diagrams

# Legacy System

# Pipeline
#### Dockerhub: https://hub.docker.com/repositories/theagns

![Pipeline Screenshot](pipelines.png)

# Project Solution

