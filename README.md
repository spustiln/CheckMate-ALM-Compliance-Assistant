# 💼 AML Compliance Simulator (Streamlit)

This project is a gamified AI-powered AML (Anti-Money Laundering) simulator built with Streamlit. It allows Tier 1 analysts to review flagged transactions, escalate to Tier 2 compliance, and generate FinCEN-style SAR reports in DOCX format.

## Features

- 📊 AI-based transaction flagging
- 🧑‍💼 Tier 1 and Tier 2 decision flow
- 🧾 SAR Report Generator (DOCX)
- 🔁 90-day Continuing SAR reminder
- 🧰 Interactive Streamlit UI

## How to Use

```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
```

Upload your `tx.csv` and optional `alerts.csv` to begin.

## Files

- `streamlit_app.py`: Main Streamlit application
- `requirements.txt`: Dependency list
- `README.md`: Project documentation

## Compliance Notes

- Never inform the customer about SAR filings
- Follow BSA/FinCEN 30- and 90-day rules for SAR timing
