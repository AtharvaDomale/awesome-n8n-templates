# 🤖 AI-Powered WhatsApp Chatbot for Text, Voice, Images, and PDF with RAG

Enable Retrieval-Augmented Generation (RAG) on WhatsApp with support for text, voice, image, and document queries—all powered by OpenAI and MongoDB Vector Search.

🔗 **Workflow Link**: [n8n.io/workflows](https://n8n.io/workflows/4827-ai-powered-whatsapp-chatbot-for-text-voice-images-and-pdf-with-rag/)

---

## 👥 Who Is This For?

- Internal support teams  
- Product specialists  
- Knowledge managers in tech companies  

---

## 🚨 Problem Solved

Manually navigating product documentation slows down response time and creates inconsistency. This workflow automates document ingestion and enables fast, AI-powered responses over WhatsApp.

---

## 🧩 Workflow Overview

### 📥 Workflow 1: Document Ingestion & Indexing
- Imports Google Docs content
- Splits into chunks
- Embeds chunks using OpenAI embeddings
- Stores in MongoDB Atlas Vector Store for semantic search

### 💬 Workflow 2: Query & Respond via WhatsApp
- Supports:  
  - 📝 Text  
  - 🎙️ Voice (auto-transcribed)  
  - 🖼️ Images (contextual analysis)  
  - 📄 PDFs and documents  
- Retrieves relevant chunks using vector similarity
- Uses GPT-4o-mini with RAG for smart responses
- Maintains multi-turn context

---

## ⚙️ Setup Instructions

### 🗂️ Vector Embedding Setup
1. **Google Docs**: Authenticate and input your doc URL  
2. **MongoDB Atlas**: Connect your vector-enabled collection  
3. **Create a Search Index** (Example below)  
4. **Ensure** matching `data_index` is used in both workflows  

```json
{
  "mappings": {
    "dynamic": false,
    "fields": {
      "_id": { "type": "string" },
      "text": { "type": "string" },
      "embedding": {
        "type": "knnVector",
        "dimensions": 1536,
        "similarity": "cosine"
      },
      "source": { "type": "string" },
      "doc_id": { "type": "string" }
    }
  }
}
