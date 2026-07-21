# Hi, I'm Paweł 👋

Coding for fun.
Coding for bread.

**Practices:** DDD • Hexagonal Architecture • Test-Driven Development • Infrastructure as Code • CI/CD

---
## 💼 Featured Projects

### Passwordless Authentication System 

[![Auth System Repo](https://github-readme-stats.vercel.app/api/pin/?username=BankApp-project&repo=auth&theme=tokyonight&show_owner=true)](https://github.com/BankApp-project/auth)

A production-ready, completely passwordless authentication system based on the WebAuthn standard (Passkeys), built as a group project. The goal was to create an exceptionally user-friendly flow (one click + email) while eliminating password-related risks and account enumeration vulnerabilities.

**Architecture & Engineering:**
- **Microservices Architecture:** Clear boundaries featuring a REST API for authentication and an async AMQP service for notifications via RabbitMQ.
- **Robust Security:** Completely eliminated account enumeration possibilities and vendor lock-in while maintaining full control over credential storage.
- **Infrastructure as Code (IaC):** Delivered a DevOps solution that enables one-command provisioning of the entire stack (Docker, PostgreSQL, RabbitMQ, Cloudflare tunnel, Nginx), allowing a new server to spin up in minutes.
- **TDD:** Driven by strict red-green-refactor cycles.

**Tech:** Java 25 • Spring Boot • Spring Security • RabbitMQ • WebAuthn • PostgreSQL • Docker • Cloudflare

---

### BankApp Core Transaction System

[![BankApp Repo](https://github-readme-stats.vercel.app/api/pin/?username=bankapp-project&repo=bankapp-backend&theme=tokyonight&show_owner=true)](https://github.com/bankapp-project/bankapp-backend)

A banking backend co-developed with other IT enthusiasts to deeply explore multithreading, concurrency challenges, and data integrity in financial systems. The core challenge: building a system completely resilient to race conditions when multiple requests modify the same balance.

**Architecture & Engineering:**
- **Concurrency Control:** Implemented pessimistic locking with Spring Data JPA and PostgreSQL to guarantee transaction isolation.
- **Feature-Rich Banking Module:** Extended the system to include account creation, user management, inter-account transfers, strict IBAN validation, and transaction history tracking.
- **Testing & CI/CD:** Wrote comprehensive JUnit tests targeting complex concurrency scenarios and automated AWS deployments via GitHub Actions.

**Tech:** Java 21 • Spring Boot • PostgreSQL • AWS (EC2, RDS) • Docker • GitHub Actions

---

### Spong-Fu (Boot.dev Hackathon)

[![Spong-Fu Repo](https://github-readme-stats.vercel.app/api/pin/?username=spong-fu&repo=spongfu&theme=tokyonight&show_owner=true)](https://github.com/spong-fu/spongfu)

A browser-based multiplayer game developed from scratch in just 72 hours by a 3-person international team (India, USA, Poland). Built during the Boot.dev hackathon, competing among 2,000+ participants. 

**Engineering Highlights:**
- **Real-Time Multiplayer:** Designed and established seamless client-server communication using WebSockets.
- **Backend Mechanics:** Engineered the core server-side logic, including a custom collision detection system, physics simulation, and an active player matchmaking queue.

**Tech:** Java • JavaScript • WebSockets

---

### Potrzebnik

[![Potrzebnik Repo](https://github-readme-stats.vercel.app/api/pin/?username=potrzebnik&repo=potrzebnik&theme=tokyonight&show_owner=true)](https://github.com/potrzebnik/potrzebnik)

A platform is actively being built to connect pro bono organizations (such as orphanages) with potential donors. 

**Project Dynamics:**
- Developed in a cross-functional team environment collaborating closely with a Product Owner, UX Designers, and Frontend/Backend developers to deliver real-world social value.

**Tech:** Next.js • TypeScript • Drizzle ORM

---

### Socratic
[![Socratic Repo](https://github-readme-stats.vercel.app/api/pin/?username=pawel-mackiewicz&repo=socratic&theme=tokyonight&show_owner=true)](https://github.com/pawel-mackiewicz/socratic)

An AI-powered educational application built to consolidate scattered lifelong learning processes into a single, cohesive ecosystem. An entirely vibecoded project that I actively use and develop on a daily basis.

**Key Features:**
- **AI Integration:** Personalized learning paths structured around Bloom's taxonomy.
- **Automated Content:** Auto-generation of flashcards based on previously studied concepts.
- **Spaced Repetition:** Integrated the SuperMemo-2 algorithm to power a highly effective flashcard system for mastering both general knowledge and foreign language vocabulary.

**Tech:** Codex • Antigravity • React

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
