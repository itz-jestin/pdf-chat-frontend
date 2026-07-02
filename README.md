DocuMind AI — Frontend
A React-based interface for DocuMind AI, a Retrieval-Augmented Generation (RAG) application that lets users upload PDFs and ask natural-language questions about their content.

🔗 Live demo: https://pdf-chat-frontend-seven.vercel.app/

Note: the backend is hosted on Railway. Some users on certain mobile networks (e.g. Jio) may intermittently see a DNS resolution error — a fix is in progress.

🔗 Backend repo: github.com/itz-jestin/documind-backend

Overview
This frontend connects to the DocuMind AI backend to provide:
PDF upload and processing
Chat-style Q&A over document content
Real-time responses powered by an LLM via OpenRouter
Tech Stack
React — UI framework
Vercel — deployment/hosting
Fetch/Axios for API communication with the FastAPI backend
Getting Started
Prerequisites
Node.js (v18+ recommended)
npm or yarn

Installation
Bash
Environment Variables
Create a .env file in the root directory:
Code
Run Locally
Bash

The app will be available at http://localhost:3000.
Build for Production
Bash
Project Structure
Code
Related
Backend repo (FastAPI + RAG pipeline): documind-backend

License
MIT
