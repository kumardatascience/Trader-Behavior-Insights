
# Trader Performance vs Market Sentiment 
This project analyzes how market sentiment (Fear / Greed) relates to trader behavior
and performance on the Hyperliquid exchange.

## Methodology
- Cleaned and aligned timestamps across datasets
- Aggregated trade-level data to daily trader-level metrics
- Engineered features such as daily PnL, win rate, trade frequency, trade size,
  and long/short bias
- Merged trader metrics with daily Fear–Greed sentiment
- Analyzed performance, behavior, and trader segments across sentiment regimes

## Key Insights
- Trader performance varies across sentiment regimes, with higher upside during
  Greed periods and higher downside risk during Fear periods.
- Traders change behavior based on sentiment, trading more frequently and with
  larger position sizes during Fear regimes.
- Frequent traders tend to outperform infrequent traders during Greed regimes.

## Optional Extension
A simple logistic regression model was used to predict next-day trader profitability
using behavior metrics and market sentiment. Results show modest predictive power.

## How to Run
Open `Trader Performance vs Market Sentiment_Assignment.ipynb` and run all cells. 

## Summary 
Daily trader-level metrics were derived from trade data and merged with market
sentiment from the Fear–Greed Index. Performance and behavior were analyzed across
sentiment regimes, and traders were segmented based on activity, consistency, and
directional bias.

The analysis shows that market sentiment impacts both trader behavior and risk
profiles, highlighting the value of sentiment-aware analysis.
