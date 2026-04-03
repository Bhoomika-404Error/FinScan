# ⬡ FinScan — SME Financial Health Scanner

> Know your financial risk before it knows you.

![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.32+-red?style=flat-square&logo=streamlit)
![Plotly](https://img.shields.io/badge/Plotly-5.20+-purple?style=flat-square&logo=plotly)
![Domain](https://img.shields.io/badge/Domain-Fintech%20%2F%20Compliance-teal?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🧠 What is FinScan?

FinScan is an interactive SME Financial Health Intelligence dashboard that turns raw company financials into a real-time risk scorecard — the kind of analysis that fintech compliance teams do manually, automated into a single tool.

Built for the Indian SME context with compliance checks mapped to **GST, KYC/KYB, FEMA, and AML regulations**.

---

## ✨ Features

### 📊 Financial Health Score (0–100)
Multi-dimensional scoring engine across 5 weighted pillars:
- **Profitability** (25 pts) — Net margin analysis
- **Compliance** (25 pts) — GST, KYC, AML, audit posture
- **Liquidity** (20 pts) — Cash runway and debt-to-revenue
- **Transaction Health** (15 pts) — Large-value and cross-border exposure
- **Operational Maturity** (15 pts) — Tenure, team size, governance

### 🚨 Anomaly & Risk Detection
Real-time flagging of:
- Unusual large-value transaction concentration
- Elevated cross-border payment exposure (FEMA risk)
- AML structuring pattern indicators
- Cash runway crisis alerts
- Chronic late payment patterns
- GST compliance breaches

### 📈 12-Month Financial Forecast
- Dual-axis revenue vs expense trend
- Net profit bar overlay
- Growth-adjusted projections

### 🔍 Transaction Volume Analysis
- 12-month transaction history
- Flagged transaction overlay
- Volume trend detection

### 📋 Compliance Checklist
Live status for GST filing, KYC/KYB, annual audit, AML training, FEMA exposure, and late payment risk.

### 💡 AI-Powered Insights
Context-aware recommendations — not generic tips, but specific actions based on the company's actual numbers.

### 🎯 Cost Structure Breakdown
Category-wise expense waterfall + dual gauge charts for debt ratio and margin.

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/Bhoomika-404Error/FinScan.git
cd FinScan

# Install dependencies
pip install -r requirements.txt

# Run the dashboard
streamlit run sme_scanner.py
```

Opens at `http://localhost:8501` 🎉

---

## 📦 Dependencies

```
streamlit>=1.32.0
pandas>=2.0.0
plotly>=5.20.0
numpy>=1.26.0
```

---

## 📂 Project Structure

```
FinScan/
├── sme_scanner.py       # Main Streamlit application
├── requirements.txt     # Python dependencies
└── README.md
```

---

## 🎮 How to Use

1. **Enter company profile** in the sidebar — name, industry, team size
2. **Input financials** — monthly revenue, expenses, debt, cash reserves
3. **Set transaction behaviour** — volume, large txn %, cross-border %
4. **Configure compliance posture** — GST status, KYC, audit, AML
5. **Read the dashboard** — every metric, chart and insight updates live

Change any input and the entire dashboard recalculates instantly.

---

## 🏗️ Scoring Methodology

| Dimension | Weight | Key Factors |
|---|---|---|
| Profitability | 25% | Net margin bands |
| Compliance | 25% | GST filing, KYC, AML, audit |
| Liquidity | 20% | Cash runway, debt-to-revenue ratio |
| Transaction Health | 15% | Large txn %, cross-border %, late payments |
| Operational Maturity | 15% | Years in operation, team size, governance |

**Grade scale:** A+ (85–100) · A (75–84) · B+ (65–74) · B (55–64) · C (45–54) · D (35–44) · F (<35)

---

## 🎨 Design

Dark-themed, built to feel like a professional fintech product:
- `Outfit` for display and UI text
- `JetBrains Mono` for numbers and financial figures
- Teal (`#00D4AA`) primary accent — clean, financial, modern
- Severity-coded anomaly flags (red / amber / blue)

---

## 🛠️ Built With

- [Streamlit](https://streamlit.io/) — App framework
- [Plotly](https://plotly.com/python/) — Interactive charts
- [Pandas](https://pandas.pydata.org/) — Data processing
- [NumPy](https://numpy.org/) — Numerical computation

---

## 👩‍💻 Author

**Bhoomika** — [@Bhoomika-404Error](https://github.com/Bhoomika-404Error)

*Built as part of a fintech data analytics portfolio. Inspired by the real problems SMEs face with financial visibility and compliance risk.*

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">
  <sub>⬡ FinScan · Because financial risk shouldn't be invisible</sub>
</div>
