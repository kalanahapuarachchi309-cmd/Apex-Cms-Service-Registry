# APEX-CMS: Netflix Eureka Service Registry

> **GitHub Repository About Description:**
> *Netflix Eureka Service Discovery Server for APEX-CMS, providing heartbeat monitoring, registration, and load balancing.*

---

## 👨‍🎓 Student & Submission Information

| Field | Details |
| :--- | :--- |
| **Student Name** | Kalana Maduranaga |
| **Student Number** | 241711018 |
| **GCP Project ID** | `apex-cms-506311` |
| **Service Name** | `service-registry` |
| **Default Port** | `9001` |

---

## 📖 Service Overview

The **Service Registry** is powered by **Spring Cloud Netflix Eureka Server**. It acts as the central directory for all active microservice instances across the cluster. Microservices register dynamically on startup with ephemeral ports and send periodic heartbeats.

### Registered Services
- `API-GATEWAY`
- `CUSTOMER-SERVICE`
- `VEHICLE-SERVICE`
- `ORDER-SERVICE`

---

## 🧰 Technology Stack

- **Java Version:** Java 25 / OpenJDK 21
- **Framework:** Spring Boot 4.1.0, Spring Cloud Netflix Eureka Server
- **Configuration:** Spring Cloud Config Client
- **Build System:** Apache Maven

---

## 🚀 Setup & Local Execution

```bash
mvn clean compile
mvn spring-boot:run
```
Open the Eureka Dashboard in your browser:
👉 [http://localhost:9001](http://localhost:9001)\n