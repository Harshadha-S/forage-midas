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

### Task 1 — Project Setup

- Configured Java 17 development environment
- Set up Spring Boot project
- Installed required dependencies
- Verified project using automated tests

---

### Task 2 — Kafka Integration

Implemented a Kafka consumer that:

- Listens to transaction events
- Deserializes incoming transaction messages
- Integrates with the existing Spring Boot application
- Verified functionality using embedded Kafka tests

---

### Task 3 — Database Integration

Integrated H2 with Spring Data JPA by:

- Creating transaction entities
- Validating financial transactions
- Updating sender and recipient balances
- Persisting successful transactions
- Rejecting invalid transactions

---

### Task 4 — REST API Integration

Connected the application to an external Incentive API by:

- Sending transaction data using REST
- Receiving incentive responses
- Applying incentives to recipient accounts
- Updating transaction records accordingly

---

## Learning Outcomes

Through this project, I gained practical experience with:

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

