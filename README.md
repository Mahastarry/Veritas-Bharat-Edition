# Veritas: Bharat Edition ⚖️
**Theme 11: Court Judgments to Verified Action Plans** *PanIIT AI for Bharat Hackathon 2026*

## 📌 Executive Summary
Veritas is an AI-powered Decision Support System (DSS) designed to bridge the "Directive Gap" in Indian governance. High Court judgments are often dense, unstructured 50+ page PDFs. Veritas isolates actionable mandates, maps them to the responsible government departments (BBMP, PWD, Revenue), and generates a trackable "Compliance Clock" to prevent administrative delays and Contempt of Court citations.

## ✨ Key Features
- **Intelligent Directive Extraction:** Uses specialized LLM prompting to isolate "The Actionable Core" (Who, What, and When) of a judgment.
- **Explainable AI (XAI) Workspace:** A split-screen interface linking extracted tasks directly to the source paragraph in the original PDF for 100% human verification.
- **Departmental Mapping:** Automatically routes mandates to specific administrative wings based on legal context.
- **Compliance Dashboard:** A centralized "Command Center" for the Law Secretary to monitor deadlines and departmental accountability.

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS (Swiss Minimalist Design)
- **Icons:** Lucide-React
- **Processing:** LLM-based parsing logic (Claude/Gemini API ready)
- **Deployment:** Netlify / Vercel

## 📂 Project Structure
```text
├── src/
│   ├── components/       # UI: VerificationWorkspace, Dashboard, FileUpload
│   ├── data/             # Mock Legal Data (WP 12847/2024 - Karnataka HC)
│   ├── app/              # Main App Routing and Logic
│   └── styles/           # Global Tailwind Configurations
├── public/               # Asset management
└── package.json          # Dependencies & Scripts
