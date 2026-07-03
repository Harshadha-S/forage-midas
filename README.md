# MIDAS – Banking Backend Simulation

A backend banking simulation built as part of the **JPMorgan Chase Advanced Software Engineering Virtual Experience** on Forage.

This project focuses on designing and implementing backend services commonly used in financial systems, including asynchronous message processing, transaction validation, database integration, and REST API communication.

---

## Overview

MIDAS simulates a financial transaction processing service capable of:

- Processing banking transactions asynchronously using Kafka
- Validating transactions before execution
- Persisting transaction records using an H2 in-memory database
- Updating user account balances
- Integrating with an external Incentive API
- Building enterprise backend services using Spring Boot

---

## Features

- Kafka-based transaction processing
- Spring Boot backend architecture
- H2 database integration
- Spring Data JPA
- REST API integration
- Transaction validation
- Automated testing
- Maven project structure

---

## Tech Stack

- Java 17
- Spring Boot
- Apache Kafka
- Spring Data JPA
- H2 Database
- Maven
- JUnit
- REST APIs

---

## Tasks Completed

### Task 1 – Project Setup

**What I did**
- Set up the Java 17 development environment.
- Configured the Spring Boot project using Maven.
- Added the required dependencies and verified the project setup by running the provided tests.

**What I learned**
This task helped me understand how enterprise Java projects are structured and how Spring Boot applications are configured before development begins.

---

### Task 2 – Kafka Integration

**What I did**
- Implemented a Kafka listener to consume transaction messages.
- Deserialized incoming messages into Java objects.
- Verified the integration using embedded Kafka tests.

**What I learned**
I learned how event-driven systems use message queues to process requests asynchronously and how different services can communicate without being tightly coupled.

---

### Task 3 – H2 Database Integration

**What I did**
- Integrated an H2 in-memory database using Spring Data JPA.
- Created entities to store transaction records.
- Implemented transaction validation and updated account balances after successful transactions.

**What I learned**
This task gave me practical experience with database persistence, entity relationships, and enforcing business rules before writing data to a database.

---

### Task 4 – REST API Integration

**What I did**
- Connected the application to an external Incentive API.
- Sent transaction data using REST requests.
- Processed incentive responses and updated recipient balances accordingly.

**What I learned**
I learned how backend services communicate through APIs, why service boundaries are important, and how external services can be integrated into an existing transaction workflow without changing the overall system design.

---

## Learning Outcomes

- Enterprise backend architecture
- Event-driven systems
- Message queues using Kafka
- Database modeling with JPA
- Financial transaction validation
- REST API consumption
- Spring Boot application development

---

## Acknowledgements

This project was completed as part of the **JPMorgan Chase Advanced Software Engineering Virtual Experience Program** hosted on **Forage**.

