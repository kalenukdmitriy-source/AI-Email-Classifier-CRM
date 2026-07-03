<div align="center">

# 🚀 AI Email Classifier CRM

### AI-Powered Email Classification & Smart CRM Automation with n8n

<img src="Banner.png" width="100%" alt="AI Email Classifier CRM Banner">

<br>

![n8n](https://img.shields.io/badge/n8n-Automation-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Google AI](https://img.shields.io/badge/AI-Powered-Workflow-4285F4?style=for-the-badge)

</div>

---

# 📌 About

**AI Email Classifier CRM** is a complete AI-powered email automation system built with **n8n**.

The workflow automatically receives incoming emails from **Gmail**, analyzes them using **OpenAI**, classifies each message by category, detects the language, generates an AI summary and reply, stores every interaction inside **Google Sheets CRM**, and automatically applies the correct Gmail label.

This project demonstrates how AI can automate an entire email processing pipeline with almost zero manual work.

---

# ✨ Features

- 📥 Automatic Gmail email processing
- 🤖 AI-powered email classification
- 🌍 Automatic language detection
- 📝 AI-generated email summaries
- ✉️ AI-generated email replies
- 🏷 Automatic Gmail label assignment
- 📊 Google Sheets CRM logging
- 📈 Dashboard with email analytics
- ⚡ Fully automated workflow
- 🔧 Easy to customize and extend

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| OpenAI API | Email Analysis & AI Reply |
| Gmail API | Email Processing |
| Google Sheets | CRM Storage & Dashboard |

---

# 📊 Workflow

```text
Gmail
   │
   ▼
Receive Email
   │
   ▼
Filter Internal Emails
   │
   ▼
OpenAI Analysis
(Category / Language /
Summary / Reply)
   │
   ▼
Format Response
   │
   ├──────────────► Google Sheets CRM
   │
   ├──────────────► Gmail AI Reply
   │
   └──────────────► Apply Gmail Label
```

---

# 📸 Screenshots

## 🤖 Main AI Email Workflow

<img src="screenshots/workflow.png" width="100%">

Receives emails, analyzes them with AI, generates replies, stores interactions in CRM and applies Gmail labels automatically.

---

## 📊 Google Sheets CRM

<img src="screenshots/google-sheets-crm.png" width="100%">

Central CRM where every processed email is stored with category, summary, language, confidence score and AI response status.

---

## 📈 CRM Dashboard

<img src="screenshots/dashboard.png" width="100%">

Dashboard displaying email statistics, category distribution and AI processing metrics.

---

## 📥 Incoming Support Email

<img src="screenshots/incoming-email.png" width="100%">

Example of an incoming technical support request received in Gmail.

---

## 🤖 AI Generated Reply

<img src="screenshots/ai-reply.png" width="100%">

Automatic AI-generated response sent directly from Gmail.

---

# 📁 Project Structure

```text
AI-Email-Classifier-CRM/
│
├── Banner.png
├── README.md
│
└── screenshots/
    ├── workflow.png
    ├── google-sheets-crm.png
    ├── dashboard.png
    ├── incoming-email.png
    └── ai-reply.png
```

---

# 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kalenukdmitriy-source/AI-Email-Classifier-CRM.git
```

### 2. Import the workflow

Open **n8n** and import or recreate the workflow in your workspace.

### 3. Configure credentials

Before running the automation configure:

- OpenAI API
- Gmail API
- Google Sheets API

### 4. Activate

Enable the workflow and send a test email to your Gmail account.

---

# 💼 Business Value

- Reduce manual email processing
- AI-powered email classification
- Automatic CRM synchronization
- Instant AI-generated email replies
- Automatic Gmail organization
- Centralized email history
- Analytics dashboard
- Faster customer response time

---

# 🎯 Use Cases

- AI Email Assistant
- Email CRM Automation
- Customer Support Automation
- AI Helpdesk
- Gmail Automation
- Sales Email Processing
- Business Process Automation
- AI Workflows

---

# 📄 License

This project is published for educational and portfolio purposes.

---

<div align="center">

### ⭐ If you like this project, give it a star!

</div>
