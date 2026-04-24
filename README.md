# hr-automation-ai-agent.json

# 🤖 AI HR Automation System (n8n + RAG + AI Agent)

This project demonstrates how to build an **AI-powered HR assistant** using n8n, comparing:

1. Traditional automation (data ingestion)
2. AI Agent-based intelligent system

---

## 🚀 System Overview

### 1️⃣ Data Ingestion Workflow (Non-AI)
- Fetch resumes from Google Drive
- Process documents
- Generate embeddings
- Store in Pinecone vector database

👉 Purpose: Build a searchable knowledge base of candidates

---

### 2️⃣ AI Agent Workflow
- AI Agent with memory
- Vector search (Pinecone)
- Answers HR queries like:
  - "Find Python developers"
  - "List candidates with 3+ years experience"

👉 Purpose: Intelligent HR assistant

---

## 🧠 Architecture

Google Drive → n8n → Embeddings → Pinecone → AI Agent → HR Queries

---

## 🛠 Tech Stack
- n8n
- OpenAI (LLM + Embeddings)
- Pinecone (Vector DB)
- Google Drive API

---

## 💡 Real Use Cases
- Resume screening automation
- Candidate search system
- HR chatbot
- Internal knowledge assistant

---

## ⚖️ Key Insight

| Feature | Traditional Workflow | AI Agent |
|--------|--------------------|---------|
| Logic | Rule-based | Intelligent |
| Query Handling | Fixed | Dynamic |
| Scalability | Medium | High |

---

## 📂 Files
- `/workflows/hr-automation-non-ai.json`
- `/workflows/hr-automation-ai-agent.json`

---

## 👨‍💻 Author
Akash C.M
