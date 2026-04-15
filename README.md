# CrowdWisdomTrading Marketing Agents

## 🚀 Overview
This project implements AI-based marketing agents to analyze competitors, identify user pain points, and generate human-like engagement responses for prediction markets.

The system is designed using an agent-based architecture inspired by Hermes framework principles.

---

## 🧠 Features

### 1. Competitor Analysis Agent
- Identifies key competitors like Polymarket, Kalshi, PredictIt
- Generates structured market insights
- Highlights strengths & opportunities

### 2. Reddit Pain Point Agent
- Simulates discovery of user problems
- Generates 3–5 natural, non-spammy replies
- Focuses on trust, reliability, and decision-making issues

### 3. Closed Learning Loop
- Improves generated responses iteratively
- Demonstrates adaptive agent behavior

---

## ⚙️ Tech Stack
- Python
- Agent-based architecture (Hermes-inspired)
- OpenRouter (LLM integration with fallback handling)
- Apify (scraping concept integration)

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python main.py
📂 Output
outputs/competitor_report.txt
outputs/reddit_replies.json
💡 Key Design Decisions
Implemented fallback logic to handle API failures gracefully
Focused on reliability and deterministic outputs
Designed modular agent structure for scalability
🔥 Future Improvements
Real-time Reddit scraping using Apify
Dynamic competitor data extraction
Advanced feedback-based learning loop
👤 Author

Deepak Vishwakarma


---

# 📁 2. Make Sure These Files Have Data

### 📄 `outputs/competitor_report.txt`
✔ Already generated → good

### 📄 `outputs/reddit_replies.json`
👉 Run once again to ensure it's saved:

```bash
python main.py