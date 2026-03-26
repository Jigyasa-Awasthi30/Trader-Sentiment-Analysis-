# Trader Behavior Analytics Using Market Sentiment

##  Problem Statement

Financial markets are heavily influenced by **investor sentiment**, often driving irrational decisions such as over-leveraging during bullish phases or panic selling during downturns.

This project aims to answer:

> **How does market sentiment (Fear vs Greed) impact trader performance and decision-making?**

---

##  Objectives

* Analyze the effect of sentiment on **trader profitability (PnL)**
* Understand how sentiment influences **risk-taking behavior (leverage & position size)**
* Identify **behavioral patterns** in trading decisions
* Generate **data-driven recommendations** for improved trading strategies

---

## Data Sources

### 1. Market Sentiment Dataset

* Daily sentiment classification: **Fear / Greed**

### 2. Trader Activity Dataset (Hyperliquid)

* Trade-level data including:

  * Execution price
  * Position size
  * Trade direction (Long/Short)
  * Leverage
  * Closed Profit & Loss (PnL)

---

##  Approach

###  Data Preparation

* Standardized datetime formats
* Removed incomplete records
* Created unified date field for merging

###  Data Integration

* Combined sentiment and trading datasets on date

### Feature Engineering

* Profit classification (profit vs loss)
* Trade size segmentation (Small / Medium / Large)
* Sentiment labeling for each trade

### Analysis Performed

* PnL distribution across sentiment states
* Win rate comparison
* Leverage vs sentiment behavior
* Trade size and directional bias analysis
* Correlation analysis between trading variables

---

##  Key Findings

* **Fear markets** exhibit more stable and controlled trading behavior
* **Greed markets** lead to aggressive strategies with higher leverage
* Increased leverage correlates with **greater losses**, especially during Greed phases
* Traders tend to **overestimate market direction during Greed**, impacting performance

---

##  Behavioral Interpretation

This analysis reveals classic behavioral finance patterns:

*  **Overconfidence Bias** during Greed → excessive risk-taking
*  **Loss Aversion & Caution** during Fear → disciplined trading
*  Sentiment-driven decision-making overrides rational strategies

---

##  Strategic Insights

* Incorporating sentiment signals can **enhance risk management frameworks**
* Adaptive leverage strategies based on sentiment can improve outcomes
* Avoiding emotional trading during extreme sentiment phases is critical

---

##  Tools & Technologies

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Google Colab

---

##  Repository Structure

```bash id="0zts6k"
Trader-Behavior-Insights/
│── Trader_Sentiment_Analysis.ipynb
│── README.md
```

---

##  Conclusion

The study highlights that **market sentiment is a powerful driver of trader behavior**.

By aligning trading strategies with sentiment indicators, traders can:

* Reduce unnecessary risk
* Improve consistency
* Make more informed decisions

---

##  Author

**Jigyasa Awasthi**
Aspiring Data Scientist | Machine Learning Enthusiast

📎 GitHub: https://github.com/Jigyasa-Awasthi30/Trader-Sentiment-Analysis-

---

##  Final Note

This project demonstrates the ability to combine **data analysis, behavioral understanding, and business insight** — key skills required for modern data-driven trading systems.

## Recruiter Note

This project goes beyond standard data analysis by connecting **market sentiment with real trader behavior**, uncovering actionable insights that are directly applicable to trading platforms and financial decision-making systems.

What makes this work valuable:

* **Business Impact Focused**: Instead of just analyzing data, the project translates findings into **practical trading strategies** like adaptive leverage and sentiment-aware risk control.
* **Behavioral Intelligence**: Demonstrates a strong understanding of **behavioral finance concepts** (overconfidence, loss aversion) and how they manifest in real-world trading data.
* **End-to-End Ownership**: Covers the complete pipeline — from data cleaning and feature engineering to insight generation and strategic recommendations.
* **Scalable Thinking**: The approach can be extended to **real-time sentiment tracking systems, algorithmic trading models, or risk engines**.
* **Strong Analytical Foundation**: Uses structured analysis (PnL distribution, correlation, segmentation) to support conclusions with data.

This project reflects my ability to:

* Work with **complex datasets**
* Extract **meaningful, decision-driven insights**
* Bridge the gap between **data science and real-world applications**

I am particularly interested in roles where I can contribute to **data-driven decision-making, fintech innovation, or machine learning-based systems**.

I would love the opportunity to bring this analytical and problem-solving mindset to your team.

