# 🛒 Shopping Cart Management Service

A simple and efficient shopping cart management service built with modern technologies, focused on **performance**, **scalability**, and **clean architecture**.

This project demonstrates best practices in backend development using **Java**, **Spring Boot**, **Redis**, **MongoDB**, and **Docker**, following a clean and modular architecture.

---

## 📚 Table of Contents

* [About the Project](#about-the-project)
* [Main Goals](#main-goals)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Project Architecture](#project-architecture)
* [How to Run the Project](#how-to-run-the-project)
* [Screenshots](#screenshots)
* [Contributing](#contributing)
* [License](#license)

---

## 📖 About the Project

This project was developed as part of the **Java10x** program and aims to demonstrate the use of modern backend technologies to build a **scalable and efficient shopping cart system**.

The application integrates with an external product API, uses **Redis** for caching, **MongoDB** for data persistence, and follows clean architecture principles to ensure maintainability and scalability.

---

## 🎯 Main Goals

* Provide a smooth and efficient shopping cart experience
* Reduce external API calls using smart caching strategies
* Apply clean architecture and design best practices
* Demonstrate real-world backend development patterns
* Enable easy deployment using Docker

---

## 🛠 Technologies Used

### Core Stack

* **Java 17** – Modern LTS version with performance and language improvements
* **Spring Boot** – Application framework
* **MongoDB** – NoSQL database for persistent storage
* **Redis** – In-memory cache for fast access
* **OpenFeign** – Declarative HTTP client for external APIs

### DevOps & Tools

* **Docker & Docker Compose** – Containerized environment
* **Maven** – Dependency and build management

---

## ✨ Features

* 🛒 Product listing fetched from an external API
* 🧠 Smart caching using Redis to reduce API calls
* 🗄️ MongoDB persistence for shopping carts
* 🔌 External API integration using OpenFeign
* ⚡ High performance and scalable architecture
* 🧩 Clean and modular codebase

---

## 🧱 Project Architecture

```
controller/
 ├── CartController.java
service/
 ├── CartService.java
 ├── ProductService.java
repository/
 ├── CartRepository.java
client/
 ├── ProductClient.java
model/
 ├── Cart.java
 ├── Product.java
config/
 ├── RedisConfig.java
```

---

## 🚀 How to Run the Project

### ✅ Requirements

* Java 17+
* Docker (recommended)
* Maven (or Maven Wrapper)

---

### ▶️ Running with Docker (Recommended)

```bash
docker-compose up -d
```

This will start:

* Application
* Redis
* MongoDB

---

### ▶️ Running Locally (Without Docker)

1. Start **MongoDB** and **Redis**
2. Run the application:

```bash
./mvnw spring-boot:run
```

---

## 📸 Screenshots

> You can add screenshots of:

* API responses
* Swagger UI
* Application logs
* Architecture diagram

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for more details.

---

✨ **This project demonstrates clean code, good architectural decisions, and modern backend practices — ideal for showcasing in a professional portfolio.**


