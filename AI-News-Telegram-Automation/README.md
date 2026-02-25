# 📰 AI News Telegram Automation (n8n + Groq)

An automated AI-powered news aggregation system built using **n8n** and **Groq LLM** that fetches RSS feeds across multiple categories and delivers a structured Telegram newsletter daily.

---

## 🚀 Features

- Fetches news from multiple RSS feeds:
  - 🤖 AI & Technology
  - 💰 Finance & Markets
  - 🌍 Global Politics
  - 🏅 Sports
  - 🌎 World News
- Uses Groq LLM for:
  - Intelligent classification
  - Section grouping
  - Headline prioritization
- Formats Telegram-ready Markdown
- Sends automated daily newsletter
- Fully modular workflow

---

## 🏗 Architecture

Schedule Trigger  
→ Multiple RSS Feeds  
→ Merge  
→ Data Cleanup (Code Node)  
→ AI Agent (Groq Model)  
→ Formatter (Code Node)  
→ Telegram Bot  

---

## 📦 Workflow File

The n8n workflow JSON file is located here:

```
workflows/ai-news-telegram-workflow.json
```

Import this file into your n8n instance to use.

---

## 🔧 Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-news-telegram-automation.git
```

---

### 2️⃣ Import Workflow into n8n

- Open n8n
- Go to Workflows
- Click **Import**
- Select the JSON file from `/workflows`

---

### 3️⃣ Configure Credentials

You must configure:

- Groq API credentials
- Telegram Bot Token
- RSS feed URLs (optional customization)

---

## 🤖 AI Model Used

Groq Chat Model (LLaMA 3.1 or equivalent)

---

## 📅 Automation

The workflow is designed to run via a Schedule Trigger daily.

---

## 📌 Example Output

```
📰 Top Trending News – 26 Feb 2026

📊 Finance
• Headline 1
• Headline 2

🤖 AI & Tech
• Headline 1
• Headline 2

🏅 Sports
• Headline 1
• Headline 2
```

---

## 🛠 Tech Stack

- n8n
- Groq LLM
- Telegram Bot API
- RSS Feeds

---

## 📄 License

MIT
