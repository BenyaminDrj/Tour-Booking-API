## Tour Booking API

A RESTful full-stack service for a tour booking platform, inspired by real-world production patterns.

---

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

---

## Core Features

- User authentication & authorization (JWT)
- Role-based access control (admin, guide, user)
- CRUD operations for tours, users, and reviews
- Advanced API features:
  - Filtering
  - Sorting
  - Field limiting
  - Pagination
  - Secure password hashing
  - Rate limiting & data sanitization
  - Centralized error handling

---

## Architecture

- MVC pattern
- RESTful API design
- Middleware-based request pipeline
- Global error handling strategy

---

## Security Practices

- JWT authentication
- Password hashing with bcrypt
- HTTP security headers (Helmet)
- Rate limiting
- NoSQL injection & XSS protection

---

## Application Type

Monolithic full-stack application with REST API and server-side rendered frontend.

---

## Project Structure

- controllers/ → Request handling logic
- models/ → Mongoose schemas and data models
- routes/ → API and view routes
- utils/ → Reusable utilities and helpers
- public/ → Frontend static assets (CSS, JS, images)
- views/ → Pug templates for server-side rendering
- data/ → Development data and import scripts

---

## Getting Started

```bash
npm install
npm run dev
```
