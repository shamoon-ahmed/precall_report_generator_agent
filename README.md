# 📞 Pre-Call Report Generator

An AI-powered assistant built using the **OpenAI Agents SDK** and **Chainlit UI**, designed to help sales reps generate pre-call reports by scraping and analyzing data from **LinkedIn profiles** and **company websites**.

---

## 🧠 How It Works

- Built with **OpenAI Agents SDK**
- Uses **tool calling** to scrape data from the web and LinkedIn
- Tools are integrated using real APIs like **Apify**, **Firecrawl**, and **ElevenLabs**
- Maintains **conversation history** using Chainlit sessions
- Runs on an interactive **Chainlit UI** for easy chat and voice input

---

## 🚀 Features

- 🔍 Scrapes **LinkedIn profiles** and **company websites**
- 🔧 Dynamically calls tools based on user queries
- 📄 Generates structured **pre-call reports**
- 🗣️ Supports both **text** and **voice input** (`/listen`)
- 🔄 Remembers context with **session history**

---

## 🔑 Environment Variables

Create a `.env` file with the following keys:

```env
GEMINI_API_KEY=
LINKEDIN_SCRAPER_API_KEY=
FIRECRAWL_API_KEY=
ELEVENLABS_API_KEY=
```
---

## ⚙️ Installation

1. **Clone the repo**:
   ```bash
   git clone https://github.com/shamoon-ahmed/precall_report_generator_agent.git
   cd your-repo-name

2. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt

---

## 💬 How to Use

1. **Run the app** in your terminal:

   ```Powershell
   uv run chainlit run agent.py

2. Type your message or use /listen to speak your request

3. Paste a LinkedIn profile URL or a company website link

4. Type "generate report" to receive a structured pre-call summary

