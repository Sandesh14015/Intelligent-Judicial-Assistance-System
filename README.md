# ⚖️ IJAS — Intelligent Judicial Assistance System

> **"Current systems provide information. Our system provides actionable guidance and decision support."**


[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## Project Overview

India's judicial digital ecosystem — eCourts, NJDG, eFiling, Tele-Law — is fragmented. Citizens, especially from rural or underprivileged backgrounds, struggle to navigate case status tracking, eFiling procedures, and legal aid access.

**IJAS** is a single intelligent entry point to India's entire judicial digital ecosystem — not just a FAQ bot, but a system that *guides, assists, and simplifies justice.*

---

##  Key Features

### ✅ Core
| Feature | Description |
|---|---|
| 🤖 AI Chatbot (NLP) | Understands natural language queries in English & Hindi |
| 📋 Case Status Checker | Look up current stage, next steps, and expected timeline |
| 📁 eFiling Guidance | Step-by-step help with document submission |
| 🚦 Traffic Fine Assistant | Challan lookup and payment walkthrough |

### 🔥 Innovations
| Feature | Description |
|---|---|
| 🧭 Smart Case Navigator | "What should I do next?" — proactive legal guidance |
| 📊 NJDG Data Visualizer | Graphs, court-wise comparisons, state-wise case load |
| 🖐️ "Do It For Me" Mode | Step-by-step assistant with auto-fill demo & direct portal links |
| 🎯 Intent-Based Smart Routing | Detects language + intent from messy/Hindi input automatically |
| 🆘 Legal Aid Mode | Suggests Tele-Law services and free legal aid for those who can't afford a lawyer |
| 🎤 Voice-Based Assistant | Speak your query — get voice + text response (accessibility-first) |
| 👍 Feedback Learning System | Thumbs up/down on answers to simulate reinforcement learning improvement |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────┐
│                    User Interface                    │
│         (Web App + Voice Input + Chatbot UI)         │
└───────────────────┬─────────────────────────────────┘
                    │
┌───────────────────▼─────────────────────────────────┐
│               NLP Intent Engine                      │
│   (Language Detection → Intent Classification →      │
│    Entity Extraction → Smart Routing)                │
└───────────┬───────────────────┬─────────────────────┘
            │                   │
┌───────────▼──────┐  ┌─────────▼───────────────────┐
│  Response Engine │  │     Data Layer               │
│  - Case guidance │  │  - Mock NJDG JSON data       │
│  - eFiling steps │  │  - Case status simulator     │
│  - Legal aid     │  │  - Court statistics          │
│  - Feedback loop │  │  - eFiling document data     │
└──────────────────┘  └─────────────────────────────┘
```

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5 / CSS3 / JavaScript |
| Backend | Java (Spring Boot) |
| NLP / AI | Custom intent classifier + keyword engine |
| Data | Mock JSON (simulated NJDG + eCourts data) |
| Voice | Web Speech API |
| Visualization | Chart.js / D3.js |

---

## 📂 Project Structure

```
IJAS/
├── frontend/
│   ├── index.html
│   ├── chatbot.js
│   ├── visualizer.js
│   └── styles/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── services/
│   │   │   ├── IntentClassifier.java
│   │   │   ├── CaseNavigator.java
│   │   │   └── LegalAidRouter.java
│   │   └── models/
│   └── pom.xml
├── data/
│   ├── mock_cases.json
│   ├── njdg_stats.json
│   └── efiling_steps.json
├── docs/
│   └── architecture.png
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- Java 17+
- Node.js 18+ (for frontend dev server)
- Maven 3.8+

### Installation



The app will be available at 

---

## 💬 Example Interactions

```
User:  "Mera challan kaise bharu?"
IJAS:  [Detects: Hindi | Intent: Traffic Fine Payment]
       → Shows step-by-step challan payment guide
       → Provides direct portal link
       → Offers "Do It For Me" walkthrough mode

User:  "Check case status CNR UP123456"
IJAS:  → Current Stage: Under Trial — District Court, Lucknow
       → Next Hearing: 14 April 2026
       → Next Step: Attend hearing or submit adjournment application
       → [What should I do next?] button
```

---

## 📊 NJDG Visualizer Preview

- 📈 Pending cases trend (year-over-year)
- ⚖️ High Court vs District Court comparison
- 📍 State-wise judicial load heatmap

*(Powered by mock NJDG data — real API-ready architecture)*

---

## 🎯 Impact

| Metric | Value |
|---|---|
| 🇮🇳 Target Users | 1.4 billion citizens, especially rural & underprivileged |
| 🌐 Languages Supported | English, Hindi (expandable) |
| ♿ Accessibility | Voice input, simple UI, legal aid suggestions |
| ⚡ Entry Points Unified | NJDG + eCourts + eFiling + Tele-Law + Live Streaming |

---

## 👥 Team

| Name | Role |
|---|---|
| [Team Member 1] | AI / NLP |
| [Team Member 2] | Backend (Java) |
| [Team Member 3] | Frontend / UI |
| [Team Member 4] | Data & Research |

---

## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

---

> Built with ❤️ for **Smart India Hackathon** — making justice accessible to every Indian citizen.
