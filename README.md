# ⚙️ Lumora Services

The backend API powering Lumora's creative marketplace ecosystem.

This service manages authentication, artist portfolios, commissions, messaging, payments, notifications, and platform administration.

## ✨ Features

* Authentication & authorization
* User management
* Portfolio management
* Commission workflows
* Messaging services
* Notification system
* Payment tracking
* Admin tools
* Analytics & reporting

## 🛠 Tech Stack

* NestJS
* TypeScript
* PostgreSQL
* Prisma ORM
* Redis
* BullMQ
* JWT Authentication

## 🚀 Getting Started

### Install Dependencies

```bash
npm install
```

### Configure Environment

```bash
cp .env.example .env
```

### Run Database Migrations

```bash
npx prisma migrate dev
```

### Start Development Server

```bash
npm run start:dev
```

### Run Tests

```bash
npm run test
```

## 📂 Project Structure

```text
src/
├── modules/
├── common/
├── config/
├── database/
├── jobs/
├── guards/
├── interceptors/
└── main.ts
```

## 🔐 Security

* JWT Authentication
* Role-Based Access Control
* Request Validation
* Rate Limiting
* Audit Logging

## 📜 License

MIT License
