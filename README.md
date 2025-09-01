# PLP-Hackaton-3.0-vibe-coding
# 🎭 Mood Journal – AI-Powered Emotion Tracker  

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=googlechrome)](https://ai-powered-mood-jour-8xu2.bolt.host)  

**Mood Journal** is a simple but powerful web app that lets you track your emotions through journaling.  
Powered by the **Hugging Face Sentiment Analysis API**, it gives instant feedback on your emotional state and shows trends over time with beautiful charts.  

👉 **[Visit the Mood Journal here](https://ai-powered-mood-jour-8xu2.bolt.host)**  

---

## ✨ Features
- 📝 Write daily journal entries in a clean, colorful interface  
- 🤖 AI-powered **emotion analysis** (Hugging Face Sentiment API)  
- 📊 Visualize mood trends with **interactive charts (Chart.js)**  
- 💾 Store, view, and manage your entries with **CRUD operations**  
- 🎨 Aesthetic and beginner-friendly design with multiple mood colors & emojis  

---

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Chart.js)  
- **Backend:** Python (Flask)  
- **Database:** MySQL  
- **AI:** Hugging Face Sentiment Analysis API  

---

## ⚡ How It Works
1. User writes a journal entry ✍️  
2. Flask backend stores it in MySQL 💾  
3. Text sent to Hugging Face API 🤖  
4. API returns emotion scores (e.g., Joy 72%, Sadness 18%) 🎯  
5. Mood trends displayed beautifully with Chart.js 📊  

---

## 🚀 Getting Started (Local Setup)
### Prerequisites
- Python 3.x  
- MySQL  
- Node.js (optional, for frontend package management)  

### Installation
```bash
# Clone the repo
git clone https://github.com/your-username/mood-journal.git
cd mood-journal

# Install dependencies
pip install -r requirements.txt
