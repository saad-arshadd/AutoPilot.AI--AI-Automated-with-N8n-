
# 🧠📅 AutoPilot.AI — Your AI Executive Assistant Powered by n8n

**AutoPilot.AI** is a fully automated AI agent built using **n8n** that acts as your personal **task manager, calendar scheduler, and productivity analyst** — all in one smart pipeline. It combines the power of LLMs with workflow automation to organize your time, responsibilities, and priorities effortlessly.

---

## 🚀 What It Can Do

✅ **Schedule Meetings & Events Automatically**  
✅ **Assign Tasks to Yourself with Priority Levels**  
✅ **Sync Everything to Google Sheets & Calendar**  
✅ **Extract and Speak Your Daily Schedule**  
✅ **Summarize All Pending Tasks from Sheets**  
✅ **Take Voice Commands (via Webhook/Interface)**  
✅ **Fully Automated via n8n Workflows**  

---

## 🧠 How It Works (Behind the Scenes)

1. **Trigger**: Accepts a voice/text prompt (e.g., “Schedule team call for tomorrow 3 PM”)
2. **LLM Agent (Llama/GPT)** understands intent
3. **n8n Workflow** routes action:
   - `Google Calendar Node`: Adds/extracts events
   - `Google Sheets Node`: Logs new tasks with priorities
4. **Output**: Returns confirmation OR summary of schedule/tasks
5. **Optional**: Sends notification via Email, WhatsApp, Slack, etc.

---

## ⚙️ Technologies Used

- 🤖 **n8n** – Workflow automation engine  
- 🧠 **LLM (LLaMA / GPT / Claude)** – Intent detection & natural responses  
- 📆 **Google Calendar API** – Event management  
- 📊 **Google Sheets API** – Task tracking  
- 🔗 **Webhooks & n8n Interface** – Input/output gateway  
- 🛠️ Optional Frontend: Streamlit / Telegram Bot / Voice Assistant

---

