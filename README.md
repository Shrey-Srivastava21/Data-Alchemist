
# 🧠 Data Alchemist Pro  
### *AI-Powered Data Cleaner & Rule Builder*

> An intelligent spreadsheet-to-insights engine built with DeepSeek AI, Redis task queues, and Next.js – transforming messy CSV/XLSX files into clean, validated datasets with explainable AI.

---

## 🚀 Live Demo & Links

| Resource      | Link                                                                 |
|---------------|----------------------------------------------------------------------|
| 🔗 Live Demo   | [Data-Alchemist.vercel.app](https://data-alchemist.vercel.app) |
| 🧠 GitHub Repo | [github.com/Shrey-Srivastava21/Data-Alchemist](https://github.com/Shrey-Srivastava21/Data-Alchemist.git) |
| 🎥 Demo Video  | [Watch Here](....)                              |

---

## 📦 Project Overview

A full-stack AI-powered web app to:
- Upload CSV/XLSX files for clients, workers, and tasks
- Validate data with 12+ rules & DeepSeek AI insights
- Auto-correct issues using smart suggestions
- Queue and optimize validation with Redis
- Export clean data and reusable rule files

---

## 🛠️ Tech Stack

| Layer         | Technology Used                           |
|---------------|--------------------------------------------|
| **Frontend**  | Next.js 14, TypeScript, Tailwind CSS       |
| **UI**        | Shadcn UI, Magic UI                        |
| **Backend**   | Node.js, API Routes (Next.js), TypeScript |
| **AI Layer**  | DeepSeek AI API                            |
| **Queue**     | Redis + Task Queues                        |
| **Database**  | MongoDB + Mongoose                         |
| **Auth**      | NextAuth.js (Email or OAuth)               |

---

## ⚙️ Core Features

### ✅ Smart File Upload
- Supports **CSV/XLSX** for various datasets  
- Auto-detects headers and cleans malformed fields  

### 🧠 AI-Powered Validation
- 12+ built-in validation rules:
  - Required fields, duplicate IDs, malformed JSON/arrays
  - Out-of-range values, missing references, slot overloads  
- Leverages **DeepSeek AI** to:
  - Suggest contextual fixes
  - Explain anomalies
  - Generate rules from natural language  

### 🔁 Redis-Powered AI Queueing
- Batches and caches prompts via Redis  
- Prevents race conditions and redundant calls  

### 🎨 Visual UI + Rule Builder
- MagicUI homepage with CTAs  
- Shadcn UI dashboards for:
  - Uploads, validation feedback, and error badges  
- Rule builder supports natural-language rule entry  

### 💾 Export Functionality
- Download cleaned **CSV/XLSX**
- Export AI-generated `rules.json` for automation

---

## 🧪 Validation Rules Implemented

1. Missing Required Fields  
2. Duplicate Entity IDs  
3. Malformed Arrays / JSON  
4. Value Range Checks  
5. Skill Slot Overload  
6. Reference Integrity Checks  
7. AI-based Anomaly Correction  
8. Phase/Duration Validity  
9. Cross-Entity Dependency Rules  
10. AI Suggestion Matching  
11. Redis-Prompt De-Duplication  
12. Pattern Detection & Explanation  

---

## 🖥️ Local Development Setup

### 🔧 Prerequisites
- Node.js 18+
- Redis Server or Cloud Redis URL
- MongoDB URI
- DeepSeek AI API Key

### ⚙️ Steps to Run

```bash
git clone https://github.com/Shrey-Srivastava21/data-alchemist.git
cd data-alchemist-pro

# Install dependencies
npm install

# Add your env file
touch .env.local
```

### 🧬 Sample `.env.local`

```env
MONGODB_URI=mongodb://localhost:27017/data-alchemist
NEXTAUTH_SECRET=your-nextauth-secret-key-here
NEXTAUTH_URL=http://localhost:3000
OPENROUTER_API_KEY=your-openrouter-api-key-here
REDIS_USERNAME=default
REDIS_HOST=your-aiven-redis-host.aivencloud.com
REDIS_PORT=your-port
REDIS_PASSWORD=your-password
```

```bash
# Start development server
npm run dev
```

---

## 🌐 Deployment Guide (Vercel)

Vercel automatically detects Next.js projects.

### 🚀 Manual Deployment

```bash
npm run build
vercel --prod
```

### 🔑 Vercel Environment Variables

Set these in **Vercel → Project Settings → Environment Variables**:

```env
MONGODB_URI=mongodb://localhost:27017/data-alchemist
NEXTAUTH_SECRET=your-nextauth-secret-key-here
NEXTAUTH_URL=http://localhost:3000
OPENROUTER_API_KEY=your-openrouter-api-key-here
REDIS_USERNAME=default
REDIS_HOST=your-aiven-redis-host.aivencloud.com
REDIS_PORT=your-port
REDIS_PASSWORD=your-password
```

---

## 🧪 How to Test the Platform

1. Upload a sample CSV or XLSX file  
2. Check validation feedback in real-time  
3. Use the AI validation module for suggestions  
4. View Redis logs for queue activity  
5. Export the clean file & ruleset  

---

## ✨ Feature Highlights

| Feature                         | Description                                                      |
|----------------------------------|------------------------------------------------------------------|
| AI-Powered Validation            | Fixes malformed fields, detects anomalies                        |
| Redis-Based AI Queuing           | Reliable, deduplicated prompt management                         |
| Natural Language Rule Builder    | “Don’t assign T001 with T002” → AI-generated rules               |
| Real-Time Inline Feedback        | Visual error highlights with fix suggestions                     |
| Export Clean Data + Rules        | One-click CSV + JSON download                                    |
| Beautiful UI                     | MagicUI landing + Shadcn dashboard                               |

---

## 🙏 Special Thanks

- [DeepSeek AI](https://deepseek.com)  
- [Redis](https://redis.io)  
- [Shadcn UI](https://ui.shadcn.com)  
- [Magic UI](https://magicui.design)

---

> **Built with ❤️ by Shrey Srivastava for intelligent, AI-driven data workflows.**
