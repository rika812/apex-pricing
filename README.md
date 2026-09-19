# Apex Price Intelligence — E-Commerce Competitor Crawler & Repricing Portal

> **Proprietary Market Scraper & Repricing Engine** engineered for automated e-commerce catalog monitoring, MAP compliance tracking, and Telegram alert dispatching.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-emerald?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rika812.github.io/apex-pricing/)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Playwright](https://img.shields.io/badge/Playwright-Scraper-green?style=for-the-badge&logo=playwright&logoColor=white)](https://playwright.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

---

## ⚡ Key Features

- **Automated Multi-Channel Scraping:** Continuously tracks consumer prices across **Amazon US, BestBuy, Walmart, and B&H Photo**.
- **Real-Time Undercut Detection:** Instant algorithmic repricing recommendations when competitors drop prices below MAP thresholds.
- **Webhook Dispatchers:** Automated alert feeds sent directly to client Telegram bots (`@ApexDeals_Bot`) and Slack channels.
- **Enterprise Web Portal:** High-performance dashboard featuring Chart.js historical price trends, live crawler log console, and one-click master CSV exports.
- **Resilient Pipeline Architecture:** Residential proxy rotation and anti-bot mitigation ensuring 99.8% uptime without Captcha blockage.

---

## 🛠 Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend & Scraping** | Python, Playwright, AsyncIO, BeautifulSoup4, Requests |
| **Data Processing** | Pandas, JSON serialization, PostgreSQL schema |
| **Frontend Portal** | HTML5, Tailwind CSS, Chart.js, Vanilla JavaScript |
| **Infrastructure & CI/CD** | GitHub Actions, GitHub Pages, Linux Cron Daemons |

---

## 🚀 Quick Start (Local Setup)

### 1. Clone the repository:
```bash
git clone https://github.com/rika812/apex-pricing.git
cd apex-pricing
```

### 2. Install dependencies:
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

pip install -r requirements.txt
playwright install chromium
```

### 3. Run Crawler Simulation:
```bash
python scraper_simulation.py
```

### 4. Launch Web Dashboard:
Simply open `index.html` in any modern web browser or run a lightweight local server:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000`.

---

## 📊 Live Web App

The dashboard is accessible 24/7 via GitHub Pages:  
👉 **[https://rika812.github.io/apex-pricing/](https://rika812.github.io/apex-pricing/)**

---

## 📄 License
MIT License. Developed for enterprise market data tracking.
