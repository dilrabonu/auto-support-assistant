# auto-support-assistant

# 🚗 Automotive Support Assistant (Streamlit + GitHub Integration)

A fully functional AI-powered customer support tool for automotive services. Users can ask vehicle-related questions and generate real-time support tickets, which are automatically created as GitHub issues.

## 🔧 Features

- 💬 Conversational AI using LangChain and OpenAI
- 🧠 Smart ticket intent detection
- 📩 Support form for user name, email, and issue description
- 🔁 GitHub Issues Integration (via API)
- ✅ Tracks and links tickets directly to your GitHub repo

## 🌐 Live Demo

👉 [Try it now on Hugging Face Spaces](https://huggingface.co/spaces/Dilrabonu/Auto-Support-AI)

## 🛠️ Tech Stack

- Streamlit
- LangChain
- OpenAI API
- GitHub REST API
- FAISS (Document Search)
- Python (Backend)

## 📸 Preview

![App Screenshot](your_app_screenshot.png)

## 🚀 How It Works

1. User types a question or support request.
2. If a ticket is needed, a form appears.
3. After submission, an issue is auto-created in your GitHub repo.
4. The user gets confirmation + link to track.

## 📂 Project Structure

```bash
├── app.py                 # Main Streamlit app
├── github_issues.py       # GitHub API integration
├── chat_handler.py        # Chat logic & LangChain
├── document_processor.py  # FAISS index & data handling
├── data/                  # Source documents
├── requirements.txt
└── README.md
