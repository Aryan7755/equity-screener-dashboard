# 📊 Equity Screener & Valuation Dashboard

A Python-based tool that screens NSE-listed stocks using fundamental ratios and estimates intrinsic value using a Discounted Cash Flow (DCF) model — deployed as an interactive Streamlit dashboard.

## 🎯 Goal

Help identify potentially under/overvalued stocks by combining fundamental screening (P/E, P/B, ROE, Debt-to-Equity, Revenue Growth) with a DCF-based intrinsic value estimate.

## 🛠️ Tech Stack

- **Python** — core logic
- **Pandas** — data processing
- **yfinance** — market & fundamental data
- **Streamlit** — interactive dashboard


## 🚀 How to Run (once complete)

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

## 📌 Features (planned)

- [ ] Fetch fundamental data for NSE-listed stocks
- [ ] Screen stocks by P/E, P/B, ROE, Debt-to-Equity, Revenue Growth
- [ ] DCF-based intrinsic value estimation
- [ ] Interactive Streamlit dashboard with filters
- [ ] Auto-generated investment thesis per stock

## 📄 License

Personal project — for educational/portfolio purposes.