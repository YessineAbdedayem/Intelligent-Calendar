
# 🗓️ Smart Calendar

An **AI-powered intelligent calendar** that helps organize meetings, manage tasks, and optimize schedules.  
It uses **LLMs (Groq API)** + **embeddings (Sentence Transformers + FAISS)** to understand natural language requests like:

> "Schedule a meeting with Mariam tomorrow at 9pm"  
> "Show me meetings this week"  
> "Cancel meeting meeting-123"

---

## 🚀 Features
- 📅 Add, update, and delete meetings
- 🤖 Natural language understanding for scheduling
- 🔍 Smart search with embeddings (FAISS + Sentence Transformers)
- 🕒 Handles relative time ("tomorrow", "this morning", "next Thursday")
- 🖥️ Simple desktop GUI (Tkinter)

---

## 🛠️ Tech Stack
- **Python 3**
- **Groq API** (LLM-based intent understanding)
- **Sentence Transformers** (embeddings)
- **FAISS** (vector search engine)
- **Tkinter** (GUI)

---

## 📦 Installation

Clone the repository:
```bash
git clone https://github.com/YessineAbdedayem/smart-calendar.git
cd smart-calendar
pip install -r requirements.txt
