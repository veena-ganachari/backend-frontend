# Full-stack Assignment — Backend + Frontend

**Full-stack assignment with Node.js backend (JWT auth, role-based access, Task CRUD APIs) and React frontend, including Swagger docs, Postman collection, and scalability notes.**

---

## Summary
This repository contains a complete internship assignment implementing a secure, versioned REST API and a minimal frontend UI for testing.  
Stack used:
- **Backend:** Node.js + Express + MongoDB (Mongoose)  
- **Auth:** bcrypt for password hashing, JWT for authentication  
- **Frontend:** React (Create React App)  
- **Docs & Tests:** Swagger UI and Postman collection included

---

## Features implemented
- User registration & login (with hashed passwords and JWT tokens)
- Role-based access control (user / admin)
- CRUD APIs for **Tasks** (owner-restricted; admin can see all)
- API versioning (`/api/v1/...`)
- Centralized error handling and input validation
- Swagger documentation endpoint (`/api-docs`)
- Postman collection for quick testing
- Dockerfile & docker-compose for containerized setup
- Basic logging (Winston) and sample log file

---

## Repo structure
