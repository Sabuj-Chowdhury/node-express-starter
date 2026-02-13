# 🚀 Node Express Starter (TypeScript)

A clean, scalable, and production-ready Node.js + Express starter
template built with TypeScript.

This project provides a solid backend foundation with: - Express 5 -
TypeScript - JWT Authentication ready setup - Environment configuration
with dotenv - Centralized error handling - Zod validation support -
Scalable folder structure

---

## 📌 Project Overview

This starter template is designed to help developers quickly bootstrap a
backend API with best practices in mind.

It follows a modular architecture:

src/ ├── app/ │ ├── config/ │ ├── errorHelpers/ │ ├── middlewares/ │ └──
routes/ ├── app.ts └── server.ts

The structure separates concerns clearly: - Routes → API endpoints -
Middlewares → Error handling, Not Found handling - Config → Environment
variables - Helpers → Custom error utilities

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Sabuj-Chowdhury/node-express-starter
cd node_express_starter
```

Install dependencies:

```bash
npm install
```

---

## 🔐 Environment Setup

Create a `.env` file in the root directory.

You can copy from:

```bash
cp .env.example .env
```

Update environment variables like:

- PORT
- JWT secrets
- CORS origin
- Cookie configuration

---

## ▶️ Running the Project

Run in development mode:

```bash
npm run dev
```

The server will start on:

    http://localhost:port

---

## 🔑 Authentication (JWT Ready)

The project includes:

- jsonwebtoken integration
- Access & Refresh token configuration support
- Cookie-parser support
- Secure environment-based secret management

You can easily extend it for: - Login/Register - Role-based access
control - Token refresh logic

---

## 🛡 Error Handling

Includes:

- Global Error Handler middleware
- Custom AppError class
- 404 Not Found middleware

All errors are centralized and structured for production readiness.

---

## 📦 Tech Stack

- Node.js
- Express 5
- TypeScript
- Zod
- dotenv
- jsonwebtoken
- cors
- cookie-parser

---

## 🏗 How It Works (Short Explanation)

1.  `server.ts` starts the Express server.
2.  `app.ts` configures middlewares and routes.
3.  Routes handle API requests.
4.  Errors are passed to the global error handler.
5.  Environment variables control runtime behavior.
6.  JWT & cookies are ready for authentication implementation.

---

## 🚀 Why Use This Starter?

✔ Clean architecture\
✔ Production-ready structure\
✔ Easy to scale\
✔ Type-safe with TypeScript\
✔ Secure env configuration\
✔ Minimal but extensible

---

## 📈 Future Improvements

You can easily extend this with:

- Database integration (MongoDB / PostgreSQL)
- Docker support
- Swagger documentation
- Unit & Integration tests
- CI/CD pipeline

---

## 👨‍💻 Author

Sabuj Chowdhury
