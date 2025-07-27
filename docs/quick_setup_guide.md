# Oracle Precision Pro - Quick Setup Guide

## Installation

1. **Copy the Script**: Copy the entire content of `oracle_precision_pro.pine`
2. **TradingView**: Go to TradingView Pine Script Editor
3. **Paste Code**: Paste the script and click "Add to Chart"
4. **Configure Settings**: Adjust parameters in the indicator settings

## Quick Configuration

### For Beginners (Recommended Settings)
```
Technical Indicators:
- Fast EMA: 9
- Slow EMA: 21
- RSI Length: 14
- ADX Minimum: 20

Confidence Weights:
- Trend Weight: 25%
- MACD Weight: 20%
- RSI Weight: 20%
- Volatility Weight: 20%
- ADX Weight: 15%

Multi-Timeframe:
- Enable: Yes
- Higher Timeframe: 4H (for 1H charts) or 1D (for 4H charts)
- HTF Weight: 30%

Risk Management:
- Enable: Yes
- Stop Loss ATR: 2.0
- Take Profit ATR: 3.0
```

### For Experienced Traders
```
Confidence Weights (Aggressive):
- Trend Weight: 30%
- MACD Weight: 25%
- RSI Weight: 25%
- Volatility Weight: 10%
- ADX Weight: 10%

Risk Management (Tight):
- Stop Loss ATR: 1.5
- Take Profit ATR: 2.5
```

## Key Features Toggle

### Essential Features (Always Enable)
- ✅ Show Signal Labels
- ✅ Enable Alerts
- ✅ Enable Risk Management
- ✅ Enhanced Alert Messages

### Optional Features
- 🔄 Multi-Timeframe Analysis (recommended for higher accuracy)
- 🔄 Show Background Shading (visual preference)
- 🔄 Show Risk Levels on Chart (helpful for new traders)

## Signal Interpretation

### BUY Signal Checklist
- 🔥 Oracle BUY label appears
- Confidence score ≥ 60%
- Green background shading (if enabled)
- Stop Loss and Take Profit levels displayed

### SELL Signal Checklist
- 🔥 Oracle SELL label appears
- Confidence score ≥ 60%
- Red background shading (if enabled)
- Stop Loss and Take Profit levels displayed

## Alert Setup

1. **Right-click** on chart → "Add Alert"
2. **Select** "Oracle PRECISION BUY" or "Oracle PRECISION SELL"
3. **Configure** notification method (email, mobile, webhook)
4. **Set** alert frequency to "Once Per Bar Close"

## Common Mistakes to Avoid

❌ **Don't**: Trade every signal regardless of confidence
✅ **Do**: Focus on signals with 70%+ confidence

❌ **Don't**: Ignore the higher timeframe when enabled
✅ **Do**: Wait for HTF confirmation for stronger signals

❌ **Don't**: Move stop losses against you
✅ **Do**: Follow the ATR-based risk management levels

❌ **Don't**: Use on ranging/sideways markets
✅ **Do**: Use during trending market conditions

## Timeframe Recommendations

| Chart Timeframe | Higher Timeframe | Best For |
|----------------|------------------|----------|
| 15m | 1H | Scalping |
| 1H | 4H | Day Trading |
| 4H | 1D | Swing Trading |
| 1D | 1W | Position Trading |

## Support

For detailed optimization and backtesting instructions, see the complete guide in `docs/oracle_precision_pro_guide.md`.