# 🤖 ToLearnChatbot

An AI-powered Student Assistant built with Streamlit and Google Gemini AI.

This chatbot helps students:

- Learn concepts
- Ask questions
- Analyze PDFs
- Analyze Images
- Use Voice Input
- Save Chat History
- Interact with AI through a modern interface

---

## 🚀 Features

### 💬 AI Chat Assistant

- Powered by Google Gemini AI
- Answers academic and general questions
- Maintains conversation history

### 🔐 Secure Login System

- Username and Password Authentication
- Credentials stored using environment variables

### 🎤 Voice Input

- Speech-to-text support

### 📂 File Upload Support

- PDF Analysis
- Image Analysis

### 💾 Chat History

- Save conversations
- Load previous chats
- Delete saved chats

---

## 📁 Project Structure

```text
ToLearnChatbot/
│
├── app.py
├── auth.py
├── chat_manager.py
├── file_processor.py
├── speech_utils.py
├── requirements.txt
├── uploads/
├── saved_chats/
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/amankprajith-star/ToLearnChatbot.git
cd ToLearnChatbot
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Create Environment Variables

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key

APP_USERNAME=admin
APP_PASSWORD=1234
```

### Run Application

```bash
streamlit run app.py
```

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini AI
- SpeechRecognition
- PyPDF2
- Pillow
- dotenv

---

## 🎯 Learning Outcomes

This project helped me learn:

- Python Development
- Streamlit Framework
- API Integration
- Environment Variables
- Git & GitHub
- File Handling
- Voice Processing
- AI Application Development

---

## 👨‍💻 Author

**Aman Prajith**

B.Tech Artificial Intelligence & Data Science

GitHub:
https://github.com/amankprajith-star
