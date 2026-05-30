# 🚀 AI Social Media Automation Platform

An intelligent Social Media Automation Platform that enables users to create, schedule, and automatically publish AI-generated content across multiple social media platforms.

Built with React, TypeScript, Node.js, Express, MongoDB, Gemini AI, Leonardo AI, Cloudinary, and Zernio APIs.

---

## ✨ Features

### 🤖 AI Content Creation
- Generate engaging social media posts using Google Gemini AI
- Multiple content tones:
  - Professional
  - Creative
  - Funny
  - Minimalist
  - Excited
- Automatic hashtag generation

### 🎨 AI Image Generation
- Generate high-quality AI images using Leonardo AI
- Custom image prompts created automatically
- Image generation directly linked to post content

### 📅 Smart Scheduling
- Schedule posts for future publishing
- Date and time-based automation
- Automatic publishing through scheduler service

### 🔗 Multi-Platform Management
- Connect multiple social media accounts
- Centralized account management
- Publish to multiple platforms simultaneously

### 📊 Dashboard Analytics
- Scheduled posts tracking
- Published posts monitoring
- Connected account statistics
- Activity logs and history

### ☁️ Media Management
- Cloudinary integration
- Secure media storage
- Optimized media delivery

### 🔐 Authentication System
- User registration
- Login authentication
- JWT-based security
- Protected routes

---

## 🏗️ Architecture

Frontend:
- React 19
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Axios

Backend:
- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose

AI Services:
- Google Gemini AI
- Leonardo AI

Automation:
- Node Cron Scheduler
- Zernio Social Publishing API

Cloud Services:
- Cloudinary

---

## 📂 Project Structure


social-scheduler/
│
├── client/
│ ├── src/
│ │ ├── pages/
│ │ ├── components/
│ │ ├── context/
│ │ ├── api/
│ │ └── assets/
│
├── server/
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── services/
│ ├── middlewares/
│ └── config/


---

## ⚡ Core Modules

### AI Composer
Generate complete social media content with:
- AI-generated captions
- Smart hashtags
- AI-generated images
- Direct scheduling options

### Scheduler Engine
- Cron-based automation
- Automatic publishing
- Scheduled execution
- Failure handling

### Dashboard
- Post statistics
- Activity monitoring
- Account overview
- Publishing history

### Account Manager
- Social account integrations
- Connection management
- Platform selection

---

## 🛠️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/social-media-automation.git

cd social-media-automation
Frontend Setup
cd client

npm install

npm run dev
Backend Setup
cd server

npm install

npm run server
🔑 Environment Variables
Server (.env)
PORT=5000

MONGODB_URI=

JWT_SECRET=

GEMINI_API_KEY=

LEONARDO_API_KEY=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=

ZERNIO_API_KEY=
Client (.env)
VITE_BACKEND_URL=http://localhost:5000
🚀 Future Enhancements
AI Content Calendar
Post Performance Analytics
Team Collaboration
Bulk Scheduling
Social Listening
Trend Detection
AI Caption Variations
Advanced Reporting
📸 Screenshots
Dashboard

Add your dashboard screenshot here.

![Dashboard](./screenshots/dashboard.png)
AI Composer
![AI Composer](./screenshots/ai-composer.png)
Scheduler
![Scheduler](./screenshots/scheduler.png)
🎯 Key Highlights

✅ AI-Powered Content Generation

✅ AI Image Generation

✅ Automated Publishing

✅ Multi-Platform Management

✅ Cloud Media Storage

✅ Secure Authentication

✅ Responsive Modern UI

✅ Full Stack TypeScript Architecture
