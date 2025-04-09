# SheHub

**Empowering women through tech, community, and growth.**

Welcome to the SheHub backend project — the Spring Boot-powered heart of the SheHub platform.

🌐 [Visit our teaser page](http://www.shehub.es)

---

## 🚀 Project Overview

SheHub is a digital platform designed to connect, inspire, and support women in their personal and professional journeys. This repository contains the backend code for SheHub, built using **Java**, **Spring Boot**, and **PostgreSQL**.

> **⚠️ Status:** _Project is in early development stage._

---

## 📦 Tech Stack

- **Java 17**
- **Spring Boot 3**
- **Spring Security (JWT)**
- **Spring Data JPA**
- **PostgreSQL**
- **Dotenv for environment config**
- **Lombok for boilerplate reduction**

---

## 📁 Project Structure (Planned)

``bash
shehub/
├── src/
│   ├── main/
│   │   ├── java/com/shehub/...
│   │   └── resources/
│   └── test/
├── pom.xml
└── README.md

---

## 🔒 Authentication
Authentication is handled using JWT tokens, managed securely through HTTP-only cookies. This approach ensures better protection against XSS attacks while maintaining a stateless backend.

Users will be able to register, log in, and access protected endpoints based on their roles.

Tokens are sent as secure HTTP-only cookies (not accessible via JavaScript).

Spring Security is configured to validate and refresh tokens as needed.

---

## 📌 Goals & Milestones
- Set up base project structure
- Define and implement core entities
- Create user authentication system (JWT)
- Connect to extern PostgreSQL database
- Deploy first working backend API
- Continue developing core and additional features

---

## 🧑‍💻 Contributing
This project is currently under internal development. If you're interested in collaborating, stay tuned — we’ll open up contributions as soon as the foundation is laid.

---

## 📄 License
TBD — this project currently does not have an open-source license applied.

---

## 💌 Contact
If you'd like to get in touch or follow along with the progress:

🌍 Website: www.shehub.es

📧 Email: [info@shehub.es]

🐙 GitHub: [(https://github.com/SheHub-es)] 


