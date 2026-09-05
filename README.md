# 🚀 FinTrace AI | Autonomous Payment Reconciliation & Support Agent
**Built for PS-8: Automated Settlement & Customer Q&A Platform**

FinTrace AI is an enterprise-grade SaaS dashboard designed to bridge the gap between legacy banking infrastructure and customer support teams. By autonomously cross-referencing payment gateways, bank settlements, and internal ledgers, FinTrace AI eliminates payment ambiguity, translates cryptic bank error codes into **Plain-English delay explanations**, and generates empathetic, native-language support resolutions.

---

## 🌟 Core Features

* **Real-Time Batch Reconciliation Matrix**: Dynamically ingests and cross-references `gateway.csv`, `bank.csv`, and `ledger.csv` files to instantly flag discrepancies, missing entries, and exceptions.
* **AI-Driven Audit Engine**: Powered by the Groq SDK (`llama-3.1-8b-instant`) to perform deep-dive risk assessments and confidence scoring on failed or delayed transactions.
* **Plain-English Settlement Status & Delay Reason**: Automatically translates complex database logs and bank error codes into clear, non-technical explanations for support agents (Strictly fulfilling PS-8 requirements).
* **Multi-Lingual Payer-Facing Resolution Generator**: Instantly drafts empathetic messaging across multiple regional languages (Hindi, Telugu, Tamil, Bengali, Marathi, etc.) ensuring anxious customers receive instant clarity.

---

## 🛠 Tech Stack

* **Frontend & Framework**: Next.js 14 (App Router), React, TypeScript
* **Styling**: Tailwind CSS (Dark-Mode Enterprise SaaS Aesthetic)
* **AI & NLP Inference**: Groq SDK (`llama-3.1-8b-instant`)
* **Data Processing**: `csv-parse/sync` for multi-source log reconciliation

---

## 🚀 Getting Started Locally

Follow these steps to run the application locally on your machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/Kushagra061310/fintrace-ai-live.git](https://github.com/Kushagra061310/fintrace-ai-live.git)
cd fintrace-agent
npm install
GROQ_API_KEY=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
npm run dev

📂 Project Structure

fintrace-agent/
├── app/
│   ├── api/
│   │   └── trace/
│   │       └── route.ts     # Core API endpoint handling CSV parsing & Groq AI prompt-chaining
│   ├── globals.css          # Tailwind styling setup
│   └── page.tsx             # Main SaaS dashboard interface
├── mock_data/
│   ├── gateway.csv          # Payment gateway transaction logs
│   ├── bank.csv             # Bank settlement records
│   └── ledger.csv           # Internal financial ledger entries
├── public/                  # Static assets
├── .env.local               # Local environment variables (Ignored by Git)
└── package.json             # Project dependencies and metadata

git clone [https://github.com/Kushagra061310/fintrace-ai-live.git](https://github.com/Kushagra061310/fintrace-ai-live.git)
cd fintrace-agent
