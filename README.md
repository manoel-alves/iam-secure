# 🔐 IAM Secure
*An Identity & Access Management (IAM) system that provides a security infrastructure for authentication services.*

---

## 📝 Description
**IAM Secure** is a scalable and secure **Identity and Access Management (IAM)** system designed to handle authentication, authorization, and user management in distributed systems.

_Built with_ **Spring Boot**, it leverages **PostgreSQL** for relational data, **MongoDB** for flexible document storage, and **RabbitMQ** for asynchronous communication.

The system is built with microservices architecture, enabling modular development, independent scaling, and easy integration with other systems. 

### Key Features:
- 🔐 **Authentication & Authorization** — Secure login, role-based access control, and token management.
- 📡 **Asynchronous Messaging** — Event-driven communication via RabbitMQ.
- 🗄️ **Polyglot Persistence** — Relational and NoSQL databases for optimized data storage.
- 📊 **Observability** — Health checks, metrics, and structured logging for production readiness.
- ⚙️ **Extensible Architecture** — Easily integrates with external identity providers and services.

---

## 🗃️ Table of Contents
* [📝 Description](#-description)
* [⚙️ Services](#-services)
* [🛠️ Tech Stack](#-tech-stack)
* [©️ License](#-license)

---

## ⚙️ Services

### 📋 Planned:
|        Service         |         Components          |                             Description                              |
|:----------------------:|:---------------------------:|:--------------------------------------------------------------------:|
|  _discovery-service_   |        Eureka Server        |         Central service registry for locating microservices          |
|    _config-service_    |     Spring Cloud Config     |        Centralized configuration management for all services         |
|   _gateway-service_    |    Spring Cloud Gateway     |      API Gateway for routing, load balancing, and edge security      |
|    _audit-service_     |      RabbitMQ, MongoDB      |                         Security audit logs                          |
| _notification-service_ |     RabbitMQ, Mail/SMS      |                        Notifications & events                        |
|     _auth-service_     | Spring Security, JWT/OAuth2 | Authentication & authorization service (token issuance, login, RBAC) |
|     _user-service_     | Spring Data JPA, PostgreSQL |              User management (CRUD, roles, credentials)              |
|   _profile-service_    |     Spring Data MongoDB     |                   Profile and preferences storage                    |

---

## 🛠️ Tech Stack

### Languages & Frameworks:
|     **Component**     | **Version** |
|:---------------------:|:-----------:|
|         Java          |     21      |
|      Spring Boot      |    3.5.6    |
|     Spring Cloud      |  2025.0.0   |
|        Lombok         |   1.18.42   |

### Build & Dependency Management:
| **Component** | **Version** |
|:-------------:|:-----------:|
|     Maven     |    3.9+     |

### Testing Tools:
|    Library     | Version |
|:--------------:|:-------:|
|     JUnit      | 5.12.2  |
|    Mockito     | 5.17.0  |
| Testcontainers | 1.21.3  |
|     JaCoCo     | 0.8.13  |

### API Documentation:    
|     Component     | Version |
|:-----------------:|:-------:|
| Springdoc OpenAPI |  2.6.0  |

### Observability & Logging:
|             Component             | Version |
|:---------------------------------:|:-------:|
| Spring Boot Actuator / Micrometer |  3.5.5  |

---

## ©️ License
This project is licensed under the terms of the [GNU General Public License v3.0](LICENSE).

**IAM Secure**  
Copyright (C) 2025 Manoel Alves

