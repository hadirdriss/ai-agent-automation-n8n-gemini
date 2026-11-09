# 🤖 AI Agent Automation — Gemini, Gmail & Google Sheets

## 📌 Overview

This project demonstrates the development of an **AI-powered conversational agent using n8n**, Google Gemini, Gmail, and Google Sheets.

The agent processes incoming chat messages, generates contextual responses using conversational memory, logs interactions in Google Sheets, and sends emails through Gmail.

The workflow combines generative AI, workflow automation, and Google services to build an intelligent assistant.

## ✨ Features

- 💬 **Conversational AI Agent** — Processes incoming messages through an n8n chat interface.
- 🧠 **AI-powered Responses** — Generates contextual responses using Google Gemini 2.5 Flash.
- 🗂️ **Conversational Memory** — Maintains conversation context using Simple Memory.
- 📊 **Automated Logging** — Stores user messages and AI responses in Google Sheets.
- 📧 **Email Automation** — Generates and sends emails through Gmail.
- 🔄 **Workflow Orchestration** — Connects AI and external services using n8n.

## 🏗️ Workflow Architecture

The workflow follows these steps:

1. Receive an incoming message through the n8n Chat Trigger.
2. Forward the message to the AI Agent.
3. Process the request and generate a response using Google Gemini.
4. Retrieve conversational context from Simple Memory.
5. Append the interaction to Google Sheets.
6. Send emails through Gmail when required.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation and orchestration |
| Google Gemini 2.5 Flash | Large Language Model (LLM) |
| LangChain | AI agent framework integration |
| Simple Memory | Conversational context management |
| Google Sheets API | Interaction logging and storage |
| Gmail API | Automated email sending |

## 📁 Project Structure

```text
AI-Agent-Automation/
├── README.md
├── workflow/
│   └── AI_Agent_Automation.json
└── screenshots/
    └── workflow.png
```

## ⚙️ Setup & Installation

### Prerequisites

- An n8n instance (cloud or self-hosted)
- A Google account
- Google Gemini API access
- A Google Sheet for storing interactions
- Gmail configured in n8n

### Configuration

1. Import the workflow JSON file into n8n.
2. Configure your Google Gemini credentials.
3. Connect Google Sheets using OAuth2.
4. Configure Gmail credentials.
5. Set up your Google Sheet with the following columns:

   - `timestamp`
   - `session_id`
   - `user_message`
   - `assistant_response`

6. Review the workflow configuration.
7. Activate the workflow and test the conversational agent.

## 🔐 Security

- Never commit API keys, OAuth tokens, or credentials to GitHub.
- Remove personal Google Sheet IDs before publishing.
- Configure credentials securely through n8n.
- Review workflow settings before making the project public.

## 🎯 Project Goals

This project showcases practical skills in:

- AI Agent Development
- Generative AI Integration
- Workflow Automation
- API Integration
- Conversational Memory
- Google Workspace Automation

## 🚀 Future Improvements

- Add a human approval step before sending emails.
- Integrate additional AI tools and APIs.
- Improve error handling and logging.
- Implement long-term conversational memory.
- Add a web-based chatbot interface.

## 👨‍💻 Author

Developed as a portfolio project focused on **AI automation, generative AI, and API integration**.



