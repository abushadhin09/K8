# বাংলা শিক্ষা (Bangla Shikkha)

Premium Bengali Educational Web Application + Admin Panel

**Designed & Developed by ABU SHADHIN**  
Owner: [t.me/OWNER_BUNNY404](https://t.me/OWNER_BUNNY404)

## Tech Stack

- **Frontend:** Next.js 14, React, Tailwind CSS, Framer Motion
- **Backend:** Node.js, Express, Socket.io
- **Database:** MongoDB
- **Storage:** Cloudinary
- **Payment:** SSLCommerz
- **AI:** OpenAI API

## Getting Started

### Prerequisites

- Node.js 18+
- MongoDB (local or Atlas)

### Setup

```bash
# Install dependencies
npm install

# Copy environment file
cp .env.example .env

# Build shared package
npm run build -w @bangla-shikkha/shared

# Seed database (admin + demo data)
npm run seed

# Start dev servers (web + API)
npm run dev
```

- Web: http://localhost:3000
- API: http://localhost:4000

### Default Admin Login

- Email: `admin@gmail.com`
- Password: `ownerbunnyshadhin`

### Demo Teacher

- Email: `teacher@demo.com`
- Password: `teacher123`

## Features

- Student / Teacher / Admin roles with JWT auth
- Bangladesh flag-inspired premium UI with light/dark mode
- Course cards, enrollment, SSLCommerz payments
- Realtime chat (text, files, voice, pin/delete)
- Assignments, exams, results, ranking
- Attendance, class routine, notices
- Live class (Jitsi Meet)
- AI study assistant (Bengali)
- PDF certificate generator
- Admin dashboard and site settings

## Project Structure

```
KLZ/
├── apps/web/       # Next.js frontend
├── apps/server/    # Express + Socket.io API
└── packages/shared # Shared TypeScript types
```
