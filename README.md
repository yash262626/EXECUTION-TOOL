<div align="center">

# 📊 Execution Sales Dashboard

**A sales operations dashboard for tracking orders, dispatches and client follow-ups in one view**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Excel](https://img.shields.io/badge/Excel_Import%2FExport-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

</div>

---

## 🎯 What it does

Sales teams often track orders, factory updates and follow-ups across scattered Excel sheets. This dashboard brings them into a single page, so the daily execution status is visible at a glance and nothing slips through.

## ✨ Features

- 📈 **KPI analytics** for orders, dispatches and follow-ups
- 📊 **Interactive charts** (Chart.js) to spot delays and pending work
- 📥 **Excel / CSV import and export** (SheetJS) so existing sheets plug straight in
- 🔔 **Reminders** for pending follow-ups and upcoming deliveries
- 🗒️ **Daily updates** with factory status and remarks per project
- 🔎 **Filters** by client, status and priority
- ⚡ **Productivity tracking** for day-to-day workflow management
- 🌐 Runs entirely in the browser: no server, no install

## 🚀 Quick Start

1. Download or clone the repo.
2. Open the dashboard HTML file in any modern browser.
3. Import `kei_sample_data (2).csv` to see it in action, or import your own sheet.

## 🧾 Data Format

The import expects these columns:

| Column | Example |
|---|---|
| Date | `2026-05-29` |
| Client Name | `Mahindra Realty` |
| Project Name | `Armoured Cable` |
| Order Status | `Pending` / `In Progress` / `Completed` / `Delayed` |
| Dispatch Status | `Pending` / `Partial` / `In Transit` / `Completed` |
| Priority | `Low` / `Medium` / `High` / `Urgent` |
| Follow-up Status | `Pending` / `Done` |
| Expected Delivery | `2026-06-06` |
| Factory Update | `Production in progress` |
| Remarks | `Client follow-up pending` |

> The included CSV is **sample data** for demonstration only.

## 🗂️ Files

```
EXECUTION-TOOL/
├── kei_dashboard_fixed__4_ (1).html   # The dashboard (single file)
├── kei_sample_data (2).csv            # Sample dataset
└── README.md
```

## 🛣️ Roadmap

- [ ] Rename the HTML file to `index.html` and host on GitHub Pages
- [ ] Add screenshots of each dashboard view
- [ ] Export a formatted daily report

---

<div align="center">

Built by [Yash Dhanraj Ail](https://github.com/yash262626) · [Portfolio](https://yashail.netlify.app)

</div>
