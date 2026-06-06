# 🤖 Gemini Chatbot Python

A simple AI-powered chatbot built using Google's Gemini API and Python. This project demonstrates how to integrate Gemini AI into Python applications to create an interactive conversational assistant.

## 🚀 Features

* 💬 Interactive chatbot interface
* 🤖 Powered by Google Gemini AI
* 🔑 Secure API key management using `.env`
* 📝 Clean and beginner-friendly code
* ⚡ Fast response generation
* 🐍 Built with Python

## 📂 Project Structure

```bash
gemini-chatbot-python/
│
├── gemini_client.py
├── .env
├── requirements.txt
├── README.md
└── .gitignore
```

## 🛠️ Tech Stack

* Python 3.x
* Google Gemini API
* python-dotenv

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Ronit049/gemini-chatbot-python.git
cd gemini-chatbot-python
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 🔑 Set Up Gemini API Key

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_api_key_here
```

Get your API key from Google AI Studio.

## ▶️ Run the Chatbot

```bash
python gemini_client.py
```

## 💻 Example

```text
You: Hello
Gemini: Hi! How can I help you today?

You: Explain Python in simple words.
Gemini: Python is an easy-to-read programming language...
```

## 📜 Requirements

```txt
google-genai
python-dotenv
```

## 🔒 Security Note

Never commit your API key to GitHub.

Add the following to `.gitignore`:

```gitignore
.env
venv/
__pycache__/
```

## 🎯 Learning Outcomes

By building this project, you will learn:

* Working with APIs in Python
* Environment variable management
* AI chatbot development
* Prompt-response workflows
* Python project structure

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

## 📄 License

This project is licensed under the MIT License.
