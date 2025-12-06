A simple and efficient shopping cart management service built with modern technologies to ensure high performance, scalability, and clean architecture.

🔗 Table of Contents

About the Project

Technologies Used

Java 17

Lombok

Redis

MongoDB

OpenFeign

Docker

External API

Features

Screenshots

How to Run the Project

Contributing

License

📖 About the Project

This project was developed as part of the Spring Boot module in the Java10x program.
It is a shopping cart management service that integrates with an external API to provide a list of products.
The architecture leverages Redis for caching, MongoDB for NoSQL persistence, and Docker for containerized deployment, ensuring performance, scalability, and maintainability.

🎯 Main Goals

Provide a smooth and efficient shopping cart experience.

Reduce unnecessary calls to the external product API using smart caching.

Offer simple and scalable deployment using Docker containers.

Demonstrate clean architecture and modern Java practices.

🛠 Technologies Used
Java 17

Modern LTS version of Java, featuring improved performance, stability, and language enhancements.

Documentation: https://openjdk.org/projects/jdk/17/

Lombok

Reduces boilerplate code by auto-generating getters, setters, constructors, and more.

Documentation: https://projectlombok.org/

Redis

In-memory key-value store used as a caching layer to improve API response time and reduce external requests.

Documentation: https://redis.io/docs/

MongoDB

NoSQL database used to persist shopping cart data with flexibility and scalability.

Documentation: https://www.mongodb.com/docs/

OpenFeign

A declarative HTTP client that simplifies communication with external APIs and minimizes boilerplate.

Documentation: https://github.com/OpenFeign/feign

Docker

Provides isolated and reproducible environments for running Redis, MongoDB, and the application itself.

Documentation: https://docs.docker.com/

Course reference: https://aluno.java10x.dev/209723-docker

External API

The project integrates with an external API to retrieve available products for the cart.

Learn more about working with APIs: https://www.postman.com/api-documentation/

✨ Features

Product Listing — Display all products retrieved from an external API.

Cart Management — Create, update, pay for, and delete shopping carts.

Smart Caching with Redis — Avoid redundant API calls by caching product data.

MongoDB Persistence — Stores cart data securely and efficiently.

External API Integration — Fetch dynamic product information in real time.

Docker Support — Run the entire stack using containerized services.

📸 Screenshots
🛒 Shopping Cart UI

🧱 Project Architecture

🚀 How to Run the Project
📌 Requirements

Java 17

Docker (recommended)
or
Local installations of Redis and MongoDB

Maven or mvnw wrapper

▶️ Running with Docker Compose
docker-compose up -d

▶️ Running Locally (without Docker)

Start Redis and MongoDB manually.

Run the application:

./mvnw spring-boot:run

🤝 Contributing

Contributions are welcome!
Feel free to fork the project, submit issues, or open pull requests.

📄 License

This project is licensed under the MIT License.
See the LICENSE file for more details.

