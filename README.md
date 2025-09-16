# n8n-ai-chatbot-with-discord

# 🤖 AI Chatbot Workflow with n8n (Demo)

This repository contains a **demo chatbot workflow** built using [n8n](https://n8n.io/).  
The workflow demonstrates how to integrate **AI models, memory, external APIs, and messaging tools** inside an automation pipeline.  

Even though this is a **demo version** (not fully configured with API keys/tokens), it highlights my ability to:  
- Design automation workflows  
- Connect multiple services (AI, APIs, Discord)  
- Showcase real-world chatbot architecture  

---

## ⚡ Features
- **Chat Trigger** → Starts when a chat message is received  
- **Ollama Chat Model** → Generates AI-powered responses  
- **Simple Memory** → Maintains conversational context  
- **HTTP Request Node** → Placeholder for external API calls (e.g., Weather, Crypto, News)  
- **Discord Integration** → Sends chatbot responses to a Discord channel  

---

## 🛠 Workflow Overview

```plaintext
When Chat Message Received
        │
        ▼
   Ollama Chat Model ----> Simple Memory
        │
        ▼
      AI Agent ----> HTTP Request (external API)
        │
        ▼
   Update Discord Channel

---
 
