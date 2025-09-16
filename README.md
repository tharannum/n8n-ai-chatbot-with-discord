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
 ```
📂 Project Files

1. workflow.json → Exported n8n workflow (can be imported into n8n)

2. README.md → Project overview and usage (this file)

3. Documentation.md → Detailed explanation of the nodes and workflow

4. screenshots/ → Contains images of the workflow

📸 Workflow Diagram

Here’s how the workflow looks in n8n:

 

<img width="896" height="488" alt="Workflow Diagram" src="https://github.com/user-attachments/assets/3f1c33bb-c2f6-4340-bfd6-1605a689d48e" />

##🚀 How to Use (Demo Instructions)

Clone this repo

git clone https://github.com/tharannum/n8n-chatbot-demo.git


Open n8n (self-hosted or cloud version).

Import workflow.json into your n8n instance.

Replace demo placeholders with real credentials:

Ollama / OpenAI key

Discord Bot token

Any API key for the HTTP Request node

Execute the workflow 🚀

✅ Features

- Handles chat messages and forwards them to an AI Agent.

- Uses Ollama Chat Model for intelligent responses.

- Maintains context with Simple Memory.

- Sends output to Discord via Bot integration.

- Supports HTTP Requests for external APIs.
