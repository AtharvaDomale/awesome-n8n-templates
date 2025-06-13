
# Build a Voice AI Chatbot with ElevenLabs and InfraNodus Knowledge Experts

**Created by:** InfraNodus  

**Last update:** 14 days ago  

**Categories:** Sales, Support, AI

---

## 🎯 Overview

This workflow enables you to build an **AI Voice Chatbot** using **ElevenLabs** for voice interface and **InfraNodus GraphRAG** as the knowledge base. It allows access to multiple knowledge graphs ("experts") and returns high-quality responses without the complexity of standard RAG vector store workflows.

---

## 🔧 How It Works

1. **Voice Input:** The user speaks through ElevenLabs conversational AI.
2. **Webhook Request:** The spoken query is sent via POST to n8n containing the prompt and sessionID.
3. **Expert Selection:** n8n AI agent chooses the right InfraNodus graph expert(s).
4. **Query Processing:** The query is reformulated and sent to InfraNodus endpoint.
5. **Knowledge Retrieval:** Relevant responses and statements from selected experts are returned.
6. **Response Integration:** n8n AI agent integrates these into a final answer.
7. **Voice Output:** ElevenLabs transforms text response into speech.

---

## 🧠 Why Use GraphRAG over Vector Stores?

- No need for complex setup or metadata configuration.
- Easy to update and manage knowledge bases.
- Provides context-rich responses based on document relationships.
- Can be reused in multiple n8n workflows.

---

## 🛠 Requirements

- [ ] InfraNodus account + API key ([API access](https://infranodus.com/api-access))
- [ ] ElevenLabs account
- [ ] OpenAI API key (or other LLM)
- [ ] n8n instance with AI agent and HTTP/Webhook nodes

---

## 📦 Customization Options

- Swap ElevenLabs for Telegram bot
- Combine voice with text AI chatbot (e.g., [popupchat.dev](https://popupchat.dev))
- Use GitHub repo for more workflow enhancements

---

## ❓ FAQ

**Q1:** How many experts to use?  

**A:** 2–7 is optimal to ensure quality and manageable orchestration.

**Q2:** Why not use ElevenLabs' own knowledge base?  

**A:** External knowledge allows reuse and better control of sources and context.

---

## 📚 Setup Guide & Resources

- 🔗 [n8n Workflow](https://n8n.io/workflows/4484-build-a-voice-ai-chatbot-with-elevenlabs-and-infranodus-knowledge-experts/)
- 📘 [Complete Setup Guide](https://support.noduslabs.com/hc/en-us/articles/20318967066396-How-to-Build-a-Text-Voice-AI-Agent-Chatbot-with-n8n-Elevenlabs-and-InfraNodus)
