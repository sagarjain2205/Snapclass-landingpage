<div align="center">

<img src="static/img/app_logo.png" alt="SnapClass Logo" width="80"/>

# SnapClass — AI Powered Attendance System

**Next-gen classroom attendance using Face Recognition & Voice Biometrics**

[![🌐 Landing Page](https://img.shields.io/badge/🌐%20Landing%20Page-Visit%20Now-00C7B7?style=for-the-badge&logo=vercel)](https://snapclass-landingpage-mu.vercel.app)

[![🚀 Live Website](https://img.shields.io/badge/🚀%20Live%20Website-snapclass-5865F2?style=for-the-badge&logoColor=white)](https://snapclassattendance.streamlit.app)
[![📂 Main Project Repo](https://img.shields.io/badge/📂%20Main%20Repo-SnapClass-black?style=for-the-badge&logo=github)](https://github.com/sagarjain2205/SnapClass)
---

</div>

## 📌 About

SnapClass is an AI-powered attendance system built for modern classrooms. Teachers can take attendance in seconds using a single class photo or a sequential voice roll-call — no manual entry, no hassle.

This repo contains the **landing page** for SnapClass — built with plain HTML, CSS, and JS, served via Flask.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📸 **AI Face Analysis** | Detects every student from a single class photo using computer vision |
| 🎙️ **Voice ID Roll-call** | Matches student voice biometrics in real-time using Resemblyzer |
| 📱 **QR-Driven Enrollment** | Students join courses instantly via unique QR codes |
| ☁️ **Supabase Cloud** | Real-time PostgreSQL with secure auth and file sync |

---

## 🛠️ Tech Stack

**Landing Page**
- HTML5, CSS3, Vanilla JS
- Flask (serves templates + static files)
- Climate Crisis + Outfit (Google Fonts)

**Main App** *(see main repo)*
- Streamlit frontend
- Flask backend
- FaceRecognition + Dlib (Face AI)
- Resemblyzer + Librosa (Voice AI)
- Supabase (PostgreSQL + Storage)

---

## 📁 Folder Structure

```
project/
├── templates/
│   └── index.html          # Landing page HTML
├── static/
│   ├── css/
│   │   └── style.css       # All styles + dark theme
│   ├── js/
│   │   └── script.js       # Scroll reveal animations
│   ├── fonts/
│   │   └── chison.ttf      # Custom font (optional)
│   └── img/
│       ├── app_logo.png
│       └── demo/           # Screenshot images used in journey sections
└── app.py                  # Flask entry point
```

---

## 🚀 Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/sagarjain2205/SnapClass
cd SnapClass

# 2. Install Flask
pip install flask

# 3. Run
python app.py
```

Then open `http://localhost:5000` in your browser.

---

## 🔗 Links

| | |
|---|---|
| 🌐 **Live App** | [snapclassattendance.stramlit.app](https://snapclassattendance.streamlit.app) |
| 💻 **Main Repo** | [github.com/sagarjain2205/SnapClass](https://github.com/sagarjain2205/SnapClass) |
| 🖥️ **Landing Page** | [snapclass-landingpage-mu.vercel.app](https://snapclass-landingpage-mu.vercel.app) |
| 👤 **Developer** | [Sagar Jain](https://github.com/sagarjain2205) |

---

<div align="center">

Built with ❤️ by **Sagar Jain**

</div>
