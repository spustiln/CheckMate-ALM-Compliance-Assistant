# ♟️ CheckMat AML Assistant

CheckMat AML Assistant is a Streamlit-based application that simulates an Anti-Money Laundering (AML) Tier 1 and Tier 2 compliance review process. Analysts can flag transactions, escalate suspicious cases, and generate FinCEN-style SAR reports automatically.

## 🚀 Features

- 💡 AI-style rule-based flagging (velocity, structuring, prior alerts)
- 🧑‍💼 Tier 1 & Tier 2 decision interface
- 📄 SAR report generation in Word format
- 📊 Case log with 90-day SAR follow-up tracking
- 📂 Streamlit interface for demo, audit, and training use

## 📦 Setup

1. Clone this repository:
```bash
git clone https://github.com/your-org/checkmat-aml-assistant.git
cd checkmat-aml-assistant
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the app:
```bash
streamlit run CheckMat_AML_Assistant.py
```

## 📁 Files

- `CheckMat_AML_Assistant.py` – Main app script
- `requirements.txt` – Dependencies
- `README.md` – App overview and usage
- `AML_4Minute_RealData_DemoScript.txt` – Demo script
- `AML_Demo_Narration.md` – Narrated case explanations

## ✅ Notes

- Designed for small-dollar transaction simulations
- Reset logic ensures fresh UI for each case
- All reports export as `.docx`
