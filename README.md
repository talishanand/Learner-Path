# 🧠 Learner Path — AI-Powered Day-Wise Learning Path Generator

An **n8n AI agent workflow** that automatically creates personalized, day-wise learning plans for any topic — complete with curated resources, a structured Google Doc, and scheduled Google Calendar events.

---

## ✨ Features

- 📅 **Day-wise curriculum** — structured from beginner to advanced
- 🔍 **Real resource URLs** — fetched live via SerpAPI (YouTube, articles, docs)
- 📄 **Google Docs** — auto-creates and fills a formatted learning document
- 🗓️ **Google Calendar** — schedules daily 2-hour study sessions automatically
- 🤖 **Powered by Google Gemini** — intelligent planning and content generation

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| [n8n](https://n8n.io) | Workflow automation |
| Google Gemini (PaLM API) | AI agent brain |
| SerpAPI | Web search & URL extraction |
| Google Docs API | Document creation & update |
| Google Calendar API | Event scheduling |

---

## 🚀 How It Works

1. **User sends a chat message** — e.g., *"Learn React in 7 days starting tomorrow"*
2. **AI plans the curriculum** — topics structured day by day
3. **SerpAPI fetches real URLs** — YouTube tutorials, official docs, articles
4. **Google Doc is created** — titled `7-Day React Learning Path` with all content
5. **Calendar events are scheduled** — one per day, 11 AM–1 PM, with links
6. **Final response** — Doc URL + event summary returned to the user

---

## 📦 Setup

### Prerequisites
- n8n instance (self-hosted or cloud)
- Google Gemini API key
- SerpAPI key
- Google Docs & Google Calendar OAuth2 credentials

### Import Workflow
1. Download `My Workflow.json`
2. Open your n8n instance
3. Go to **Workflows → Import**
4. Upload the JSON file
5. Add your credentials for each node
6. Activate the workflow

---

## 💬 Example Prompt
Learn Python in 5 days starting from Monday


**Output:**
- Google Doc: `5-Day Python Learning Path`
- 5 Calendar events (Mon–Fri, 11 AM–1 PM)
- Real YouTube, article, and documentation links for each day

---

## 📁 Files

| File | Description |
|------|-------------|
| `My Workflow.json` | n8n workflow export |
| `README.md` | Project documentation |

---

## 🙌 Author

Made by [@talishanand](https://github.com/talishanand)
