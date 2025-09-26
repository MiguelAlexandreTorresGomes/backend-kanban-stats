# 🚀 Kanban API

A complete Kanban-style task management system backend.

## 🛠️ Tech Stack
- **Runtime**: Node.js + Express.js
- **Database**: PostgreSQL + Prisma ORM
- **Architecture**: MVC Pattern
- **Authentication**: JWT (JSON Web Tokens)


## 📋 Features
- [x] Boards CRUD
- [ ] Lists CRUD (in development)
- [ ] Cards CRUD
- [ ] JWT Authentication

## 🏃‍♂️ Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 12+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/MiguelAlexandreTorresGomes/backend-kanban.git
cd backend-kanban

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your database credentials

# Run database migrations
npx prisma migrate dev

# Start the development server
npm run dev
