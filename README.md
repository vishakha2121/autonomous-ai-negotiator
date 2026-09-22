# 🤝 Autonomous AI Enterprise Negotiator

### Multi-Agent Debate • Constraint Optimization • LLM-Powered Deal Engine

> **"Where AI agents debate, optimize, and close deals — autonomously."**

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.111-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

---

## 📖 Overview

**Autonomous AI Enterprise Negotiator** is an intelligent multi-agent system that autonomously negotiates **procurement deals, vendor pricing, contracts, and SLAs** using:

- 🧠 **Multi-Agent Debate** — Buyer, Seller, and Mediator agents argue to reach optimal deals
- ⚖️ **Constraint Optimization** — Linear programming ensures budget, deadline, and quality constraints are respected
- 🤖 **LLM-Powered Reasoning** — GPT-based agents generate human-like negotiation arguments
- ⚡ **Real-Time UI** — Beautiful React dashboard with animated debate flow

This project demonstrates how **agentic AI** can automate complex commercial negotiations — from RFQ to signed contract — without human intervention.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🤝 **Multi-Agent Debate** | 3 specialized agents (Buyer, Seller, Mediator) negotiate in rounds |
| 📊 **Constraint Optimization** | OR-Tools based LP solver finds optimal deal price |
| 🧠 **LLM Reasoning** | GPT-4o-mini powered agents with role-based prompts |
| 💾 **Persistent History** | SQLite/SQLAlchemy stores every negotiation round |
| 🎨 **Premium UI** | Dark glassmorphism design with Framer Motion animations |
| ⚡ **REST API** | FastAPI backend with auto-generated Swagger docs |
| 🔄 **Fallback Mode** | Works offline with mock LLM if no API key |

---

## 🏗️ Architecture



---

## 🚀 Getting Started

### Prerequisites

- **Python 3.11+** → [Download](https://www.python.org/downloads/)
- **Node.js 18+** → [Download](https://nodejs.org/)
- **Git** → [Download](https://git-scm.com/)
- **OpenAI API Key** (optional) → [Get Key](https://platform.openai.com/api-keys)

> 💡 **No API key? No problem!** The app runs in **mock mode** with simulated LLM responses.

---

### 🔧 Backend Setup

```bash
# 1. Navigate to backend
cd backend

# 2. Create virtual environment
python -m venv venv

# 3. Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Setup environment variables
copy .env.example .env       # Windows
# cp .env.example .env       # Mac/Linux

# 6. Edit .env and add your OpenAI key (optional)
# OPENAI_API_KEY=sk-your-key-here

# 7. Run the server
python run.py