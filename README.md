# 🧠 Daily Briefing Agent

An AI-powered assistant built with LangChain that gives you a **daily summary** of:
- 📅 All Google Calendar events for today
- 💬 Recent Slack messages
- ✅ A summary of all todos or tasks

Perfect for engineers, PMs, and anyone who wants a smart, centralized daily briefing.

---

## 🚀 Features

- ✅ Fetch all events for the current day from Google Calendar
- ✅ Read recent messages from a specified Slack channel
- ✅ Summarize daily tasks or todos
- 🤖 Combine all data into a coherent markdown-style summary using an LLM

---

## 📦 Requirements

- Python 3.10+
- Slack bot token
- Google Cloud credentials
- OpenAI API key (or another LangChain-compatible model)

## 📅 Step-by-Step: Get Google Calendar API Access
### Step 1: Create a Google Cloud Project
- Go to Google Cloud Console
- Click "Create Project", name it (e.g., Daily Briefing Agent), and hit Create

### Step 2: Enable Google Calendar API
- Navigate to your project
- Go to APIs & Services → Library
- Search for Google Calendar API
- Click it and press Enable

### Step 3: Create OAuth Credentials
- Go to APIs & Services → Credentials
- Click "Create Credentials" → OAuth Client ID
- Choose:
    - Application type: Desktop App
    - Download the credentials.json file

### Step 4: First-Time Authorization
- Place credentials.json in the project root

On first run, a browser window will prompt you to authorize the app

After login, it will save a token.json file that keeps you authenticated
