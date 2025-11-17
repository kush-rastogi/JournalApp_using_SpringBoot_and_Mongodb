📝 **JournalApp — Spring Boot + MongoDB**

JournalApp is a backend application built using Spring Boot, MongoDB Atlas, JWT Authentication, Redis, and Kafka.
It follows a clean layered architecture and includes secure user authentication along with full CRUD operations for journal entries.

🚀 **Tech Stack**

Java 17

Spring Boot

MongoDB Atlas

JWT Authentication

Redis Cache

Kafka Messaging

Maven

📌 **Features**

JWT-based registration & login

CRUD APIs for journal entries

Clean Controller → Service → Repository structure

Redis integration for faster token validation

Kafka events for user activity

Swagger API documentation

🛠 **Setup**

Clone the repository

Add your MongoDB URI in application.yml

Configure Redis (optional)

Configure Kafka (optional)

Run the application using:

mvn spring-boot:run

📁 **API Endpoints**

POST /auth/register

POST /auth/login

GET /journal

POST /journal

PUT /journal/{id}

DELETE /journal/{id}

📈 **Highlights**

Secure authentication flow

Cloud-hosted MongoDB

Modular & scalable backend design

Real-world debugging & integration experience
