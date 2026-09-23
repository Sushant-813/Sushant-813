# Hi there, I'm Sushant Sharma 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?size=24&duration=3500&color=3BA4F2&center=true&vCenter=true&width=600&lines=Java+Backend+Developer;Spring+Boot+Developer;Backend+Architecture+Enthusiast;Always+Learning+Something+New)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=Sushant-813&color=blue)

I'm a student and aspiring **Java Backend Developer** who enjoys building backend systems and understanding how real-world software is designed.

My primary focus is **Java, Spring Boot, backend architecture, databases, and software engineering fundamentals**. I prefer learning by building production-style projects that involve real engineering concepts such as authentication, transactional workflows, concurrency, event sourcing, double-entry accounting, auditability, and deterministic data reconstruction.

I'm also consistently practicing **Data Structures & Algorithms** in Java to strengthen my problem-solving skills.

---

## 🚀 What I'm Focused On

- ☕ Building backend applications with **Java & Spring Boot**
- 🏗️ Learning backend architecture and system design
- 🔐 Authentication & authorization with Spring Security and JWT
- 🗄️ Database design, SQL, and transaction management
- ⚡ Understanding concurrency and transactional workflows
- 🧩 Exploring Event Sourcing and domain-driven backend design
- 💻 Practicing Data Structures & Algorithms in Java
- 🧪 Writing maintainable code with comprehensive automated tests

---

## 🛠️ Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- REST APIs
- JWT Authentication
- Event Sourcing
- Double-Entry Ledger Architecture

### Databases

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

- MySQL
- PostgreSQL
- Relational Database Design
- Transactions & ACID
- Indexing
- Database Migrations with Flyway

### Tools & Technologies

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- Git & GitHub
- Maven
- Docker
- Postman
- IntelliJ IDEA
- VS Code

---

## 📚 Currently Learning

- Backend Architecture
- System Design Fundamentals
- Event-Driven & Event-Sourced Systems
- Authentication & Authorization
- Database Design & Optimization
- Concurrency & Transaction Management
- Clean Code & Software Engineering Practices
- Data Structures & Algorithms

---

## 📌 Featured Projects

### 🔗 URL Shortener Service

A production-style URL shortening service built with **Spring Boot, Spring Security, JWT, JPA/Hibernate, and MySQL**.

**Key Features**

- User authentication and authorization
- JWT-based security
- URL shortening
- Redirect handling
- Click tracking and analytics
- RESTful API design
- Persistent data storage with JPA/Hibernate

[![Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github)](https://github.com/Sushant-813/url-shortener-service)

---

### 💰 Event Sourced Ledger

A backend system implementing an **event-sourced, double-entry financial ledger** using Java and Spring Boot.

The project focuses on understanding how financial systems can derive account balances from an immutable history of events rather than storing mutable balances as the source of truth.

**Key Features**

- Event-sourced architecture
- Double-entry bookkeeping
- Account management
- Deposits, withdrawals, and transfers
- Immutable financial events
- Ledger entry generation
- Balance reconstruction from event history
- Historical balance reconstruction
- Transactional workflows
- Concurrency handling
- Deterministic event ordering
- Audit trail and historical queries
- Pagination
- Database indexing
- Flyway database migrations
- Comprehensive automated testing

**Architecture Concepts**

```text
                         ┌──────────────────┐
                         │     Command      │
                         └────────┬─────────┘
                                  │
                                  ▼
                    ┌──────────────────────────┐
                    │ Transaction / Operation  │
                    └────────────┬─────────────┘
                                 │
                    ┌────────────┴────────────┐
                    ▼                         ▼
           ┌─────────────────┐      ┌─────────────────┐
           │      Event      │      │  Ledger Entries │
           └────────┬────────┘      └────────┬────────┘
                    │                        │
                    └────────────┬───────────┘
                                 ▼
                    ┌──────────────────────────┐
                    │   Immutable History      │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │ Balance Reconstruction   │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │     Account Balance      │
                    └──────────────────────────┘
```

The project explores real backend engineering concerns including:

- **Transaction boundaries**
- **Consistency**
- **Concurrency**
- **Immutable history**
- **Auditability**
- **Historical reconstruction**
- **Deterministic state reconstruction**
- **Double-entry accounting**

[![Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github)](https://github.com/Sushant-813/event-sourced-ledger)

---

## 📊 Development Focus

```text
                         JAVA
                           │
                           ▼
                     SPRING BOOT
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
       REST APIs        SECURITY        PERSISTENCE
          │                │                │
          │                │                ▼
          │                │             DATABASES
          │                │                │
          │                │       ┌────────┴────────┐
          │                │       ▼                 ▼
          │                │      SQL            INDEXING
          │                │
          └────────────────┼────────────────┐
                           ▼                │
                   BACKEND ARCHITECTURE    │
                           │                │
              ┌────────────┼────────────┐   │
              ▼            ▼            ▼   │
        EVENT SOURCING  CONCURRENCY  SYSTEM DESIGN
              │            │            │
              └────────────┼────────────┘
                           ▼
                  SOFTWARE ENGINEERING
```

---

## 🎯 2026 Goals

- Build more production-style backend systems
- Strengthen Java and Spring Boot expertise
- Improve Data Structures & Algorithms problem solving
- Develop stronger system design fundamentals
- Learn more about distributed systems and scalable architectures
- Improve database design and performance optimization
- Continue writing maintainable, well-tested backend code

---

## 🤝 Connect With Me

<p align="left">
  <a href="https://github.com/Sushant-813">
    <img src="https://img.shields.io/badge/GitHub-Sushant--813-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
</p>

---

> *"Consistency beats intensity. Keep building, keep learning."*
