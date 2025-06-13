
# 📬 Gmail AI Email Manager

Automatically monitor, analyze, and classify Gmail messages using AI for smarter email organization and prioritization.

🔗 **Workflow Link**: [n8n.io/workflows/4722](https://n8n.io/workflows/4722-gmail-ai-email-manager/)

---

## ⚙️ How It Works

### 📧 Gmail Monitoring (Trigger)
- Polls Gmail inbox every minute
- Triggers workflow on new emails

### 📖 Email Content Extraction
- Retrieves full body, subject, headers, metadata
- Captures sender, recipient, labels, and threads

### 🔍 Email History Analysis
- Checks prior messages from sender
- Detects cold vs. warm emails
- Analyzes entire thread history

### 🤖 Intelligent Classification Agent
- Uses Claude Sonnet 4 for context-aware classification
- Detects intent, urgency, and automation

### 🏷️ Smart Label Assignment
Automatically applies labels:
- **To Respond**: Action needed
- **FYI**: Informational
- **Notification**: Service or policy updates
- **Marketing**: Promotions and ads
- **Meeting Update**: Calendar events
- **Comment**: Feedback on tasks/docs

### 📋 Structured Processing
- Parses AI output to ensure consistency
- Maps output to Gmail Label IDs

---

## 🛠️ Tools Used

- **n8n** – Workflow automation
- **Gmail API** – Email access and labeling
- **Anthropic Claude** – Email classification
- **Gmail Tools** – History and thread search
- **Structured Output Parser** – Label mapping

---

## 📦 Key Features

- Real-time classification
- Context-aware email history analysis
- Cold vs. warm email detection
- Multiple intelligent label categories
- Auto Gmail label application
- Thread tracking and header analysis

---

## 🚀 Ideal Use Cases

- Executives with high email volume
- Sales teams managing prospects
- Customer support ticket triage
- Marketing content filtering
- Teams needing smart email organization

---

## 👨‍💻 Created By

**Max Mitcham** – [maxmitcham](https://n8n.io/workflows/4722-gmail-ai-email-manager/)

---

> AI-Powered Inbox Management
