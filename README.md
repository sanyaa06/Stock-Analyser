# 📈 Stock Analyser AI

> An AI-powered stock portfolio monitoring system built with **n8n**, **Google Sheets**, **Yahoo Finance**, **Gemini AI**, **QuickChart**, and **Gmail**.

Automatically tracks stocks from a watchlist, maintains historical market data, generates AI-powered portfolio insights, summarizes market conditions, and emails a professional dashboard every day.

---

## ✨ Features

### 📊 Watchlist Management
- Track unlimited stocks using Google Sheets
- Easy addition/removal of companies
- Automatic portfolio updates

### 📈 Live Price Monitoring
- Fetches live prices from Yahoo Finance
- Calculates daily price changes
- Updates portfolio automatically
- Maintains historical price logs

### 🤖 AI Portfolio Analysis
- Executive portfolio summary
- Portfolio health analysis
- Best & worst performers
- Company-wise insights
- Risk alerts
- Tomorrow's watchlist

### 🌍 Market Intelligence
- Overall market sentiment
- NIFTY 50 analysis
- Market outlook
- AI-generated market summary

### 📧 Automated Reporting
- Professional HTML dashboard
- Portfolio KPI cards
- Performance charts
- Company performance table
- AI insights delivered via Gmail

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Automation | n8n |
| AI | Google Gemini |
| Market Data | Yahoo Finance |
| Database | Google Sheets |
| Charts | QuickChart |
| Email | Gmail |

---

# 📂 Repository Structure

```text
Stock-Analyser/
│
├── README.md
├── LICENSE
├── .gitignore
├── .env.example
│
├── workflow/
│   ├── sheet-updater-workflow.json
│   └── daily-report-workflow.json
│
├── screenshots/
│
└── docs/
```

---

# 🔄 Workflow Architecture

## Workflow 1 — Live Portfolio Updater

Runs on a schedule and continuously updates the portfolio.

```text
Schedule Trigger
      │
      ▼
Read Watchlist (Google Sheets)
      │
      ▼
Yahoo Finance API
      │
      ▼
Calculate Price Change
      │
      ▼
Update Watchlist
      │
      ▼
Append Historical Data
```

### Responsibilities

- Read tracked companies
- Fetch latest prices
- Calculate change %
- Update watchlist
- Store historical records

---

## Workflow 2 — Daily AI Report

Runs once every day and generates a complete portfolio report.

```text
Schedule Trigger
      │
      ▼
Read History Sheet
      │
      ▼
Generate Portfolio Metrics
      │
      ▼
Generate Charts
      │
      ▼
Portfolio AI Analysis
      │
      ▼
Market AI Summary
      │
      ▼
Generate HTML Dashboard
      │
      ▼
Send Gmail Report
```

### Responsibilities

- Read portfolio history
- Build dashboard metrics
- Generate charts
- Create AI portfolio analysis
- Generate market summary
- Email daily report

---

# 🚀 Setup

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Stock-Analyser.git
```

---

## 2. Import Workflows

Import both workflows into n8n:

```
workflow/sheet-updater-workflow.json
workflow/daily-report-workflow.json
```

---

## 3. Configure Credentials

Connect:

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

## 5. Activate Workflows

Activate:

- ✅ Sheet Updater Workflow
- ✅ Daily Report Workflow

---

# 📧 Generated Report

Each report includes:

- 📊 Portfolio dashboard
- 📈 Daily performance chart
- 🤖 AI portfolio analysis
- 🌍 Overall market summary
- 📋 Company performance table
- 🎯 Tomorrow's watchlist

---

# 🔮 Future Improvements

- Multiple market indices
- Sector performance analysis
- Financial news integration
- Telegram & Slack notifications
- Technical indicators
- React dashboard
- Portfolio performance trends

---

# 🤝 Contributing

Contributions, feature requests, and suggestions are welcome.

Fork the repository and submit a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Sanya Srivastava**

If you found this project useful, consider giving it a ⭐ on GitHub!
