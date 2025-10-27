# Hey, I'm Paweł 👋

**Java Developer** specializing in secure and resilient backend architecture. I enjoy solving complex challenges in microservices, concurrency, and CI/CD automation to build robust, production-ready systems.

---

## What I'm Up To

- **Open to Opportunities:** Seeking full-time **Java Software Engineer** roles with teams that value business context, maintain high engineering standards, and build systems for long-term success. Open to relocation.
  
- **Current Focus:** Strengthening expertise in algorithms, data structures, and system design patterns
---

## 🧰 Core Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Java-25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring-Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>
</p>

**Architecture:** Microservices • Event-Driven • Hexagonal • Domain-Driven Design  
**Practices:** Test-Driven Development • Infrastructure as Code • CI/CD

---

## 💼 Featured Projects

### Passwordless Authentication System
**Live Demo:** [auth.bankapp.online](https://auth.bankapp.online)

Built a production-ready WebAuthn authentication system in collaboration with a business analyst, and UX designers. The goal: eliminate password-based authentication while maintaining full control over credential storage and avoiding vendor lock-in.

**What I delivered:**
- Microservices architecture with clear boundaries: REST API for authentication + async AMQP service for notifications via RabbitMQ
- Test-Driven Development using red-green-refactor cycles throughout
- Infrastructure-as-code deployment enabling one-command provisioning of the entire stack (Docker, PostgreSQL, RabbitMQ, Cloudflare tunnel, Nginx)

**Tech:** Java 25 • Spring Boot • Spring Security • RabbitMQ • WebAuthn • PostgreSQL • Docker • Cloudflare

[![Auth System Repo](https://github-readme-stats.vercel.app/api/pin/?username=BankApp-project&repo=auth&theme=tokyonight&show_owner=true)](https://github.com/BankApp-project/auth)

---

### BankApp's Core Transaction System
**Live Demo:** [bankapp.mackiewicz.info](https://bankapp.mackiewicz.info)

Built a banking application to explore concurrent transaction processing and data integrity patterns in financial systems. The core challenge: preventing race conditions when multiple requests attempt to modify the same account balance simultaneously.

**My approach:**
- Implemented pessimistic locking with Spring Data JPA and PostgreSQL to guarantee transaction isolation
- Wrote comprehensive JUnit tests specifically targeting concurrency scenarios
- Automated deployment through GitHub Actions to AWS infrastructure (EC2 + RDS)

**Tech:** Java 21 • Spring Boot • PostgreSQL • AWS (EC2, RDS) • Docker • GitHub Actions

[![BankApp Repo](https://github-readme-stats.vercel.app/api/pin/?username=pawel-mackiewicz&repo=bankapp&theme=tokyonight&show_owner=true)](https://github.com/pawel-mackiewicz/bankapp)

---

## 🏔️ When I'm Not Coding

Recharging by:
- 🧘 Practicing yoga
- ⛰️ Hiking mountain trails
- 🛶 Kayaking  
- 🧖 Sauna sessions

(And yes, there's usually a Sudoku puzzle nearby)

---

## 📫 Let's Connect

<p align="left">
  <a href="https://linkedin.mackiewicz.info" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
  <a href="mailto:career@mackiewicz.info" target="blank"><img align="center" src="https://img.shields.io/badge/Contact_Me-333333?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Email" /></a>
</p>
