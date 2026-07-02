# وافيّة — Wafiya 💳

> منصة إدارة مالية ذكية | Smart Personal Finance Management Platform

![HTML](https://img.shields.io/badge/HTML5-Single%20File-f08a6c?style=flat-square)
![No Backend](https://img.shields.io/badge/Backend-None-7fd1ae?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-a78bfa?style=flat-square)

---

## 🌐 Live Demo
Deploy instantly → drag the folder to [netlify.com/drop](https://app.netlify.com/drop)

---

## ✨ Features

- **3 ways to onboard** — manual entry, fake bank connect, or CSV upload
- **Virtual wallets** — auto-split salary into commitments / bills / daily spending
- **Live charts** — donut, bar, and line charts powered by Chart.js
- **Bill management** — mock checkout payment flow
- **Payment schedule** — auto-generated from your commitments
- **Multi-user** — multiple accounts stored locally per browser
- **Navy → purple glassmorphism** design

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/wafiya.git
cd wafiya

# 2. Run local server
python -m http.server 8000

# 3. Open in browser
# http://localhost:8000
```

> ⚠️ Always open via `localhost:8000` — not by double-clicking the file.  
> localStorage is origin-scoped, so mixing file:// and http:// will lose your data.

---

## 📁 Structure

```
wafiya/
├── index.html   # The entire app — HTML + CSS + JS in one file
└── README.md
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 + CSS3 | Structure, CSS variables, glassmorphism |
| Vanilla JavaScript | All logic — no frameworks |
| Chart.js 4.4.1 | Data visualization (CDN) |
| Tabler Icons 3.10 | Icons (CDN) |
| localStorage API | User data persistence |

---

## 📊 Data Input Modes

### 1. يدوي — Manual
Enter salary + choose commitments + adjust ratio sliders.

### 2. ربط بنكي — Fake Bank Connect
Select Alinma Bank or Other → animated connection flow → auto-generated commitments based on income ratios.

### 3. رفع CSV — CSV Upload
Upload a transaction file from your banking app → system auto-categorizes (rent, electricity, car payment...) → dashboard built from real data.

---

## 🎨 Design

- Background: `linear-gradient(160deg, #161a35 → #2b2454 → #5b4a8a → #7a5fa8)`
- Cards: `rgba(255,255,255, .06–.12)` with `backdrop-filter: blur()`
- Accent: Lavender `#a78bfa` | Coral `#f08a6c` | Amber `#e0a45c` | Teal `#7fd1ae`

---

## 📝 License

MIT — free to use, modify, and distribute.

---


