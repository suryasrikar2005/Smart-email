# 🧠 Smart Email Assistant (AI-Powered Gmail Reply Generator)

### 🚀 Overview
Smart Email Assistant is a Chrome Extension integrated with Gmail that automatically generates **AI-based professional replies** using the **Google Gemini API**.  
It saves time, enhances productivity, and helps users craft polished responses instantly — all without leaving Gmail.

---

## 🧩 Problem Statement
Writing professional emails is repetitive and time-consuming.  
Users often struggle to maintain tone, clarity, and consistency while replying to multiple emails daily.

---

## 💡 Solution
The Smart Email Assistant integrates an **AI Reply button** directly into Gmail’s compose window.  
When clicked, it:
1. Captures the current email content.
2. Sends it to a **Spring Boot backend**.
3. The backend calls the **Gemini API** to generate a relevant, professional reply.
4. The generated text is automatically inserted back into Gmail’s reply box — ready to send.

---

## ⚙️ Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend (Extension)** | JavaScript, HTML, CSS |
| **Backend** | Spring Boot (Java) |
| **AI Model** | Google Gemini API |
| **Communication** | REST API (JSON) |
| **Browser API** | Chrome Extension Manifest V3, MutationObserver |
| **Testing Environment** | Localhost (for backend), Gmail Web Interface |
