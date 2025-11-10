---

A hands-on collection of **resources, examples, and documentation** designed to help you understand and master **Spring Boot** and its ecosystem — including **Spring Data JPA**, **Spring Security (JWT & OAuth2)**, **Caching**, and more.

---

## 🎯 Overview  

This repository acts as a **comprehensive learning guide** for building modern backend applications using **Spring Boot**.  
It combines **theoretical concepts**, **code examples**, and **ready-to-run mini projects** that demonstrate how everything works together.

### 🧠 You’ll Learn:
- ✅ Internal working of **Spring Boot**  
- ✅ CRUD, pagination & query methods using **Spring Data JPA**  
- ✅ **JWT Authentication** and **OAuth2 Login** (Google, GitHub)  
- ✅ **Role-Based Access Control (RBAC)** and password hashing with BCrypt  
- ✅ **Caching** using Spring Cache abstraction and Redis  
- ✅ Real-world integration of all these concepts  

---

## 📂 Repository Contents  

| Section | Description |
|----------|-------------|
| 🧩 **Spring Boot Internals** | Learn auto-configuration, dependency injection, and context initialization. |
| 🧠 **Spring Data JPA** | Entity mapping, relationships, JPQL, and native queries. |
| 🔐 **Spring Security** | JWT, OAuth2 (Google/GitHub), and RBAC with BCrypt hashing. |
| ⚡ **Caching** | Spring cache abstraction, Redis setup, and performance tuning. |
| 📘 **Docs & Guides** | PDFs/DOCX explaining each concept with diagrams and examples. |
| 🧪 **Sample Projects** | Ready-to-run code samples for practice. |

---

## 🏗️ Project Structure  

A typical Spring Boot module in this repo follows this structure 👇

```

GettingStartingWithSpringBoot/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           ├── controller/        # REST Controllers (APIs)
│   │   │           ├── service/           # Business logic layer
│   │   │           ├── repository/        # Spring Data JPA repositories
│   │   │           ├── model/             # Entity classes
│   │   │           └── config/            # Security & application configuration
│   │   └── resources/
│   │       ├── application.yml            # Application configuration
│   │       ├── static/                    # Static web resources (if any)
│   │       └── templates/                 # Thymeleaf templates (if used)
│   │
│   └── test/                              # Unit & Integration Tests
│
├── pom.xml                                # Maven dependencies
├── README.md                              # Project documentation (this file)
└── docs/                                  # Guides, PDFs, Notes, and Zipped Examples

````

---

## 🧰 Getting Started  

1. **Clone the repository**
   ```bash
   git clone https://github.com/RohitJoshi10/GettingStartingWithSpringBoot.git
````

2. **Open in your IDE**
   Recommended: *IntelliJ IDEA* or *Eclipse*.
3. **Configure your setup**

   * Update database credentials in `application.yml`
   * Add your OAuth2 Client IDs (for Google/GitHub)
4. **Run the application**

   ```bash
   mvn spring-boot:run
   ```
5. **Explore and experiment!**
   Review controllers, services, and configuration files to understand the flow.

---

## 🧭 Recommended Learning Path

1. **Step 1:**
   Learn *Spring Boot Internals* — Understand auto-configuration, starters, and lifecycle.

2. **Step 2:**
   Move to *Spring Data JPA* — Build CRUD APIs, explore repositories & custom queries.

3. **Step 3:**
   Explore *Caching* — Apply caching and test its performance impact.

4. **Step 4:**
   Dive into *Spring Security* — Implement JWT Authentication and OAuth2 login.

5. **Step 5 (Advanced):**
   Combine all features to build a complete, production-style REST API.

---

## 🧩 Key Topics Covered

* 🌱 Spring Boot Project Setup
* ⚙️ Dependency Injection & Auto-Configuration
* 💾 JPA Entities, Relationships, Query Methods
* 🔐 JWT Authentication Flow
* 🔑 OAuth2 Login with Google & GitHub
* 🧱 Role-Based Access Control (RBAC)
* 💬 Global Exception Handling & Validation
* ⚡ Caching with `@Cacheable`, `@CacheEvict`, `@CachePut`
* 🧠 Spring Boot Interview Prep Notes

---

## 🤝 Contributing

Contributions are always welcome! 💡
You can:

* Add new examples or features (WebSockets, Kafka, RabbitMQ, Cloud Gateway, etc.)
* Fix or improve documentation
* Suggest or create learning modules
* Fork ⭐ and share with others to grow the community

---

## 📜 License

This repository is **open-source** and free for **learning and educational purposes**.
If you use or modify any content, please link back to this repository.

---

## 👨‍💻 Author

**Rohit Joshi**
Software Developer | Payments Team | Passionate about Spring Boot & System Design

> *“Learn by building. Understand by breaking. Master by sharing.”*

---

## 🌐 Connect With Me

* 🔗 **GitHub:** [@RohitJoshi10](https://github.com/RohitJoshi10)
* 💼 **LinkedIn:** *http://www.linkedin.com/in/rohitjoshi1110*
* 🧠 **Topics:** Spring Boot, JPA, Security, JWT, OAuth2, Caching, Docker, Kubernetes

---

### ⭐ If this project helped you, please give it a **Star** on GitHub — it helps others discover it too! 🌟

```
