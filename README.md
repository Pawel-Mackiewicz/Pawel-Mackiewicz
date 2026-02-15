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
**Live Demo:** [bankapp.online](https://bankapp.online)

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

---

## 📫 Let's Connect

<p align="left">
  <a href="https://linkedin.mackiewicz.info" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
  <a href="mailto:career@mackiewicz.info" target="blank"><img align="center" src="https://img.shields.io/badge/Contact_Me-333333?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Email" /></a>
</p>
