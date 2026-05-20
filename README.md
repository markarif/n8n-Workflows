# 🤖 n8n Automation Workflows — by [@markarif](https://github.com/markarif)

> *Building intelligent systems that work while you sleep.*

---

## 👋 About This Repository

Hi, I'm **Mark** — a developer passionate about **AI-powered automation**. This repo is a curated collection of my n8n workflows that solve real-world problems using intelligent automation, smart data pipelines, and AI integrations.

Each workflow is plug-and-play — download the `.json` file and import it directly into your n8n instance.

---

## ⚡ Workflows

### 🧠 ACTS Policy Bulk Ingestion and Bot *(Smart - Skips Already Ingested)*
> Intelligently ingests policy documents in bulk while skipping duplicates already in the system — no manual checks needed.

- **Nodes used:** HTTP Request, IF, Set, Database
- **Use case:** Policy management, document automation
- 📥 [Download Workflow](./workflows/ACTS%20Policy%20Bulk%20Ingestion%20and%20Bot%20(Smart%20-%20Skips%20Already%20Ingested).json)

---

### 🩺 AI-Powered System Health Digest
> Uses AI to analyze system metrics and generate a human-readable health digest — like having a smart DevOps assistant on call.

- **Nodes used:** AI Agent, HTTP Request, Email/Slack
- **Use case:** System monitoring, ops automation
- 📥 [Download Workflow](./workflows/AI-Powered%20System%20Health%20Digest.json)

---

### 🚨 Aqua Flow Alert Notification
> Monitors AquaFlow data streams and triggers instant alert notifications when thresholds are breached.

- **Nodes used:** Webhook, IF, Slack/Email, Set
- **Use case:** Real-time monitoring, alert systems
- 📥 [Download Workflow](./workflows/Aqua%20flow%20Alert%20Notification.json)

---

### 📊 AquaFlow Weekly Summary
> Automatically compiles and sends a weekly summary report of AquaFlow activity — zero manual reporting.

- **Nodes used:** Schedule Trigger, HTTP Request, Google Sheets, Email
- **Use case:** Reporting automation, scheduled digests
- 📥 [Download Workflow](./workflows/AquaFlow%20Weekly%20Summary.json)

---

### 🛡️ Automated Incident Response System
> Detects incidents, triages severity, notifies the right people, and logs everything — all automatically.

- **Nodes used:** Webhook, AI Agent, Slack, PagerDuty, Google Sheets
- **Use case:** Incident management, DevOps automation
- 📥 [Download Workflow](./workflows/Automated%20Incident%20Response%20System.json)

---

## 🚀 How to Import Any Workflow

1. Open your n8n instance at `http://localhost:5678`
2. Go to **Workflows** in the sidebar
3. Click **Import** (top right)
4. Upload the `.json` file of your chosen workflow
5. Update any credentials (API keys, email, etc.) to match your setup
6. Hit **Activate** and you're live ✅

---

## 🛠️ Tech Stack

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📂 Repository Structure

```
n8n-workflows/
├── README.md
├── workflows/
│   ├── ACTS Policy Bulk Ingestion and Bot (Smart - Skips Already Ingested).json
│   ├── AI-Powered System Health Digest.json
│   ├── Aqua flow Alert Notification.json
│   ├── AquaFlow Weekly Summary.json
│   └── Automated Incident Response System.json
└── screenshots/
    └── (workflow screenshots)
```

---

## 🤝 Contributing

Found a bug or have an improvement? Feel free to open an issue or submit a pull request. Collaboration is welcome!

---

## 📬 Connect With Me

- 🐙 GitHub: [@markarif](https://github.com/markarif)
- 💼 Open to freelance automation projects and collaborations

---

<p align="center">
  <i>⭐ If any of these workflows helped you, consider starring the repo!</i>
</p>
