# AI-FAQ-Chatbot(DiagFlow)

# 🤖 AI FAQ Chatbot – Internship Assistant

This is a smart AI-powered FAQ chatbot built using **Google Dialogflow**. It answers common questions about internships, including application processes, eligibility, company information, stipend, and more.

Live Demo 👉 https://github.com/jayanibv/AI-FAQ-Chatbot/blob/main/index.html

## 💡 Features

- 🔎 Answers FAQs about internships in real-time
- 🧠 Built with NLP using Google Dialogflow
- 💬 Handles small talk and multiple question types
- 🌐 Web-integrated using Dialogflow Messenger
- 📄 Multiple response variations to make it conversational

## 🛠️ Technologies Used

- Dialogflow (Google Cloud NLP)
- HTML5 (for website integration)
- GitHub Pages (for live deployment)

## 🧩 Intents Covered

| Intent                        | Example Questions                                      |
|------------------------------|--------------------------------------------------------|
| Application Process          | How to apply? Where to submit my resume?              |
| Required Documents           | What do I need to submit?                             |
| Internship Duration          | How long is the internship?                           |
| Stipend and Benefits         | Is the internship paid? What benefits are offered?    |
| Company Information          | What does the company do? Where is it located?        |
| Small Talk (Optional)        | Hi, Thanks, What's your name?                         |

## 📦 File Structure

AI-FAQ-Chatbot/

├── README.md

├── index.html # For chatbot deployment

├── chatbot_export.zip # Dialogflow agent export

├── intents/ # Individual intent files

## 🚀 Deployment Guide

### 🧠 1. Dialogflow Setup
- Go to [Dialogflow Console](https://dialogflow.cloud.google.com/)
- Create Agent → Add Intents → Define training phrases & responses
- Enable "Dialogflow Messenger" under Integrations

### 🌐 2. Web Deployment (GitHub Pages)
- Clone this repo or upload files
- Replace `YOUR_AGENT_ID` in `index.html` with your Dialogflow agent ID
- Enable GitHub Pages (Settings → Pages → Source → `/root`)
- Share the live link (e.g., `https://yourusername.github.io/AI-FAQ-Chatbot/`)

## 📝 Report
See `chatbot_report.pdf` for full documentation, use cases, and testing details.


## 🙋‍♂️ Author
**Venkata Jayani B.**  
Intern | Saveetha Institute of Medical and Technical Sciences

## 📃 License
This project is licensed for academic and personal learning use.
