# 🤖 AI Personal Assistant – Communication Manager

A smart workflow that consolidates email, calendar, and Slack data to deliver a prioritized, AI-powered daily action plan—ideal for busy professionals and executives.

🔗 **Workflow Link**: [n8n.io/workflows/4723](https://n8n.io/workflows/4723-ai-personal-assistant/)

---

## ⚙️ How It Works

### ⏰ Automated Daily Trigger
- Runs every weekday at 8:00 AM
- Manual trigger for on-demand analysis

### 📧 Email Assistant Agent
- Analyzes unread emails under "To Respond" and "FYI"
- Detects urgency (High, Medium, Low)
- Cross-checks past emails for relationship context
- Highlights partnership or opportunity emails

### 📅 Follow-Up Assistant Agent
- Reviews last 3 days of calendar meetings
- Analyzes Fireflies transcripts for missed follow-ups
- Flags meetings with missing post-meeting communication

### 💬 Slack Assistant Agent
- Monitors direct messages and @mentions
- Identifies unreplied messages
- Prioritizes important threads needing attention

### 🎯 Master Orchestrator Agent
- Combines insights from Email, Calendar, Slack
- Cross-references Google Sheets to-do list
- Prioritizes tasks by urgency and business value
- Delivers a comprehensive daily action plan

### 📊 Task Management Integration
- Adds tasks to Google Sheets to-do tracker
- Sends daily briefing via Slack DM
- Tracks completed and pending tasks
- Maintains memory of conversations for continuity

---

## 🛠️ Tools Used

- **n8n** – Automation and workflow orchestration
- **Claude Sonnet 4 & Opus 4** – AI analysis
- **Gmail API** – Email monitoring
- **Google Calendar** – Meeting review
- **Slack API** – Message tracking
- **Fireflies API** – Transcript review
- **Google Sheets** – Task persistence

---

## 📦 Key Features

- Unified view of all communications (Email, Calendar, Slack)
- Intelligent prioritization based on AI context analysis
- Multi-agent collaboration for deep insight
- Slack-based daily summaries and task updates
- Relationship-aware email handling
- Task follow-up tracking and flagging

---

## 🚀 Ideal Use Cases

- C-level executives managing multiple channels
- Sales leaders tracking deals and meetings
- BizDev pros managing partners and follow-ups
- Anyone needing a smart daily productivity system

---

## 👨‍💻 Created By

**Max Mitcham** – [maxmitcham](https://n8n.io/workflows/4723-ai-personal-assistant/)

---

> AI That Works With You, Daily.
