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



## 🛠 Tech Stack

- n8n
- Groq LLM
- Telegram Bot API
- RSS Feeds

---

## 📄 License

MIT
