# 🐙 OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Express, TypeScript, and MongoDB.

## 📋 Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite frontend
│   ├── src/
│   ├── package.json
│   ├── vite.config.ts
│   ├── tsconfig.json
│   └── index.html
└── backend/           # Node.js + Express backend
    ├── src/
    ├── package.json
    ├── tsconfig.json
    └── .env.example
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- MongoDB 5.0+
- npm or yarn

### Frontend Setup
```bash
cd octofit-tracker/frontend
npm install
npm run dev
```
Frontend runs on: `http://localhost:5173`

### Backend Setup
```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```
Backend runs on: `http://localhost:8000`

### MongoDB Setup
```bash
# Make sure MongoDB is running on port 27017
mongod
```
MongoDB connection: `mongodb://localhost:27017/octofit-tracker`

## 📡 API Endpoints

- `GET /api/health` - Health check endpoint

## 🛠️ Tech Stack

**Frontend:**
- React 19
- Vite
- TypeScript
- ESLint

**Backend:**
- Node.js
- Express
- TypeScript
- Mongoose (MongoDB ODM)
- CORS

## 📝 License

MIT