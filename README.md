# ChatBotWith_N8N
# 🚀 AI-Powered Career Information Bot (n8n Automation)

A smart, AI-driven automation workflow built with n8n that captures career-related links (Jobs, Courses, Internships) from Telegram groups, analyzes them using LLMs, and stores the organized data into Google Sheets.

## 📸 Workflow Overview
*Visual representation of the n8n automation pipeline.*
![n8n Workflow](assets/workflow_main.png)

## ✨ Key Features
- **Intelligent Link Extraction:** Automatically identifies URLs from Telegram messages using AI (Groq/Llama 3.1).
- **Automated Data Entry:** Categorizes information (Job, Course, or Info) and saves it directly to Google Sheets.
- **User-Specific Memory:** Remembers the last 25-30 interactions for each user to provide personalized context.
- **Conversational AI:** Responds to greetings and career-related queries in a friendly, concise manner.
- **Multi-Source Logic:** If information isn't in the database, the AI provides verified info from online sources.

## 🛠️ Technology Stack
- **Automation Tool:** [n8n](https://n8n.io)
- **AI Model Provider:** Groq (Llama 3.1 70B Engine)
- **Database:** Google Sheets
- **Interface:** Telegram Bot API

## 📂 Repository Structure
- `workflow.json`: The complete n8n workflow file (ready for import).
- `assets/`: Contains screenshots of the n8n nodes, Telegram group interaction, and the Excel/Google Sheets database.

## 🚀 How to Setup
1. **Import Workflow:** Open your n8n dashboard and select `Import from File`. Upload the `.json` file from this repo.
2. **Configure Credentials:**
   - **Telegram:** Add your Bot API token from [@BotFather](https://t.me).
   - **Groq:** Add your API Key from [Groq Console](https://groq.com).
   - **Google Sheets:** Connect your Google account and select your designated spreadsheet.
3. **Set Active:** Save the workflow and toggle the `Active` button to live mode.

## 📊 Live Previews


| Telegram Interaction | Google Sheets Database |
|---|---|
| ![Telegram Bot](assets/telegram_ss.png) | ![Excel Spreadsheet](assets/excel_ss.png) |

## 🤝 Contributing
Feel free to fork this repository, open issues, or submit pull requests to improve the bot's logic or add new features.

---
**Developed with ❤️ by [Your Name]**
