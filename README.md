# JanmaBhoomi
# 🇮🇳 JanmaBhoomi — Discover the Soul of India, One Place at a Time

What if every village, every town, every forgotten street in India could tell its story?

**JanmaBhoomi** is a simple AI-powered web app that lets users explore **historical, cultural, and local facts** about any Indian place — in their own language.

> 🚀 Built during WikiVerse Hackathon 2025 | Currently in early development

---

## 👥 Team Members

| Name                 | Role       | GitLab Username         |
|----------------------|------------|------------------------ |
| KODATI VENKAT SURYA  | Developer  | @VenkatSurya            |
| Gursidak Singh Bassi | Developer  | @Gursidak               |
| Himanshu Mishra      | Developer  | @Himanshumishra         |
| Abhishek Reddy Yasa  | Developer  | @AbhishekReddyYasa      |

---

## 🧠 The Big Idea

India has over 6 lakh villages — many don’t even have a digital page.

There’s a ton of open data on Wikipedia and Wikidata — but it's not easy to access, especially in Indian languages. So, we built **JanmaBhoomi** to bring that data together, summarize it using AI, and show it in local languages like Telugu, Hindi, Bengali, and more.

---

## 🔍 What the App Can Do

- 🔎 Search any Indian place (e.g. Kurnool, Jodhpur)
- 🧠 See a simple summary of history/culture using AI
- 🖼️ View related images from Wikimedia Commons
- 🌐 Choose your preferred Indian language
- 💬 Ask basic questions in your native tongue *(coming soon)*
- 📤 Share cultural "Knowledge Cards" *(coming soon)*

---

## 🏗️ Tech Used (Simple Version)

We used basic tools that are beginner-friendly and meet the hackathon rules:

- 🐍 **Python** – for all backend and app logic
- 📦 **uv** – to manage Python environment and packages
- 🧠 **Hugging Face** – for AI summarization and translation
- 🌐 **Wikimedia APIs** – for facts, images, data
- 🖥️ **Streamlit** – to quickly build and demo the app interface

📌 The final plan is to shift this to a proper **API-based backend** using FastAPI + React for frontend (as required by the rules).

---

## ⚙️ How to Run (Locally)

```bash
# Setup environment
uv venv
uv pip install -r requirements.txt

# Run the app
streamlit run app.py

