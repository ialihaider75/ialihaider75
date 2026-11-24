# Hi, I'm Ali Haider 👋

**Backend engineer** building scalable, event-driven fintech systems in Java and Spring Boot. 7+ years of designing and owning features end to end, from architecture to production, with a focus on reliability and measurable impact. These days I'm also building AI agents, the backend way.

**[Portfolio](https://ialihaider75.github.io)** · **[LinkedIn](https://www.linkedin.com/in/ialihaider75)** · **ialihaider75@gmail.com**

---

### 🔭 Right now

- 💼 **Open to backend roles, remote or with relocation.** Based in Lahore, Pakistan (UTC+5). My role at Moniepoint ended in a recent round of layoffs, and I'm looking for my next team. If you're hiring for Java, Spring Boot or distributed systems, I'd love to hear from you.
- 🤖 **Learning applied AI by building it:** a tool-calling agent in Java, from the agent loop up ([spending-coach](https://github.com/ialihaider75/spending-coach)).
- 📦 **Maintaining** my first open-source library, [keycloak-spring-boot-starter](https://github.com/ialihaider75/keycloak-spring-boot-starter).

---

### 🤖 Building: [spending-coach](https://github.com/ialihaider75/spending-coach)

An AI agent that investigates your spending history to answer open-ended money questions, like *"Why am I running out of money before the 25th?"* It's a hand-written tool-calling loop over a Postgres transaction store, not a chat wrapper around an LLM.

- **11 tools** for overviews, period comparisons, recurring charges, anomaly detection, month-end projections and savings simulations. The arithmetic happens in Java, never in the model.
- **Guardrails:** step and wall-clock caps, repeat-call detection, and JSON-schema validation of every tool call.
- **Human in the loop:** the agent can pause to ask a clarifying question, and nothing changes in your budget until you approve its proposal.
- **Auditable:** every tool call is recorded with its arguments, result and latency.
- **Evaluated before building:** a spike tested Gemini and Groq on schema validity, tool choice and knowing when to stop.

`Java 21` · `Spring Boot 4` · `PostgreSQL` · `Redis` · `Testcontainers` · 🚧 under active development; live LLM providers are next.

---

### 🚀 Open source: [keycloak-spring-boot-starter](https://github.com/ialihaider75/keycloak-spring-boot-starter)

[![Maven Central](https://img.shields.io/maven-central/v/com.intellermatrix/keycloak-spring-boot-starter.svg)](https://central.sonatype.com/artifact/com.intellermatrix/keycloak-spring-boot-starter)
[![CI](https://github.com/ialihaider75/keycloak-spring-boot-starter/actions/workflows/pr-checks.yml/badge.svg)](https://github.com/ialihaider75/keycloak-spring-boot-starter/actions/workflows/pr-checks.yml)
[![License](https://img.shields.io/github/license/ialihaider75/keycloak-spring-boot-starter)](https://github.com/ialihaider75/keycloak-spring-boot-starter/blob/master/LICENSE)

Keycloak authentication for Spring Boot with one dependency and a YAML block. It provisions the realm, client and roles idempotently at startup, fails fast on bad configuration, and exposes a small, stable API for sign-up, login and user lookup. It also ships a **Claude Code plugin** that integrates it into your project for you.

```xml
<dependency>
    <groupId>com.intellermatrix</groupId>
    <artifactId>keycloak-spring-boot-starter</artifactId>
    <version>1.0.0</version>
</dependency>
```

---

### 🛠️ Recent work: Senior Backend Engineer at Moniepoint (2023 – 2026)

Mostly on savings:

- 💰 **Interest engine:** daily accrual and 30-day payouts, run by self-healing jobs that backfill missed runs with no money lost. Thousands of users earned millions in interest within 2 months of launch.
- 📈 **Savings onboarding and calculator:** an idempotent, asynchronous onboarding flow and a modular projection engine that helped make savings **70% of company revenue in a quarter**.
- 📬 **Exactly-once notifications:** a hybrid Outbox–Inbox design delivering email, SMS and push at ~99.9% consistency.
- ⚡ **Kafka performance:** a three-phase listener that cut latency from seconds to milliseconds.

Animated walkthroughs of these systems are on my **[portfolio](https://ialihaider75.github.io)**.

---

### 🧰 Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=flat&logo=testcontainers&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)

---

### 🌱 Off the clock

- [x] DayDreamer ✌️
- [x] ~~Programmer~~ 😁
- [x] Learner 💖
- [x] Nerd 💻
- [x] Space enthusiast 🚀

**Thanks for stopping by. If your team is building something that needs to stay up, [let's talk](https://www.linkedin.com/in/ialihaider75).**
