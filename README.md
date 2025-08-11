# Legal AI Chatbot 🏛️

An open-source AI-powered chatbot designed to **simplify complex legal information** for everyday users while maintaining accuracy, citations, and court decorum guidelines.

## 🚀 Features
- **Acts & Articles** — Complete coverage of legal texts (Constitution, IPC, CPC, etc.)
- **Plain Language Mode** — Explains legal terms in simple everyday words
- **Lawyer Mode** — Detailed sections with act numbers and citations
- **Court Decorum** — Includes procedural etiquette and best practices
- **Document Templates** — FIR, Affidavit, Petitions, etc.

## 📂 Project Structure
legal-ai-chatbot/
│
├── data/ # Collected legal texts in JSON format
├── scripts/ # Data scraping and processing tools
├── requirements.txt # Python dependencies
└── README.md

## 🔧 Installation

# Clone the repo
git clone https://github.com/<your-username>/legal-ai-chatbot.git
cd legal-ai-chatbot

# Install dependencies
pip install -r requirements.txt
📜 Data Collection
To collect law data:

python scripts/scraper.py
The scraped data will be stored in the data/ folder as JSON files.

🛡 Disclaimer
This chatbot is for informational purposes only and does not constitute legal advice.
For legal matters, please consult a qualified lawyer.

Author: Vedant kasaudhan
License: MIT
