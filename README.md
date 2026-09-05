# Hi, I'm Berk Aydemir 👋

### AI Automation Engineer | n8n Developer | AI Agents | API Integrations

I build AI-powered automation workflows that solve real business problems using modern automation tools and APIs.

Currently, I focus on developing intelligent automation systems with n8n, AI models, REST APIs, and cloud services. My goal is to create scalable workflows that save time, reduce manual work, and improve business processes.

---

## 🚀 Tech Stack

**Automation & AI**
🤖 n8n · 🧠 OpenAI · 🎙️ OpenAI Whisper · 💎 Google Gemini · 🔎 RAG (Qdrant) · 🌐 REST APIs

**Backend & Data**
🐘 PostgreSQL · 🧠 Redis · 📄 Google Sheets · 📓 Notion API · 📁 Google Drive API · 📑 Gotenberg · 🛒 SerpAPI / Google Shopping API · ⚽ RapidAPI

**Integrations & Messaging**
📧 Gmail API · 💬 Slack API · 📬 Telegram Bots · 🏠 Home Assistant API

**Dev Tools**
🐳 Docker · 💻 JavaScript · 🔀 Git & GitHub

---

## 📌 Featured Projects

### [🤖 AI Job Radar (SmartJob Radar)](https://github.com/BerkAydemirn8n/SmartJob-Radar)
An AI-powered job monitoring workflow that collects job listings, removes duplicates, analyzes them with AI, stores structured data in Google Sheets, and sends high-quality opportunities directly to Telegram. Deduplicates against previously seen listings before scoring, and only alerts on results above a quality threshold — so the feed stays high-signal instead of forwarding every match.

### [🐾 Vet Telegram AI Receptionist](https://github.com/BerkAydemirn8n/vet-telegram-ai-receptionist)
An AI-powered Telegram receptionist that handles veterinary clinic inquiries, manages appointments, provides pricing information, and connects customers with staff when needed. Uses Qdrant for retrieval-augmented answers on clinic knowledge, and enforces an "always fetch a fresh calendar event ID within the same turn" rule to eliminate a class of stale-reference bugs in reschedule/cancel flows.

### [⚽ AI Sports Digest](https://github.com/BerkAydemirn8n/ai-sports-digest)
An AI-powered workflow that collects sports news, removes duplicates, summarizes and scores stories, and delivers a daily personalized newsletter by email. Deduplicates near-identical headlines using Jaccard word-similarity rather than exact-match, so reworded versions of the same story don't slip through twice.

### [📸 Receipt Radar](https://github.com/BerkAydemirn8n/receipt-radar)
An AI-powered OCR workflow that reads receipt and invoice photos, extracts structured data (amount, date, merchant, category), and saves them to Notion — built almost entirely with no-code nodes. Normalizes all extracted dates to ISO format before storage to avoid day/month ambiguity across locales.

### [📦 Bulk Receipt Processor](https://github.com/BerkAydemirn8n/bulk-receipt-processor)
A scaled-up version of Receipt Radar that watches a shared Google Drive folder, deduplicates receipts against a PostgreSQL database, retries on failure, and sends daily summary reports to Slack.

### [✈️ AI Travel Planner](https://github.com/BerkAydemirn8n/ai-travel-planner)
An intelligent travel planning assistant that gathers trip preferences conversationally over Telegram, pulls in real venue and weather data (Foursquare, Open-Meteo), and generates a day-by-day itinerary delivered as a PDF. Includes a dedicated error-alerting branch that posts to Slack on real workflow failures, verified against an actual PDF-conversion outage.

### [🎫 IT Helpdesk / Ticket Triage](https://github.com/BerkAydemirn8n/it-helpdesk-ticket-triage)
An AI-powered support automation that classifies incoming Gmail tickets by category and priority, logs them to Notion, auto-replies to the sender, and escalates critical issues to Slack. A second, separate scheduled workflow queries the last 7 days of tickets and emails a categorized weekly summary report.

### [📧 AI Email/Inbox Assistant](https://github.com/BerkAydemirn8n/ai-email-inbox-assistant)
An AI-powered email triage system that analyzes incoming Gmail messages with an AI Agent, classifies them by urgency and intent, and routes them automatically — drafting replies for human review, scheduling meetings, sending urgent alerts, archiving spam, or labeling for later. Includes deterministic date-resolution logic to reliably handle relative date references (e.g. "this Thursday") without relying on LLM math.

### [🛒 PriceWise — Smart Shopping List & Price Comparator](https://github.com/BerkAydemirn8n/PriceWise)
An AI-powered shopping assistant that lets users manage a grocery list entirely through natural-language Telegram messages, normalizes item names into standard purchasable units, and compares live prices across retailers via SerpAPI (Google Shopping) to surface the cheapest option for each item. Includes multi-user list isolation via chat ID and deterministic empty-state/invalid-input guards on every branch, so the bot never fails silently — even on gibberish input or an empty list, it always returns a clear response instead of no response at all.

### [🏠 Smart Home Assistant](https://github.com/BerkAydemirn8n/Smart-Home-Assistant)
An AI-powered smart home controller that manages real Home Assistant devices through natural language over Telegram, by text or voice, reading live device states before acting and calling the right service with the right parameters — including ones it was never explicitly told about, like color control. A separate scheduled branch runs independently on its own, checking the temperature and turning on the AC automatically when it crosses a threshold, proactively notifying the user either way.

### [⚽ U21 Wonderkid & Performance Radar](https://github.com/BerkAydemirn8n/AI-Football-Scout)
An AI-powered scouting automation that scans five leagues weekly for standout U21 talents, using real match statistics and ratings from a football data API. Flagged players get a full scouting report — grounded in a small RAG knowledge base of professional report examples, not a generic AI guess — delivered as a photo scouting card (PDF) over Telegram, a tracked entry in Notion, and a weekly summary email, with duplicate protection to prevent the same player/match being logged twice.

---

## 🌱 Currently Learning

- Advanced n8n (sub-workflows, error-handling patterns)
- MCP (Model Context Protocol)
- Business Process Automation

---

## 🎯 Goal

Building production-ready AI automation systems that help businesses automate repetitive tasks and improve operational efficiency.

---

## 📫 Connect with Me

- GitHub:   https://github.com/BerkAydemirn8n
- LinkedIn: https://www.linkedin.com/in/berkkaydemir
