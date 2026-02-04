# trader-sentiment-analysis

# Trader Performance vs Market Sentiment

This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trader data.

## Objective
To understand whether trader performance and behavior change under different market sentiment regimes and derive actionable trading insights.

## Datasets
- Bitcoin Fear & Greed Index (daily sentiment)
- Hyperliquid historical trader data

## Methodology
- Cleaned and aligned both datasets at a daily level
- Normalized sentiment into Fear and Greed
- Computed key metrics such as daily PnL, win rate, trade frequency, and long/short ratio
- Segmented traders based on trading frequency

## Key Insights
- Trader performance is weaker during Fear sentiment.
- Trade frequency increases during Greed sentiment.
- Frequent traders are more sensitive to market sentiment changes.

## Strategy Recommendations
- Reduce trade frequency and position size during Fear days.
- Increase trade activity during Greed days only for consistently profitable traders.
- Apply stricter risk controls for frequent traders during Fear sentiment.

## How to Run
1. Open `intern.ipynb`
2. Ensure datasets are available in the `data/` folder
3. Run all cells from top to bottom

## Output
The notebook generates charts comparing trader performance and behavior across sentiment regimes.
