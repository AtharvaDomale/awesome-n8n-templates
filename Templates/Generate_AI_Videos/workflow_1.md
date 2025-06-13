# 🎬 Generate AI Videos with Google Veo3, Save to Google Drive and Upload to YouTube

This no-code workflow automates the process of generating AI-powered videos using **Google Veo3**, storing them on **Google Drive**, creating **YouTube titles using GPT-4o**, and uploading to **YouTube** — all controlled via a **Google Sheet**.

🔗 **Workflow Link**: [n8n.io/workflows/4846](https://n8n.io/workflows/4846-generate-ai-videos-with-google-veo3-save-to-google-drive-and-upload-to-youtube/)

---

## 🚀 Key Benefits

- **💡 No-Code Interface**: Trigger the workflow directly from a Google Sheet.
- **⚙️ Full Automation**: Runs hands-free once configured.
- **🧠 AI-Powered**: Uses Google Veo3 for video and GPT-4o for SEO-friendly titles.
- **📁 Cloud Backup**: Saves all videos in Google Drive.
- **📈 YouTube Ready**: Auto-upload with correct metadata.
- **🧪 Scalable**: Handles multiple prompts via sheet entries.
- **🔒 Secure**: API-based integration for all services.

---

## ⚙️ How It Works

1. **Trigger**: Manually or automatically (e.g., every 5 minutes).
2. **Fetch Data**: Pulls unprocessed rows from Google Sheet.
3. **Video Creation**: 
   - Formats data from Sheet.
   - Sends to Google Veo3 via Fal.run API.
4. **Status Check**: 
   - Waits 60s.
   - Checks video generation status.
5. **Video Processing**:
   - Fetches video URL.
   - Generates YouTube title via GPT-4o.
   - Downloads the video file.
6. **Upload & Update**:
   - Saves video to Google Drive.
   - Uploads to YouTube via Upload-Post API.
   - Updates Google Sheet with video and YouTube URLs.

---

## 🛠️ Setup Instructions

### Google Sheet

Create a Sheet with the following columns:
