# 🤖 Android Developer Job Hunting Agent — n8n

An autonomous AI-powered job hunting workflow built with n8n that automatically searches, scores, and sends job opportunities for Android Developers every morning.

## ✨ What It Does

- 🔍 Searches for Android/Kotlin/Jetpack Compose jobs every morning at 9 AM
- 🧠 Scores each job against your profile (skills, experience, location)
- ✉️ Generates custom cover letters for 70%+ matches
- 📧 Sends instant email notifications with job details
- 📊 Daily summary report at 7 PM
- 📋 Logs everything in Google Sheets automatically

## 🛠️ Tech Stack (All Free)

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation |
| OpenRouter AI | AI models (free tier) |
| SerpAPI | Google Search |
| Gmail | Email notifications |
| Google Sheets | Job tracking |

## 🚀 Setup Guide

### Step 1 — Create Accounts (All Free)
- [n8n.io](https://n8n.io) — free 14 day trial
- [openrouter.ai](https://openrouter.ai) — free AI models
- [serpapi.com](https://serpapi.com) — 250 free searches/month

### Step 2 — Get API Keys
- OpenRouter → Dashboard → API Keys
- SerpAPI → Dashboard → API Key

### Step 3 — Import Workflow
1. Download `workflow.json`
2. Open n8n → New Workflow
3. Click "..." → Import
4. Upload the JSON file

### Step 4 — Connect Credentials
- Gmail → Sign in with Google
- Google Sheets → Sign in with Google
- OpenRouter → Add API key
- SerpAPI → Add API key

### Step 5 — Update Your Profile
Open `Job Search Agent` node and update:
Name: Your Name
Skills: Your Skills
Experience: X years
Location: Remote/Your City
Email: your@email.com

### Step 6 — Publish & Activate
Click Publish → Done! Agent runs every morning at 9 AM.

## 📸 Screenshots

<img width="2358" height="880" alt="Screenshot 2026-04-28 at 10 28 01 AM" src="https://github.com/user-attachments/assets/9d74abde-cbd9-4ec6-8d19-4db9b3345c4b" />

<img width="1524" height="502" alt="Screenshot 2026-04-28 at 1 54 03 PM" src="https://github.com/user-attachments/assets/bfca47c7-cd5d-4891-b718-17dccaf1dfe4" />

<img width="2489" height="1138" alt="Screenshot 2026-04-28 at 10 30 20 AM" src="https://github.com/user-attachments/assets/d77fe67e-42d4-4c30-9e6b-be206295112b" />

<img width="1100" height="636" alt="Screenshot 2026-04-28 at 10 56 52 AM" src="https://github.com/user-attachments/assets/80d6e284-ff49-4a1e-a543-6ce08d2dd2d4" />



## 🎯 Results

- Finds 5-10 relevant jobs daily
- Generates personalized cover letters
- Saves 2-3 hours of manual job searching daily

## 👨‍💻 Built By

**Fardeel Azhar** — Android Developer
- GitHub: [ChFardeelAzhar](https://github.com/ChFardeelAzhar)
- LinkedIn: [fardeel-azhar](https://linkedin.com/in/fardeel-azhar-540a7033b)

## ⭐ If this helped you, please star the repo!
