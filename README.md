<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:00C9FF&height=220&section=header&text=AI%20Support%20Ticket%20Assistant&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Built%20with%20n8n%20•%20Groq%20AI%20•%20Google%20Sheets&descAlignY=60"/>
</p>

<p align="center">

![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71?style=for-the-badge&logo=n8n)
![Groq](https://img.shields.io/badge/Groq-LLM-blue?style=for-the-badge)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Database-34A853?style=for-the-badge&logo=googlesheets)
![AI Agent](https://img.shields.io/badge/AI-Agent-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

# 🤖 AI Support Ticket Assistant

An AI-powered Support Ticket Assistant built using **n8n**, **Groq LLM**, and **Google Sheets**.

The assistant understands natural language, automatically extracts ticket IDs, searches Google Sheets, and returns accurate support ticket information in a conversational format.

---

# 🚀 Features

- 🤖 AI-powered Support Ticket Assistant
- 🔍 Search tickets using natural language
- 🎯 Automatic Ticket ID extraction
- 📄 Google Sheets integration
- ⚡ Groq LLM integration
- 🧠 AI Agent with Tool Calling
- 💬 Conversational responses
- 🔄 Real-time ticket lookup

---

# 🏗 Workflow Architecture

```text
                    User Query
                         │
                         ▼
          💬 Chat Trigger (n8n)
                         │
                         ▼
                 🤖 AI Agent
             (Groq LLM + Memory)
                         │
                         ▼
           Extract Ticket ID Automatically
                         │
                         ▼
          📄 Google Sheets Tool
                         │
                         ▼
         Search Ticket Information
                         │
                         ▼
           Generate AI Response
                         │
                         ▼
                Response to User
```

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Groq API | Large Language Model |
| Google Sheets | Ticket Database |
| AI Agent | Natural Language Processing |
| Simple Memory | Context Management |

---

# 📊 Dataset

The Google Sheet contains realistic support ticket information including:

- Ticket ID
- Customer Name
- Company
- Department
- Issue Category
- Priority
- Status
- Assigned To
- Resolution Time
- Sentiment
- AI Suggested Action

---

# 💬 Example Queries

```
Show ticket T1001

What is the status of T1005?

Who is assigned to ticket T1008?

Show details of ticket T1010.

What is the priority of ticket T1003?
```

---

# 📸 Project Screenshots

Create a folder named:

```
screenshots
```

Add these screenshots:

```
screenshots/
│
├── workflow.png
├── google-sheet.png
├── ai-chat.png
└── ai-agent.png
```

Then display them:

## Workflow

![Workflow](screenshots/workflow.png)

---

## AI Chat

![AI Chat](screenshots/ai-chat.png)

---

## Google Sheets

![Google Sheet](screenshots/google-sheet.png)

---

## AI Agent

![AI Agent](screenshots/ai-agent.png)

---

# 📂 Project Structure

```
AI-Support-Ticket-Assistant
│
├── ai-support-ticket-assistant.json
├── README.md
└── screenshots
    ├── workflow.png
    ├── ai-chat.png
    ├── google-sheet.png
    └── ai-agent.png
```

---

# ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-support-ticket-assistant.git
```

### 2. Open n8n

Import the workflow JSON file.

### 3. Configure Credentials

- Groq API Key
- Google Sheets OAuth

### 4. Execute the workflow

Open Chat and ask questions like:

```
Show ticket T1001
```

---

# 🎯 Use Cases

- Customer Support
- IT Helpdesk
- Internal Ticket Management
- AI Service Desk
- Business Process Automation

---

# ⭐ Key Highlights

✅ Built using n8n AI Agent

✅ Google Sheets Tool Calling

✅ Automatic Ticket ID Extraction

✅ Natural Language Understanding

✅ Groq LLM Integration

✅ Modular Workflow Design

✅ Easy to Extend

---

# 🔮 Future Improvements

- Search by Customer Name
- Search by Department
- Search by Company
- Search by Priority
- Create New Ticket
- Update Ticket Status
- Email Notifications
- WhatsApp Integration
- Telegram Bot
- Dashboard Analytics

---

# 👩‍💻 Author

**Divyanshi Sharma**

MBA (Artificial Intelligence & Data Science)

Passionate about AI, Data Analytics, Workflow Automation, and Intelligent Business Solutions.

---

<p align="center">

⭐ If you found this project useful, don't forget to Star this repository!

</p>
