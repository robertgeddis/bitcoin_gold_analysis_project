# Is Bitcoin Really 'Digital Gold'? 🪙

## 🔬 Questions to Investigate

1. What is the current relationship between Bitcoin and Gold?
2. Do Bitcoin and Gold behave similarly in the economy?
3. How does demand differ between the two?

---

## 📊 Data Details

* **Source:** 10 years of daily close price market data from the yfinance library and 10 years monthly macro economic data from the FRED API. 
* **Cleaning:** Handled the 'Weekend Gap' for non-Bitcoin price data by creating both forward filled and synced versions to ensure consistent comparison.
* **Normalization:** Applied Base-100 indexing to allow for an accurate comparison between a $100k (BTC) and a $2k (Gold) asset.

---

## 📈 Analysis Workflow

* **Exploratory:** Plotting the 'Big Picture' to see long-term trends across all market based price metrics.
* **Correlations:** Exploring the relationship between Bitcoin, Gold and macro-economic indexes through heatmaps, Pearson and rolling correlations.
* **Causality:** Testing relationsips between Bitcoin, Gold and macro-economic indexes through Granger Causality Tests, Impulse Response Functions and Vector Decomposition.  

---

## 🏁 Conclusion

1. Vector Decomposition results showed that Gold holds a strong influence over Bitcoin, but Bitcoin barely has any influence over Gold.
2. Bitcoin behaves offensively, Gold defensively. Together they form a dual hedge system - Bitcoin against a weak currency, Gold against high prices.
3. Demand for Bitcoin is driven by wealth expansion, demand for Gold by wealth preservation.

