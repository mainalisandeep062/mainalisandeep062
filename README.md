<h1 align="center">Hi, I'm Sandeep Mainali 👋</h1>

<p align="center">
  <b>Java Backend Developer</b> · Kathmandu, Nepal 🇳🇵
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sandeep-mainali-5b4316324/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sawondeep4@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/mainalisandeep062"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

### 🧑‍💻 About Me

I build **Spring Boot** applications — REST APIs, event-driven systems, and AI-integrated services. I'm comfortable across the backend stack: relational data modeling, caching, asynchronous messaging, and containerized deployment.

- 🔭 Experience working as a **Java Backend Developer at Varosa Technology**, where I started as an intern and moved into a full-time role delivering production features end to end.
- 🌱 Deepening my knowledge of **distributed systems, microservices, and system design**.
- 🎓 Pursuing a **BSc. in Computer Science & Information Technology** at Tribhuvan University (2023 – 2027).
- 💬 Happy to talk about Spring Boot, RabbitMQ, Redis, PostgreSQL, or anything backend.
- 📫 Reach me at **sawondeep4@gmail.com**

---

### 🛠️ Tech Stack
 
**Languages & Frameworks:** ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)  ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white)  ![Spring Data](https://img.shields.io/badge/Spring_Data-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
 
**Database & Caching:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=flat-square&logo=liquibase&logoColor=white)
 
**Messaging & API:** ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![WebSocket / STOMP](https://img.shields.io/badge/WebSocket_/_STOMP-010101?style=flat-square&logo=socketdotio&logoColor=white) ![REST API](https://img.shields.io/badge/REST_API-02569B?style=flat-square&logo=fastapi&logoColor=white) ![OpenAPI](https://img.shields.io/badge/OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black)
 
**Cloud & DevOps:** ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
 
**Version Control:** ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
 
---

### 🔧 Key Technical Contributions

<sub>As a Java Backend Developer</sub>

<details>
<summary><b>AI Integration &amp; Real-time Streaming</b> &nbsp;<kbd>expand</kbd></summary>

<br>

- **LLM Service Integration:** Built REST APIs exposing AI capabilities through OpenRouter using Spring WebClient, with reactive request handling for long-running model calls.
- **Streaming Response Pipeline:** Delivered model output to clients in real time via Flux-based Server-Sent Events (SSE), so responses render token by token instead of blocking until completion.
- **Conversation Persistence:** Captured token-level output as it streamed, enabling full conversation history and replay of prior sessions without re-invoking the model.

</details>

<details>
<summary><b>Distributed Systems &amp; Real-time Messaging</b> &nbsp;<kbd>expand</kbd></summary>

<br>

- **Messaging Architecture:** Engineered asynchronous, event-driven pipelines using STOMP over WebSockets with RabbitMQ as the message broker, decoupling producers from consumers for real-time messaging and notifications.
- **Event-driven Notifications:** Pushed live updates to connected clients over WebSocket subscriptions, replacing polling-based refresh with broker-driven delivery.

</details>

<details>
<summary><b>Database Architecture &amp; Query Optimization</b> &nbsp;<kbd>expand</kbd></summary>

<br>

- **Persistence Layer Design:** Designed the data access layer with PostgreSQL, Hibernate, and JPA, modeling relational schemas around access patterns rather than raw entity shape.
- **Complex Result Mapping:** Adopted MyBatis for multi-object mappings that did not map cleanly onto JPA entities, keeping complex reporting queries readable and explicit.
- **Caching Strategy:** Implemented Redis caching with a cache-aside pattern, custom TTLs, and write-based eviction, noticeably reducing database load on frequently-read data while keeping cached state consistent after writes.
- **Schema Migration:** Introduced Liquibase for version-controlled migrations, making schema deployment consistent and repeatable across environments instead of manually applied.

</details>

<details>
<summary><b>Data Workflows &amp; Reliability</b> &nbsp;<kbd>expand</kbd></summary>

<br>

- **Bulk Data Exchange:** Built Excel import/export workflows (object ↔ spreadsheet) with Apache POI, allowing non-technical users to move data in and out of the system at volume.
- **Service-layer Test Coverage:** Wrote unit and integration tests for business logic, covering both happy paths and failure branches around external calls.

</details>

---

### 🚀 Featured Projects

<details>
<summary>🏦 <b>Banking Microservice</b> — a simplified banking system on a microservices architecture &nbsp;<kbd>click to expand</kbd></summary>

<br>

`Java` `Spring Boot` `Microservices` `Eureka` `RabbitMQ` `MySQL` `Docker`

Built with **Eureka** service discovery and an **API Gateway** handling JWT validation and request routing.

- `AccountService` uses **pessimistic locking** and idempotency checks to stay correct under concurrent balance updates.
- `TransactionService` orchestrates deposits, withdrawals, and transfers via **Feign clients**, publishing async events to RabbitMQ.
- `NotificationService` consumes RabbitMQ messages and pushes real-time updates to clients over WebSocket.
- A 7-service **Docker Compose** stack (API Gateway, Eureka, RabbitMQ, 4 dedicated MySQL databases) with named per-service volumes and healthcheck-gated `depends_on`, so dependent services wait for actual DB/broker readiness rather than just container start.

🔗 [View repository](https://github.com/mainalisandeep062/Banking-Microservice)

</details>

<details>
<summary>✅ <b>Task Tracker</b> — task management with JWT auth and real-time notifications &nbsp;<kbd>click to expand</kbd></summary>

<br>

`Java` `Spring Boot` `JWT` `WebSocket/STOMP` `Docker`

Stateless **JWT** authentication with role-based access control (Admin / Employee).

- API documented with **OpenAPI/Swagger**.
- Email notifications via SMTP, scheduled reminders via cron jobs, and real-time in-app notifications over **WebSocket/STOMP**.
- Containerized with Docker, with a **GitHub Actions** CI workflow and a live instance deployed on Render.

🔗 [View repository](https://github.com/mainalisandeep062/Task-Management)

</details>

---

### 📊 GitHub Stats


<p align="center">
  <a href="https://git.io/streak-stats"><img src="https://github-readme-streak-stats.herokuapp.com?user=mainalisandeep062&theme=kanagawa-paper&hide_border=true&border_radius=5&card_width=500&hide_total_contributions=true" alt="GitHub Streak" /></a>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mainalisandeep062&theme=tokyo-night&hide_border=true&height=300&area=true&color=7aa2f7&line=7aa2f7&point=bb9af7" alt="Contribution graph" />
</p>

---

<p align="center">
  <i>Thanks for stopping by — feel free to reach out!</i>
</p>
