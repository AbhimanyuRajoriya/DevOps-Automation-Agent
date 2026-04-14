# Multi-Agent DevOps Automation (n8n)

## 🚀 Overview
Automates CI/CD issue detection and fix suggestion using AI agents.

## ⚙️ Features
- Webhook trigger from GitHub
- Log analysis using OpenAI Chat
- JSON-based structured output
- Automated fix suggestions
- Controlled PR workflow (no unsafe edits)

## 🧠 Architecture
Webhook → Parser → AI Agent → Validator → Action

## 📂 Files
- Devops Automation Agent.json → import into n8n

## 🛠 Setup
1. Import workflow.json into n8n
2. Add credentials (GitHub, Gemini)
3. Trigger via webhook

## ⚠️ Note
This project was originally built on n8n cloud trial and later exported for portability.

## 🔐 Security
Credentials and internal IDs are redacted.  
Add your own credentials in n8n before running the workflow.
