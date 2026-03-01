##  insights.md

```markdown
# Trader Behavior Insights — Short Write-up

## Methodology
- Cleaned and merged Fear & Greed Index with historical trading data (daily level).
- Computed trader-level metrics: daily PnL, win rate, average trade size, leverage, trade frequency, long/short ratio.
- Compared performance across sentiment regimes (Fear vs Greed).
- Segmented traders by leverage (high vs low) and frequency (frequent vs infrequent).

## Key Insights
1. **Fear days** → Average PnL and win rate decline, especially for high-leverage traders.  
2. **Greed days** → Frequent traders capture more upside, with higher average PnL.  
3. **Bias shift** → Fear days show more short positions, while Greed days lean towards longs.

## Strategy Recommendations
- **Rule 1:** On Fear days, reduce leverage for high-leverage traders to limit drawdowns.  
- **Rule 2:** On Greed days, encourage frequent traders to increase trade frequency to maximize gains.  
