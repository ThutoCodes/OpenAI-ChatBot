# Chatbot UI by Thuto Mpshe

> A modern AI chat interface fully set up, customized, and hosted by [Thuto Thabang Mpshe](https://github.com/ThutoCodes) — built for real-world use cases and personal learning.

![Chatbot UI Screenshot](./public/readme/screenshot.png)

---

## 🚀 Live Demo

🔗 [Coming Soon / Add Your Deployment URL]

---

## 🛠 Project Overview

Chatbot UI is a responsive, full-featured interface for interacting with AI models (OpenAI, Ollama, Azure, etc.).  
This version was fully set up and deployed by Thuto Mpshe, including secure Supabase integration, real-time chat persistence, and production-ready enhancements.

---

## 🧩 Key Features

- ✅ AI-Powered Chat Interface
- 🔐 Supabase Authentication & Storage
- 🧠 Multi-model Support (LLMs)
- 💬 Responsive & Modern UI
- ⚙️ Local and Cloud Deployment Support
- 🛡️ Secure Environment Variable Configuration

---

## 👨🏽‍💻 Maintainer

**Thuto Thabang Mpshe**  
Software Development Student • Full-Stack Developer • Tech Innovator

📍 Based in South Africa  
🔗 [GitHub](https://github.com/ThutoCodes) | [LinkedIn](https://www.linkedin.com/in/thuto-mpshe)

---

## 💡 Personal Customizations

- 🌐 Hosted deployment with Supabase & Vercel
- 🧑‍💻 Added Supabase backend for secure login & storage
- 🎨 Customized interface design for professional look
- 🧩 Extended backend logic to support real data
- 📁 Organized clean project structure for scalability

---

☁️ Deployment Stack
Layer	Tech Used
Frontend	Next.js + Tailwind CSS
Backend	Supabase (Postgres)
Auth	Supabase Email Auth
Deployment	Vercel + Docker
Models	OpenAI / Ollama

---
## 📦 Local Setup

```



# Clone the repo
git clone https://github.com/ThutoCodes/chatbot-ui.git
cd chatbot-ui

# Install dependencies
npm install

# Start Supabase (requires Docker & Supabase CLI)
supabase start

# Set environment variables
cp .env.local.example .env.local
# Fill in values from `supabase status`

# Run the app
npm run chat

