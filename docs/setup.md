# 🧩 Development Setup Guide

**Course:** Building AI-Powered Applications  
**Team Name:** Nexus  
**Project Title:** Smart Student Deals & Hangout Finder  
**Date:** October 2025

## ⚙️ Prerequisites

Before you begin, make sure you have these tools installed:

| Tool | Version | Purpose |
|------|---------|---------|
| Python | 3.11+ | For backend scripts (placeholder) |
| Node.js | 18+ | For frontend or API |
| npm | 9+ | Node package manager |
| Git | 2.30+ | For cloning and collaboration |
| (Optional) VS Code | Latest | Recommended editor |

All tools can be downloaded from their official websites.  
💡 **No paid services are required.**

## 🛠️ Installation Steps

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/DM5757/Nexus.git
cd nexus
```

Or download it as a ZIP file from GitHub and extract it manually.

### 2️⃣ Set Up a Virtual Environment (Optional but Recommended)

If you're using Python for backend scripts:

```bash
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows
```

Then install dependencies (if any are added later):

```bash
pip install -r requirements.txt
```

For JavaScript/Node.js (future use):

```bash
cd src
npm init -y
```

### 3️⃣ Environment Variables

This repo includes an example environment file:

```
.env.example
```

To create your own local `.env` file:

```bash
cp .env.example .env
```

For now, these are placeholder values — you can edit them later when adding API keys or database credentials.

## ▶️ Running the Application

At this stage, the project contains no active code yet, but you can confirm your environment setup works.

### ✅ Python Test

```bash
python -c "print('Hello, Nexus Team! Setup successful 🚀')"
```

**Expected output:**
```
Hello, Nexus Team! Setup successful 🚀
```

### ✅ Node.js Test

```bash
node -e "console.log('Hello, Nexus Team! Setup successful 🚀')"
```

Both confirm your system is ready for development.

## 🧰 Troubleshooting

| Problem | Possible Cause | Solution |
|---------|----------------|----------|
| git not recognized | Git not installed | Install Git and restart your terminal |
| python command not found | Python not added to PATH | Reinstall Python with "Add to PATH" checked |
| npm not found | Node.js not installed | Download from nodejs.org |
| Permission denied | Missing admin rights | Re-run terminal as administrator |
| .env file missing | Forgot to copy example file | Run `cp .env.example .env` again |