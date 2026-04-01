# next-multi-tenant

> Next Multi-Tenant: Multi-tenant SaaS app with subdomain routing and isolated data

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Next.js, TypeScript, MongoDB, Mongoose, NextAuth

## 🏗️ Architecture
Three-tier architecture: Next.js, TypeScript backend, React/TypeScript frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/next-multi-tenant
cd next-multi-tenant

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
