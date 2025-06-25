# 📊 Trader Behavior vs Market Sentiment Analysis

This project analyzes how trader performance (like profits, volume, and trade behavior) is affected by Bitcoin market sentiment, using the Fear and Greed Index. The goal is to understand how emotions drive trading outcomes and explore ways to build smarter trading strategies.

---

## 📁 Datasets Used

1. **Fear & Greed Index**
   - Daily market sentiment score and label (Fear, Greed, etc.)
2. **Hyperliquid Trader Data**
   - Detailed trade-level data: PnL, side (buy/sell), volume, execution price, etc.

---

## 🔍 What We Did

- Cleaned and merged both datasets on a daily level
- Aggregated trading metrics like:
  - Average and total PnL
  - Buy ratio (buy trades / total trades)
  - Total trading volume in USD
  - Number of unique traders per day
- Mapped these to the sentiment data

---

## 📊 Key Insights

- **Traders perform better during Greed/Extreme Greed** days  
- **Buy ratio is higher on Greed days** → showing more risk-taking  
- **Trading volume rises with positive sentiment**
- *(Optional)* A simple ML model can predict profitable days using sentiment + volume with up to **81% accuracy**

---

## ✅ Outcome

This analysis shows that market sentiment plays a key role in how traders behave and perform. With the right metrics, we can use this information to improve trade timing, manage risk, and even build simple predictive models.

---

