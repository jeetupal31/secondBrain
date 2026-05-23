# SecondBrain — Personal Knowledge Base

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

> A personal knowledge management app — save links, notes, tweets, YouTube videos, and documents to your second brain. Organise, tag, and search everything in one place.

## Features

- 🔗 **Save anything** — links, notes, YouTube videos, Twitter/X threads, documents
- 🏷️ **Smart tagging** — tag content by topic for quick retrieval
- 🔍 **Full-text search** — find anything across your entire knowledge base
- 📁 **Collections** — group related items into named collections
- 🌐 **Share brain** — generate a public read-only link to share your collection
- 🔐 **Private by default** — JWT-authenticated, your notes stay yours

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | Next.js, TypeScript, Tailwind CSS |
| Backend | Node.js, Express, TypeScript |
| Database | MongoDB + Mongoose |
| Auth | JWT, bcrypt |

## Content Types Supported

| Type | How to save |
|------|------------|
| Link / Article | Paste URL → auto-fetches title + preview |
| Note | Free-text markdown note |
| YouTube | Paste YouTube URL → embeds video |
| Tweet | Paste Twitter/X URL → embeds tweet |
| Document | Upload file → stored with metadata |

## Local Setup

```bash
git clone https://github.com/jeetupal31/secondBrain.git
cd secondBrain
npm install

cp .env.example .env   # add MONGO_URI, JWT_SECRET

# Backend
cd server && npm run dev

# Frontend
cd client && npm run dev
```

---

Made by [Jeetu Pal](https://github.com/jeetupal31)
