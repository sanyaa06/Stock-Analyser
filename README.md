# 📊 Stock Analyser AI

> An end-to-end AI-powered stock portfolio monitoring and reporting system built using **n8n**, **Gemini AI**, **Google Sheets**, **Yahoo Finance**, **QuickChart**, and **Gmail**.

![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![Gemini](https://img.shields.io/badge/Gemini-AI-blue)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-green)
![Yahoo Finance](https://img.shields.io/badge/Yahoo-Finance-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 🚀 Overview

Stock Analyser AI is a fully automated portfolio intelligence system that tracks stocks from a Google Sheets watchlist, fetches live market prices, maintains historical data, generates AI-powered portfolio insights, summarizes overall market conditions, and delivers a professional HTML dashboard directly to your inbox every day.

---

# ✨ Features

## 📈 Portfolio Monitoring

- Track unlimited stocks
- Google Sheets watchlist
- Automatic price updates
- Historical price logging

---

## 🤖 AI Portfolio Analysis

- Executive summary
- Portfolio health score
- Best performer
- Weakest performer
- Company-wise insights
- Risk alerts
- Tomorrow's watchlist

---

## 🌍 Market Intelligence

- Overall market sentiment
- NIFTY 50 analysis
- Market outlook
- Risk assessment

---

## 📊 Interactive Dashboard

- KPI cards
- Portfolio performance table
- Dynamic QuickChart graphs
- HTML email report

---

## ⚙️ Automation

- Daily scheduled execution
- Fully automated workflow
- Gmail delivery
- Zero manual intervention

---

# 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| Workflow Automation | n8n |
| AI | Google Gemini |
| Stock Data | Yahoo Finance |
| Database | Google Sheets |
| Charts | QuickChart |
| Email | Gmail |
| Scheduling | n8n Schedule Trigger |

---

# 📂 Repository Structure

```
Stock-Analyser/
│
├── README.md
├── LICENSE
├── .gitignore
├── .env.example
│
├── workflow/
│     └── stock-analyser-workflow.json
│
├── screenshots/
│
└── docs/
```

---

# 🔄 Workflow

```
Google Sheets
        │
        ▼
Schedule Trigger
        │
        ▼
Read Watchlist
        │
        ▼
Yahoo Finance API
        │
        ▼
Update Portfolio
        │
        ▼
Store History
        │
        ▼
Generate Dashboard
        │
 ┌──────┴─────────┐
 ▼                ▼
Portfolio AI   Market AI
        │
        ▼
Generate HTML Report
        │
        ▼
Send Gmail Report
```

---

# ⚡ Setup

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Stock-Analyser.git
```

---

## 2. Import Workflow

Import

```
workflow/stock-analyser-workflow.json
```

into n8n.

---

## 3. Configure Credentials

- Google Sheets
- Gmail
- Gemini API

---

## 4. Update Configuration

Replace:

- Google Sheet IDs
- Gmail account
- Gemini API key

---

## 5. Activate Workflow

Enable the schedule trigger.

---

# 📧 Sample Report

The generated report includes:

- Portfolio dashboard
- AI portfolio summary
- Overall market summary
- Company performance table
- Daily charts
- Tomorrow's watchlist

---

# 🔮 Future Improvements

- Multiple market indices
- Sector performance
- Market news integration
- Candlestick charts
- Technical indicators
- Telegram/Slack notifications
- Web dashboard
- Mobile application

---

# 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to fork the repository and open a Pull Request.

---

# 📄 License

Licensed under the MIT License.

---

# 👨‍💻 Author

**Sanya Srivastava**

If you found this project useful, consider ⭐ starring the repository.
