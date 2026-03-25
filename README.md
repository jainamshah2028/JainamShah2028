<div align="center">
 
# Jainam S. Shah
 
**Backend & Full-Stack Engineer** · Node.js · Python · Microservices · PostgreSQL
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/jainamshah20)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/jainamshah2028)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:jainamshah2820@gmail.com)
[![Portfolio](https://img.shields.io/badge/Resume-4285F4?style=flat&logo=googledrive&logoColor=white)](#)
 
</div>
 
---
 
## About me
 
M.S. Computer Science @ Pace University (2025) · Currently building distributed backend systems at **Shoptaki** in New York on OPT.
 
I architect things that scale — microservice backends, authentication systems, and data pipelines. I care about clean separation of concerns, observable systems, and writing code that the next engineer can actually understand.
 
Right now I'm deep in **LeetCode** and system design prep, targeting backend/fullstack engineering roles at product-driven companies.
 
---
 
## What I'm building
 
### 🔐 SmartID — Distributed Auth Backend
> `Node.js` `Express` `PASETO v4` `PostgreSQL` `Prisma` `Docker`
 
A production-grade microservice authentication system with 4 independent services:
 
- **auth-service** — Email OTP flow, PASETO v4.public token issuance (Ed25519 signing), refresh token rotation, JWKS endpoint
- **gateway-service** — Path-based reverse proxy, JWKS token verification, rate limiting, configurable public route bypasses
- **user-service** — CRUD with master data validation, internal-only middleware
- **master-service** — Lookup data (roles, pronouns, country codes) with bootstrap seeding
 
All services containerized with Docker Compose, health-check-gated startup sequencing, and independent Prisma schemas per service.
 
```
Backend-Server/
├── services/
│   ├── auth-service/      # PASETO v4 · OTP · JWKS
│   ├── gateway-service/   # Reverse proxy · Rate limiter · Auth enforcement
│   ├── user-service/      # CRUD · Master validation
│   └── master-service/    # Lookup data · Bootstrap
└── docker-compose.yml     # Full orchestration
```
 
---
 
## Tech I work with
 
```python
backend   = ["Node.js", "Express.js", "Python", "PHP"]
databases = ["PostgreSQL", "MySQL", "Prisma ORM"]
infra     = ["Docker", "Docker Compose", "REST APIs"]
auth      = ["PASETO v4", "JWT", "Ed25519", "JWKS", "OAuth"]
frontend  = ["React.js", "HTML", "CSS", "JavaScript"]
tools     = ["Git", "Power BI", "BeautifulSoup"]
studying  = ["LeetCode", "System Design", "Distributed Systems"]
```
 
---
 
## Experience highlights
 
| Role | Company | Impact |
|------|---------|--------|
| Software Engineer Intern | Shoptaki, NY | Built SmartID auth backend · Docker orchestration |
| Full Stack Engineer | Replete Software Solutions | +40% user engagement · 5+ client apps shipped |
| Software Engineer | Noisy Steps Pvt. Ltd. | -20% load time · 3 full SDLC cycles |
 
---
 
## Projects
 
| Project | Stack | Highlight |
|---------|-------|-----------|
| [SmartID Backend](https://github.com/Shoptaki/Backend-Server) | Node.js · PASETO · Docker | 4-service microservice auth system |
| Python Web Scraper | Python · BeautifulSoup | 98% uptime · 50% faster ETL |
| Food Delivery Platform | PHP · MySQL · HTML/CSS | +40% new user conversion |
| BI Dashboard (TCS Forage) | Power BI · EDA | Executive-ready analytics |
 
---
 
## Currently
 
- 🔨 Building backend systems at **Shoptaki** (New York, OPT)
- 📚 Grinding **NeetCode 150** — targeting FAANG backend roles
- 📖 Deep-diving distributed systems & system design
- 🎯 Open to **full-time backend / fullstack engineering roles** starting immediately
 
---
 
## Education
 
**M.S. Computer Science** — Pace University, New York · 2023–2025
**B.Tech. Computer Science & Engineering** — Indus University, India · 2018–2022
 
---
 
<div align="center">
 
*If you're building something interesting and need a backend engineer who ships — let's talk.*
 
**[jainamshah2820@gmail.com](mailto:jainamshah2820@gmail.com)**
 
</div>
