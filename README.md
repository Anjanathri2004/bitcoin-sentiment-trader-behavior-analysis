# 📊 Bitcoin Market Sentiment vs Trader Behavior Analysis

## 📌 Project Overview
This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader behavior** using historical trading data from the Hyperliquid exchange. The goal is to understand how sentiment impacts trading volume, profitability, win rate, and risk behavior.

---

## 🎯 Objectives
- Compare trader behavior during **Fear** and **Greed** market conditions  
- Analyze changes in trading volume, profitability (PnL), and win rate  
- Infer risk-taking behavior under different sentiment regimes  
- Identify hidden trends driven by market psychology  

---

## 📂 Project Structure
ds_Anjanathri/
├── csv_files/
│ ├── fear_greed_index.csv
│ └── historical_trades.csv
├── outputs/
│ ├── volume_vs_market_sentiment.png
│ ├── pnl_vs_market_sentiment.png
│ ├── win_rate_vs_market_sentiment.png
│ └── risk_behavior.png
├── notebook_1.ipynb
├── ds_report.pdf
└── README.md


---

## 📊 Datasets Used

### 1️⃣ Bitcoin Fear & Greed Index
- **Columns:** `date`, `classification`
- Represents daily market sentiment as Fear or Greed

### 2️⃣ Historical Trader Data (Hyperliquid)
- **Key Columns:** `Account`, `Size USD`, `Side`, `Timestamp`, `Closed PnL`
- Captures trader activity and performance

---

## ⚙️ Methodology
1. Cleaned and standardized dataset column names  
2. Converted timestamps and aggregated trader data on a daily basis  
3. Encoded sentiment labels numerically for analysis  
4. Merged sentiment and trader metrics using date  
5. Performed exploratory analysis and created visualizations  

---

## 🔍 Key Insights
- Trading volume is higher during **Greed** sentiment periods  
- Increased activity during Greed does not consistently improve profitability  
- Fear periods show lower volume but more consistent win rates  
- Risk-taking behavior increases during Greed, while Fear encourages caution  

---

## ⚠️ Limitations
- Leverage information was not available in the dataset  
- Risk behavior is inferred indirectly using volume, PnL volatility, and win rate  
- Results depend on the provided historical timeframe  

---

## 🧾 Conclusion
Market sentiment strongly influences trader behavior. While Greed leads to higher activity and risk-taking, Fear promotes more disciplined trading, highlighting the psychological impact of sentiment on financial decision-making.

---

## 🛠 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Google Colab  

---

