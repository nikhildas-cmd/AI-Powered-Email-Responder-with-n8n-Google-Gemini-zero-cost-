# AI Email Responder (n8n + Google Gemini)

## 📌 Overview
This workflow automates email handling using **n8n**, **Google Gmail API**, and **Google Gemini AI**.  
It reads incoming emails, generates an AI-powered reply, sends it back, and logs the details in Google Sheets.

## ⚙️ Features
- ✅ Gmail Trigger for new emails
- ✅ Decodes Base64 email body (handles "no subject/no body" cases)
- ✅ Uses Gemini API for smart replies (free tier)
- ✅ Sends automated replies via Gmail
- ✅ Logs sender, subject, and AI response into Google Sheets

## 🛠️ Tools Used
- [n8n](https://n8n.io) – No-code workflow automation
- [Google Gmail API](https://developers.google.com/gmail/api) – Email integration
- [Google Gemini](https://aistudio.google.com/) – Generative AI
- Google Sheets – Logging and tracking

## 🚀 Setup
1. Clone this repo / Import JSON workflow into n8n
2. Add your credentials:
   - Gmail API
   - Gemini API key
   - Google Sheets (replace `SHEET_ID`)
3. Deploy the workflow
4. Test by sending an email to your Gmail inbox

## 📂 Workflow Steps
1. Gmail Trigger → Fetch raw email
2. Function Node → Decode subject & body
3. Gemini API → Generate a polite AI reply
4. Gmail Node → Send response back
5. Google Sheets → Append log entry

## 🔮 Future Enhancements
- Sentiment analysis on emails
- Multi-language replies
- Priority tagging (Support, Sales, General)

---

💡 Built by **Nikhildas R** | AI Automation Engineer  
📧 nikhildasnikhildas1@gmail.com | 
