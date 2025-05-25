# Bitcoin Market Sentiment vs Trader Performance

This project explores the relationship between Bitcoin market sentiment (via the Fear & Greed Index) and historical trader performance using data from Hyperliquid.

## Objective
To uncover whether trader profitability correlates with daily market sentiment, and identify sentiment-driven trading patterns.

## Dataset Sources
- **Fear & Greed Index**: Contains date-wise market sentiment classification
- **Historical Trader Data**: Includes trade execution time, position, PnL, and other trade details

## Methodology
1. Parsed timestamps and extracted trade dates
2. Merged each trade with the corresponding market sentiment
3. Computed average `Closed PnL` per sentiment category
4. Classified trades as profitable/unprofitable
5. Visualized:
   - PnL distributions by sentiment (boxplot)
   - Profitability ratios (stacked bar chart)
   - Daily average PnL trends (line chart)

##  Key Findings
- **Extreme Greed** days had the **highest average profits**
- **Fear** also performed well—indicating traders may profit from volatility
- **Neutral and Extreme Fear** periods had the lowest profitability
- Most sentiment types still yielded more **unprofitable** than profitable trades



