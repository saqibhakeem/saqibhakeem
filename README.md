# Hi, I'm Muhammad Saqib 👋

### AI Engineer building autonomous agents, voice systems & production ML pipelines

I build AI systems that work without supervision: agents that use tools through **MCP**, voice and calling agents that talk to real customers, WhatsApp bots that handle conversations, and ML pipelines that retrain themselves.

📍 Karachi, Pakistan  |  🎓 Computer Science |  📬 saqibhakeem45@gmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saqib-hakeem-cs/)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-D14836?logo=gmail&logoColor=white)](mailto:saqibhakeem45@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat-25D366?logo=whatsapp&logoColor=white)](https://wa.me/923191395519)

---

## 🚀 What I Build

| | |
|---|---|
| 🤖 **Autonomous AI agents** | Agents that plan, call tools, retrieve knowledge, and complete multi-step tasks |
| 🔌 **MCP servers & integrations** | Connect LLMs to real business data and tools through the Model Context Protocol |
| 🎙️ **Voice & calling agents** | Sub-second voice agents with real-time speech-to-speech and barge-in interruption |
| 💬 **WhatsApp conversational AI** | Omni-channel conversational agents for orders, verification, and support |
| 💬 **WhatsApp bots** | Customer-facing bots for support, orders, and automation |
| 📄 **RAG systems** | Document Q&A with grounded, source-backed answers |
| ⚙️ **MLOps pipelines** | Automated ingestion, retraining, deployment, and monitoring |

---

## 🛠️ Featured Systems

### 🛡️ VanguardCOD: Autonomous Voice & WhatsApp AI for E-Commerce COD
A multi-tenant B2B SaaS platform that replaces manual call centers with autonomous voice and WhatsApp AI to verify Cash-on-Delivery (COD) orders, capture landmarks, negotiate address alterations, and eliminate Return-to-Origin (RTO) losses in emerging markets.
- **Ultra-low latency ($\le 650\text{ ms}$) voice pipeline:** Built a framework-less AsyncGroq runtime (Whisper Large v3 Turbo, LLaMA 3.3 70B, Orpheus TTS) with hardware-level RMS barge-in interruption.
- **Meta WhatsApp Cloud API Agent:** Multi-turn conversational chat for instant order confirmation, landmark negotiation, and delivery rescheduling.
- **Deterministic HITL Checkpoints & Anti-Loop Safeguards:** Gated price alterations and address changes pause for admin approval; customers receive instant WhatsApp notifications upon decision, backed by approval memory injection that prevents duplicate tickets.
- **Telephony Lifecycle & Automated Retries:** Twilio Voice PSTN gateway, 25s ring timeout, and automated 2-hour retry scheduling for missed calls.
- **Multi-Tenant SaaS Portal & Softphone Lab:** React 19, TypeScript, and Tailwind CSS v4 console with self-serve onboarding, RTO risk scoring (0-100), and an in-browser WebAudio softphone simulator.
- **Production-grade reliability:** 71 automated async tests ($100\%$ pass rate) covering telephony, agents, and multi-tenant isolation.
- **Stack:** Python, FastAPI, AsyncGroq, LLaMA 3.3 70B, Whisper, Meta WhatsApp Cloud API, Twilio Voice, React 19, TypeScript, Vite, Tailwind CSS v4, SQLAlchemy, Pytest
- 🔗 [Repository](https://github.com/saqibhakeem/VanGuardCOD.git)

### 🍽️ Restaurant MCP + RAG System
An MCP server that gives an AI agent live access to restaurant data (menu, availability, and knowledge base) combined with RAG for accurate, grounded answers.
- Exposes restaurant operations as tools an agent can call
- RAG layer answers questions from menu and policy documents
- **Stack:** Python, MCP, RAG, ChromaDB, FastAPI
- 🔗 [Repository](https://github.com/saqibhakeem/MCP-Server-Restaurant-and-Client-Agent-.git)

### 📞 AI Calling Agent (ElevenLabs)
A voice agent that holds natural phone conversations, handles customer queries, and completes tasks over a call.
- Low-latency, natural-sounding speech
- Tool calling to fetch information and take actions mid-call
- **Stack:** ElevenLabs Conversational AI, Python, LLM tool calling
- 🔗 [Repository / Demo](ADD_LINK)

### 🎙️ Voice Bot
A speech-in, speech-out assistant that understands spoken requests and answers in real time.
- **Stack:** Speech-to-text, LLM, text-to-speech, Python
- 🔗 [Repository / Demo](ADD_LINK)

### 💬 WhatsApp Bot
An automated WhatsApp assistant that handles customer conversations and workflows around the clock.
- **Stack:** WhatsApp API, Python, FastAPI, LLM
- 🔗 [Repository / Demo](ADD_LINK)

### 📄 Document Intelligence Workspace (PDF RAG)
Upload PDFs and ask questions. Answers are grounded in the document content.
- **Stack:** FastAPI, ChromaDB, LangChain, sentence-transformers, Groq API, React
- 🔗 [Repository](ADD_LINK)

### 🌫️ AQI Forecasting Pipeline (Serverless MLOps)
A fully automated system that forecasts Karachi's air quality **24, 48, and 72 hours ahead**.
- Hourly feature ingestion and daily retraining with **GitHub Actions**
- **Hopsworks** as feature store and model registry
- Diagnosed a seasonal regime shift that made every model lose to a naive baseline, then fixed it with a 45-day rolling training window: **Ridge RMSE 5.75 vs 7.26 baseline**
- Streamlit dashboard with hazard alerts, SHAP explanations, and a backtested accuracy tracker
- **Stack:** Python, scikit-learn, TensorFlow, Hopsworks, GitHub Actions, Streamlit, SHAP
- 🔗 [Repository](ADD_LINK)

### 🦷 Dental Diagnostics AI
A computer vision model for dental X-ray diagnosis, built with clinical staff input and validated against their requirements.
- **91% classification accuracy**
- **Stack:** Python, PyTorch, YOLO, scikit-learn, Django

---

## 🧰 Tech Stack

**Agents & LLMs:** LangChain · LangGraph · AsyncGroq · Whisper · MCP · Tool Calling · Agentic RAG · ElevenLabs

**Backend & APIs:** Python · FastAPI · AsyncIO · Django · REST APIs · WebSockets · Meta WhatsApp Cloud API · Twilio Telephony

**Frontend & Visuals:** React 19 · TypeScript · Vite · Tailwind CSS · WebAudio API

**ML & Deep Learning:** PyTorch · TensorFlow · scikit-learn · YOLO · SHAP · NLP · Computer Vision

**MLOps & Deployment:** Docker · GitHub Actions · CI/CD · Hopsworks · Streamlit

**Data:** PostgreSQL · SQLite (aiosqlite) · MySQL · MongoDB · ChromaDB · SQLAlchemy 2.0 · Pandas · NumPy

---

## 💼 Work With Me

I take on projects where AI needs to do real work:

- ✅ AI agents that automate repetitive business workflows
- ✅ Voice and calling agents for support, sales, and bookings
- ✅ WhatsApp automation for customer communication
- ✅ MCP servers that connect LLMs to your tools and data
- ✅ RAG chatbots trained on your documents
- ✅ ML pipelines with automated retraining and monitoring

**Have a project or an open role?** Message me on [WhatsApp](https://wa.me/923191395519) or email **saqibhakeem45@gmail.com**.

---

<p align="center"><i>I build AI that acts, not just answers.</i></p>
