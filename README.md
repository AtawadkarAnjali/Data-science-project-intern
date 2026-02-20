# Data-science-project-intern
# Trader Behavior vs Market Sentiment

## 📌 Objective

This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance using Hyperliquid historical trading data.

The goal is to uncover behavioral patterns that can inform smarter trading strategies.

---

## 📂 Dataset

Two datasets were used:

1. **Historical Trader Data**

   * Account
   * Symbol
   * Execution price
   * Size
   * Side (Long/Short)
   * Closed PnL
   * Timestamp

2. **Bitcoin Fear & Greed Index**

   * Date
   * Classification (Fear / Greed)
   * Sentiment value

---

## ⚙️ Methodology

1. Data cleaning and preprocessing
2. Timestamp conversion and daily alignment
3. Feature engineering:

   * Daily PnL per trader
   * Win rate
   * Average trade size
   * Trade frequency
   * Long/Short ratio
4. Sentiment-based behavioral analysis
5. Trader segmentation
6. Predictive modeling (bonus)
7. Streamlit dashboard for visualization

---

## 📊 Key Insights

* Trader profitability becomes more volatile during Fear periods.
* Trade frequency increases during Greed, suggesting momentum-driven behavior.
* Position sizing expands during Greed, reflecting higher risk tolerance.
* Long bias strengthens during Greed phases.
* Consistent winners adapt risk by reducing exposure during Fear.

---

## 💡 Strategy Recommendations

1. **Sentiment-adaptive risk control**
   Reduce leverage and position sizing during Fear regimes.

2. **Greed momentum filter**
   Apply trend-following strategies during Greed while limiting over-trading.

---

## 🧠 Bonus Work

* Predictive model to estimate next-day profitability
* Trader clustering to identify behavioral archetypes
* Interactive Streamlit dashboard

---

## 🚀 How to Run

### Install dependencies

```
pip install -r requirements.txt
```

### Run analysis

```
python analysis.py
```

### Run dashboard

```
python -m streamlit run app.py
```

Then open:

```
http://localhost:8501
```

---

## 📁 Project Structure

```
project/
│
├── analysis.py
├── app.py
├── requirements.txt
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
└── outputs/
```

---

## ✅ Evaluation Focus

* Correct data preparation and merging
* Clear reasoning behind analysis
* Actionable insights (not generic plots)
* Reproducibility and clean code

---

## 👩‍💻 Author

Data Science Internship Assignment — Trader Behavior Insights
