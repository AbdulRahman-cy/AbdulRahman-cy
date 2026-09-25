# 👋 Hi, I'm AbdulRahman Tamer

I'm a **backend engineer** and an engineering student at Alexandria University's Faculty of Engineering. I work mainly with **Django and PostgreSQL**, and I care about how things work underneath: query cost, indexes, concurrency, and constraint-based scheduling. I lead backend engineering for an IEEE competition team, and I'm currently exploring **distributed systems and cloud architecture**.

I also make videos about database internals and query optimization on [my YouTube channel](https://www.youtube.com/@AbdulRahmanBackend).

---

## 💻 Skills

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat&logo=django&logoColor=white)
![SimpleJWT](https://img.shields.io/badge/SimpleJWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![django-filter](https://img.shields.io/badge/django--filter-092E20?style=flat&logo=django&logoColor=white)
![Google OR-Tools](https://img.shields.io/badge/Google%20OR--Tools-4285F4?style=flat&logo=google&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)

### Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat&logo=reactquery&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat&logo=gunicorn&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

### 🔭 Currently Exploring
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Distributed Systems](https://img.shields.io/badge/Distributed%20Systems-333333?style=flat)
![Cloud Architecture](https://img.shields.io/badge/Cloud%20Architecture-333333?style=flat)

---

## 🚀 Featured Projects

### 🎓 [School Management System](https://github.com/AbdulRahman-cy/School-Management-System)
A full-stack student information system: **Django REST API + React/TypeScript frontend**, deployed with Docker Compose.

![Python](https://img.shields.io/badge/Python%203.12-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%2015-4169E1?style=flat&logo=postgresql&logoColor=white)
![OR-Tools](https://img.shields.io/badge/OR--Tools%20CP--SAT-4285F4?style=flat&logo=google&logoColor=white)
![JWT](https://img.shields.io/badge/JWT%20Cookies-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat&logo=reactquery&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat&logo=gunicorn&logoColor=white)

- **Automatic timetabling:** a constraint solver (Google OR-Tools CP-SAT) assigns lectures, tutorials, and labs to rooms and timeslots with no room, study-group, or teacher clashes across cohorts. A per-term PostgreSQL advisory lock keeps concurrent runs from double-booking.
- **Concurrency-safe enrollment:** seats are reserved with a single atomic `UPDATE ... WHERE seats_taken < capacity`, with timetable-conflict and duplicate-course checks before it.
- **Database tuning:** partial indexes on active enrollments, covering indexes, and aggregate queries instead of wide joins for the dashboards.
- **Auth:** cookie-based JWT (HttpOnly, SameSite=Strict, path-scoped refresh token, silent refresh, blacklist on logout) with Admin / Teacher / Student roles and server-side scoping to prevent IDOR.
- **Grades:** signals sync exam results into grade entries and enrollment totals; GPA and cohort statistics are computed in the database.
- **Frontend:** React + TypeScript with TanStack Query, including live seat-capacity polling.
- **Deployment:** Docker Compose with PostgreSQL, Gunicorn, and a multi-stage build that serves the frontend through Nginx.

### 📚 [Database Internals](https://github.com/AbdulRahman-cy/Database_Internals)
Video + slides series on query cost, indexes, query optimization, transactions, concurrency control, WAL, and recovery, with hands-on PostgreSQL examples.

---

## 📫 Find Me

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@AbdulRahmanBackend)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulrahman-tamer-65151b379)
