# 🌍 RealWorld Spring Boot API — Clean Edition by Aziz

> A production-style backend application built with **Spring Boot + MyBatis**, based on the RealWorld spec — featuring REST + GraphQL, JWT Auth, DDD, CQRS, SQLite, and Docker.

---

## ✅ Features
- Full CRUD (Articles, Tags, Profiles)
- JWT Authentication
- REST and GraphQL APIs (Netflix DGS)
- SQLite DB (easy local testing)
- Domain Driven Design + CQRS
- Spring Security + Spotless Formatting
- Docker-ready

---

## 🏗️ Architecture
- `api`: Web layer (Spring MVC)
- `core`: Domain model + logic
- `application`: DTOs and queries
- `infrastructure`: DB, MyBatis, config

---

## 🚀 Getting Started

```bash
./gradlew bootRun
