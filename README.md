# 🦊 Fabalos n8n Automation Server

[![Deploy on Railway](https://img.shields.io/badge/deploy-railway-black?style=flat&logo=railway)](https://railway.app)
[![Status](https://img.shields.io/website?url=https%3A%2F%2Ffabalos-n8n.up.railway.app)](https://fabalos-n8n.up.railway.app)

> **Cloud-hosted n8n instance** powering GPT workflows, Tally webhooks, and Fabaverse automations.

---

## 🧠 Use Cases  
- Tally → GPT blog title generator  
- Notion → Tagging engine  
- Custom webhook routing + automation logic  
- Fabaverse internal tools / personal productivity flows

---

## 🚀 Setup

### 🔧 Environment Variables

Copy `.env.example` into `.env` and set secrets like your OpenAI API key or encryption key.

```bash
N8N_HOST=0.0.0.0
N8N_PORT=5678
N8N_PROTOCOL=http
N8N_EDITOR_BASE_URL=https://fabalos-n8n.up.railway.app
WEBHOOK_TUNNEL_URL=https://fabalos-n8n.up.railway.app
N8N_BASIC_AUTH_ACTIVE=false
