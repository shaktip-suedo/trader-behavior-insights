# Trader Behavior Insights Analysis

## Overview
This project analyzes trader behavior by combining trade-level data with market sentiment indicators.  
The objective is to understand how sentiment impacts trading outcomes and derive actionable insights.

---

## Dataset Used
- **Trade Data**: Individual trade records including execution price, size, side, PnL, and timestamps
- **Sentiment Data**: Daily market sentiment classified as Fear / Neutral / Greed

---

## Methodology
1. Loaded and cleaned trade and sentiment datasets
2. Converted timestamps and aligned both datasets by date
3. Merged sentiment classification with each trade
4. Analyzed performance metrics such as:
   - Win rate
   - Average PnL
   - Trade behavior under different sentiment regimes

---

## Key Insights
- Trades executed during **Greed** sentiment showed higher risk-taking behavior
- **Fear** periods had lower win rates and reduced position sizes
- Neutral sentiment resulted in more stable and consistent outcomes

---

## Strategy Recommendations
- Reduce leverage and position size during **Fear** sentiment
- Apply stricter risk management during **Greed** phases
- Prefer higher-confidence setups during Neutral sentiment periods

---

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload the required CSV files
3. Run all cells sequentially to reproduce the analysis

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
