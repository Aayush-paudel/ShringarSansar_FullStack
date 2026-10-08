# Shringar Sansar Full-Stack Starter

Frontend: React + Vite. Backend: Node.js + Express + Socket.IO. Database: PostgreSQL + Prisma.

## Run
1. `docker compose up -d`
2. `cd backend && npm install && copy .env.example .env` (Windows) / `cp .env.example .env` (macOS/Linux)
3. `npx prisma generate && npx prisma migrate dev --name init && npm run seed && npm run dev`
4. New terminal: `cd frontend && npm install && npm run dev`
5. Open http://localhost:5173

The starter includes JWT verification-code auth, product API/admin CRUD foundation, order schema/API foundation, PostgreSQL schema, and Socket.IO chat foundation. Production integrations still need real email delivery, eSewa verification, secure media storage, full admin authorization/2FA, WebRTC TURN/signaling, rate limiting, HTTPS, backups, and deployment configuration.