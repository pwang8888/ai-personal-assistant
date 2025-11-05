# 🤖 AI Personal Chat Assistant

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4-orange.svg)](https://openai.com/)
[![Gradio](https://img.shields.io/badge/Gradio-UI-red.svg)](https://gradio.app/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

AI chatbot that acts as my digital representative, engaging with website visitors 24/7 and answering questions about my professional background.

---

## 🎯 Why I Built This

When potential employers visit my website at 2 AM, there's no way to engage with them. This AI agent solves that by answering questions about my background, capturing visitor emails, and sending me instant notifications.

## ✨ Features

- 💬 Natural conversations using GPT-4
- 📱 Automatic lead capture with Pushover notifications
- 📄 Dynamic context from LinkedIn PDF
- 🎓 Records unanswered questions
- 🚀 Deployed on Hugging Face

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/pwang8888/ai-personal-assistant.git
cd ai-personal-assistant
pip install -r requirements.txt
```

### Setup

1. Copy `.env.example` to `.env`
2. Add your API keys
3. Add `me/linkedin.pdf` and `me/summary.txt`
4. Run: `python app.py`

## 📊 Results

- 12+ leads captured from night visitors
- 8 FAQ items identified
- Zero missed opportunities

## 🛠️ Tech Stack

- OpenAI GPT-4o-mini
- Gradio
- PyPDF
- Pushover API
