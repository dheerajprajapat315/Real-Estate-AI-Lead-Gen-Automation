# 🏠 Real Estate AI Agent Suite (n8n + OpenAI)

An advanced automation suite designed for Real Estate dealers to instantly qualify, score, and manage international leads.

## 🚀 Key Features
- **AI Qualification:** Automatically extracts intent, budget, and property type from incoming leads.
- **Lead Scoring:** Categorizes leads into **HOT, WARM, or COLD** based on custom business logic.
- **Instant Alerts:** Automated Email notifications (with priority formatting) sent to dealers for high-priority leads.
- **Centralized Database:** Real-time data logging into Google Sheets for easy tracking.

## 🛠️ Tech Stack
- **Automation:** n8n
- **AI Model:** OpenAI (GPT-4o)
- **Storage:** Google Sheets API
- **Communication:** Gmail API / Webhooks

## 📦 How to Use
1. Import the provided `.json` workflow file into your n8n instance.
2. Configure your OpenAI and Google Sheets credentials.
3. Set up the Webhook URL as your lead source.
