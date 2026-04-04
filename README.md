# Stoney E-Commerce

A full-stack e-commerce application built with Next.js, Spring Boot, and PostgreSQL.

## Overview

This project consists of:
- **Frontend**: Next.js application with Tailwind CSS (port 3000)
- **Backend**: Spring Boot REST API (port 8080)
- **Database**: PostgreSQL (port 5432)
- **Admin Tools**: Adminer for database management (port 8888)

## Quick Start

### Prerequisites
- Docker and Docker Compose
- VS Code with Dev Containers extension

### Setup

1. Open the project in VS Code
2. Click "Reopen in Container" when prompted
3. The dev container will automatically run `npm install`

### Running Services

All services are configured in `.devcontainer/docker-compose.yml` and will start automatically in the dev container.

Access the services:
- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:8080
- **Database Admin**: http://localhost:8888

## Development

### Frontend

The frontend uses:
- Next.js 20 with Node.js 20
- Tailwind CSS for styling
- ESLint and Prettier for code quality

Useful extensions (auto-installed):
- Tailwind CSS IntelliSense
- Prettier - Code formatter
- ES7+ React/Redux/React-Native snippets

Start development:
```bash
npm run dev
```

### Backend

Spring Boot API running on port 8080. Configure database connection in application properties.

### Database

PostgreSQL database with Adminer GUI for easy management.

## Environment Variables

Create `.env` or `.env.local` in the project root for environment-specific configuration. These files are automatically ignored by Git.

## Project Structure

```
.devcontainer/     # Dev container configuration
frontend/          # Next.js frontend application
backend/           # Spring Boot backend application
.gitignore         # Git ignore rules
```

## Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
