# Hi, I'm Paweł 👋

Just a guy who loves solving problems with good code.

**Current Focus:** *LeetCode for fun & Frontend for skills*

---

## 🧰 Core Tech Stack

<div align="left">
 <p>
    <a href="https://www.java.com" target="_blank"><img src="https://img.shields.io/badge/Java-25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/></a>
    <a href="https://spring.io/projects/spring-boot" target="_blank"><img src="https://img.shields.io/badge/Spring-Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/></a>
    <a href="https://www.python.org" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/></a>
    <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" alt="FastAPI"/></a>
  </p>
  <p>
    <a href="https://www.postgresql.org" target="_blank"><img src="https://img.shields.io/badge/PostgreSQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/></a>
    <a href="https://www.rabbitmq.com" target="_blank"><img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ"/></a>
    <a href="https://redis.io" target="_blank"><img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/></a>
  </p>
  <p>
    <a href="https.docker.com" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/></a>
    <a href="https://www.vim.org/" target="_blank"><img src="https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white" alt="Vim"/></a>
  </p>
</div>

**Practices:** Test-Driven Development • Infrastructure as Code • CI/CD • DDD

---
## 💼 Featured Projects

### Passwordless Authentication System
**Live Demo:** [auth.bankapp.online](https://auth.bankapp.online) | **Repo:** [BankApp-project/auth](https://github.com/bankapp-project/auth)

A production-ready, completely passwordless authentication system based on the WebAuthn standard (Passkeys), built as a group project. The goal was to create an exceptionally user-friendly flow (one click + email) while eliminating password-related risks and account enumeration vulnerabilities.

**Architecture & Engineering:**
- **Microservices Architecture:** Clear boundaries featuring a REST API for authentication and an async AMQP service for notifications via RabbitMQ.
- **Robust Security:** Completely eliminated account enumeration possibilities and vendor lock-in while maintaining full control over credential storage.
- **Infrastructure as Code (IaC):** Delivered a DevOps solution that enables one-command provisioning of the entire stack (Docker, PostgreSQL, RabbitMQ, Cloudflare tunnel, Nginx), allowing a new server to spin up in minutes.
- **TDD:** Driven by strict red-green-refactor cycles.

**Tech:** Java 25 • Spring Boot • Spring Security • RabbitMQ • WebAuthn • PostgreSQL • Docker • Cloudflare

[![Auth System Repo](https://github-readme-stats.vercel.app/api/pin/?username=BankApp-project&repo=auth&theme=tokyonight&show_owner=true)](https://github.com/BankApp-project/auth)

---

### BankApp Core Transaction System
**Live Demo:** [bankapp.online](https://bankapp.online) | **Repo:** [pawel-mackiewicz/bankapp](https://github.com/bankapp-project/bankapp-backend)

A banking backend co-developed with other IT enthusiasts to deeply explore multithreading, concurrency challenges, and data integrity in financial systems. The core challenge: building a system completely resilient to race conditions when multiple requests modify the same balance.

**Architecture & Engineering:**
- **Concurrency Control:** Implemented pessimistic locking with Spring Data JPA and PostgreSQL to guarantee transaction isolation.
- **Feature-Rich Banking Module:** Extended the system to include account creation, user management, inter-account transfers, strict IBAN validation, and transaction history tracking.
- **Testing & CI/CD:** Wrote comprehensive JUnit tests targeting complex concurrency scenarios and automated AWS deployments via GitHub Actions.

**Tech:** Java 21 • Spring Boot • PostgreSQL • AWS (EC2, RDS) • Docker • GitHub Actions

[![BankApp Repo](https://github-readme-stats.vercel.app/api/pin/?username=bankapp-project&repo=bankapp-backend&theme=tokyonight&show_owner=true)](https://github.com/bankapp-project/bankapp-backend)

---

### Socratic
**Repo:**[pawel-mackiewicz/socratic](https://github.com/pawel-mackiewicz/socratic)

An AI-powered educational application built to consolidate scattered lifelong learning processes into a single, cohesive ecosystem. An entirely vibecoded project that I actively use and develop on a daily basis.

**Key Features:**
- **AI Integration:** Personalized learning paths structured around Bloom's taxonomy.
- **Automated Content:** Auto-generation of flashcards based on previously studied concepts.
- **Spaced Repetition:** Integrated the SuperMemo-2 algorithm to power a highly effective flashcard system for mastering both general knowledge and foreign language vocabulary.

**Tech:** Codex • Antigravity • React

[![Socratic Repo](https://github-readme-stats.vercel.app/api/pin/?username=pawel-mackiewicz&repo=socratic&theme=tokyonight&show_owner=true)](https://github.com/pawel-mackiewicz/socratic)

---

### Spong-Fu (Boot.dev Hackathon)
**Repo:**[spong-fu/spongfu](https://github.com/spong-fu/spongfu)

A browser-based multiplayer game developed from scratch in just 72 hours by a 3-person international team (India, USA, Poland). Built during the Boot.dev hackathon, competing among 2,000+ participants. 

**Engineering Highlights:**
- **Real-Time Multiplayer:** Designed and established seamless client-server communication using WebSockets.
- **Backend Mechanics:** Engineered the core server-side logic, including a custom collision detection system, physics simulation, and an active player matchmaking queue.

**Tech:** Java • JavaScript • WebSockets

[![Spong-Fu Repo](https://github-readme-stats.vercel.app/api/pin/?username=spong-fu&repo=spongfu&theme=tokyonight&show_owner=true)](https://github.com/spong-fu/spongfu)

---

### Potrzebnik
**Repo:** [potrzebnik/potrzebnik](https://github.com/potrzebnik/potrzebnik)

A platform is actively being built to connect pro bono organizations (such as orphanages) with potential donors. 

**Project Dynamics:**
- Developed in a cross-functional team environment collaborating closely with a Product Owner, UX Designers, and Frontend/Backend developers to deliver real-world social value.

**Tech:** Next.js • TypeScript • Drizzle ORM

[![Potrzebnik Repo](https://github-readme-stats.vercel.app/api/pin/?username=potrzebnik&repo=potrzebnik&theme=tokyonight&show_owner=true)](https://github.com/potrzebnik/potrzebnik)

---

## 🏔️ When I'm Not Coding

Recharging by:
- 🧘 Practicing yoga
- ⛰️ Hiking mountain trails
- 🛶 Kayaking  
- 🧖 Sauna sessions

---

## 📫 Let's Connect

<p align="left">
  <a href="https://linkedin.mackiewicz.info" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
  <a href="mailto:career@mackiewicz.info" target="blank"><img align="center" src="https://img.shields.io/badge/Contact_Me-333333?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Email" /></a>
</p>
