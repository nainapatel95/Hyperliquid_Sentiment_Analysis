# Hyperliquid_Sentiment_Analysis

## Objective

To analyse how trader behaviour changes during **Fear, Greed, and Neutral markets** and check whether trader profitability can be predicted using behavioural metrics.

The focus is on understanding trading psychology, not building a trading strategy.

---

## Dataset

Two datasets were combined using the date:

**Trading Data**

* Trade size
* PnL
* Long/Short direction
* Leverage
* Timestamp

**Market Sentiment**

* Fear & Greed Index classification

---

## Workflow

### Data Preparation

* Cleaned data & handled missing values
* Converted timestamps to daily level
* Merged sentiment with trading data

### Feature Engineering

Created daily trader metrics:

* Daily PnL
* Win rate
* Average trade size
* Trades per day
* Long/Short ratio
* Leverage

### Analysis

Compared trader behavior across Fear vs Greed markets using charts and tables.

### Prediction Model

Built a simple classification model to predict trader profitability from behavior features.

---

## Key Findings

* Trader performance changes with market sentiment
* High leverage leads to inconsistent results
* Win rate is the strongest indicator of profitability
* Overtrading does not improve performance
* Consistent low-risk traders perform better

---

## Strategy Ideas

* **Greed:** trade carefully with low leverage
* **Fear:** trade actively but control risk
* Long-term profit comes from consistency, not high risk

---

## Model Performance

Accuracy ≈ **60%**
Used as a baseline model to understand behavior patterns.

---

## Tech Stack

Python, Pandas, NumPy, Matplotlib, Scikit-learn

---

## Conclusion

Market emotion strongly influences trading behavior.
Successful traders are disciplined and risk-controlled rather than aggressive.


