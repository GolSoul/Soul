# Oracle Precision Pro Enhanced - Configuration Presets

This file contains optimized configuration presets for different trading styles and market conditions.

## Conservative Gold Trading (Low Risk)

### Basic Settings
```
Fast EMA: 12
Slow EMA: 26
RSI Length: 14
RSI Overbought: 75
RSI Oversold: 25
Bollinger Band Length: 20
BB Multiplier: 2.2
ATR Length: 14
ADX Length: 14
Min ADX Strength: 25
```

### Confidence Scoring
```
Enable Enhanced Confidence Scoring: true
Trend Weight: 30%
MACD Weight: 20%
RSI Weight: 20%
Volatility Weight: 20%
ADX Weight: 10%
Minimum Confidence Threshold: 80%
```

### Multi-Timeframe
```
Enable Multi-Timeframe Analysis: true
Higher Timeframe: 4H (for 1H charts)
MTF Fast EMA: 9
MTF Slow EMA: 21
MTF RSI Length: 14
```

### Risk Management
```
Enable Risk Management: true
Max Risk Per Trade: 1%
Stop Loss ATR Multiplier: 2.5
Take Profit Ratio: 2.0
Max Drawdown Alert: 8%
Enable Trailing Stop: true
Trailing Stop ATR Multiplier: 2.0
```

---

## Aggressive Gold Trading (High Risk/Reward)

### Basic Settings
```
Fast EMA: 8
Slow EMA: 18
RSI Length: 12
RSI Overbought: 70
RSI Oversold: 30
Bollinger Band Length: 18
BB Multiplier: 1.8
ATR Length: 12
ADX Length: 12
Min ADX Strength: 18
```

### Confidence Scoring
```
Enable Enhanced Confidence Scoring: true
Trend Weight: 25%
MACD Weight: 25%
RSI Weight: 25%
Volatility Weight: 15%
ADX Weight: 10%
Minimum Confidence Threshold: 65%
```

### Multi-Timeframe
```
Enable Multi-Timeframe Analysis: true
Higher Timeframe: 1H (for 15min charts)
MTF Fast EMA: 8
MTF Slow EMA: 18
MTF RSI Length: 12
```

### Risk Management
```
Enable Risk Management: true
Max Risk Per Trade: 3%
Stop Loss ATR Multiplier: 1.8
Take Profit Ratio: 2.5
Max Drawdown Alert: 15%
Enable Trailing Stop: true
Trailing Stop ATR Multiplier: 1.2
```

---

## Scalping Configuration (1-5 minute charts)

### Basic Settings
```
Fast EMA: 5
Slow EMA: 13
RSI Length: 10
RSI Overbought: 68
RSI Oversold: 32
Bollinger Band Length: 15
BB Multiplier: 2.0
ATR Length: 10
ADX Length: 10
Min ADX Strength: 15
```

### Confidence Scoring
```
Enable Enhanced Confidence Scoring: true
Trend Weight: 20%
MACD Weight: 30%
RSI Weight: 20%
Volatility Weight: 20%
ADX Weight: 10%
Minimum Confidence Threshold: 70%
```

### Multi-Timeframe
```
Enable Multi-Timeframe Analysis: true
Higher Timeframe: 15min
MTF Fast EMA: 5
MTF Slow EMA: 13
MTF RSI Length: 10
```

### Risk Management
```
Enable Risk Management: true
Max Risk Per Trade: 1.5%
Stop Loss ATR Multiplier: 1.5
Take Profit Ratio: 1.8
Max Drawdown Alert: 10%
Enable Trailing Stop: true
Trailing Stop ATR Multiplier: 1.0
```

---

## Swing Trading Configuration (4H-1D charts)

### Basic Settings
```
Fast EMA: 12
Slow EMA: 34
RSI Length: 21
RSI Overbought: 75
RSI Oversold: 25
Bollinger Band Length: 25
BB Multiplier: 2.5
ATR Length: 21
ADX Length: 21
Min ADX Strength: 22
```

### Confidence Scoring
```
Enable Enhanced Confidence Scoring: true
Trend Weight: 35%
MACD Weight: 20%
RSI Weight: 15%
Volatility Weight: 20%
ADX Weight: 10%
Minimum Confidence Threshold: 75%
```

### Multi-Timeframe
```
Enable Multi-Timeframe Analysis: true
Higher Timeframe: 1D (for 4H charts)
MTF Fast EMA: 12
MTF Slow EMA: 34
MTF RSI Length: 21
```

### Risk Management
```
Enable Risk Management: true
Max Risk Per Trade: 2.5%
Stop Loss ATR Multiplier: 3.0
Take Profit Ratio: 2.5
Max Drawdown Alert: 12%
Enable Trailing Stop: true
Trailing Stop ATR Multiplier: 2.5
```

---

## High Volatility Market Configuration

### Basic Settings
```
Fast EMA: 10
Slow EMA: 24
RSI Length: 16
RSI Overbought: 72
RSI Oversold: 28
Bollinger Band Length: 22
BB Multiplier: 2.3
ATR Length: 16
ADX Length: 16
Min ADX Strength: 20
```

### Confidence Scoring
```
Enable Enhanced Confidence Scoring: true
Trend Weight: 25%
MACD Weight: 20%
RSI Weight: 20%
Volatility Weight: 25%
ADX Weight: 10%
Minimum Confidence Threshold: 75%
```

### Multi-Timeframe
```
Enable Multi-Timeframe Analysis: true
Higher Timeframe: 4H
MTF Fast EMA: 10
MTF Slow EMA: 24
MTF RSI Length: 16
```

### Risk Management
```
Enable Risk Management: true
Max Risk Per Trade: 1.5%
Stop Loss ATR Multiplier: 2.2
Take Profit Ratio: 2.2
Max Drawdown Alert: 10%
Enable Trailing Stop: true
Trailing Stop ATR Multiplier: 1.8
```

---

## Low Volatility Market Configuration

### Basic Settings
```
Fast EMA: 8
Slow EMA: 20
RSI Length: 12
RSI Overbought: 68
RSI Oversold: 32
Bollinger Band Length: 18
BB Multiplier: 1.8
ATR Length: 12
ADX Length: 12
Min ADX Strength: 15
```

### Confidence Scoring
```
Enable Enhanced Confidence Scoring: true
Trend Weight: 30%
MACD Weight: 25%
RSI Weight: 25%
Volatility Weight: 15%
ADX Weight: 5%
Minimum Confidence Threshold: 65%
```

### Multi-Timeframe
```
Enable Multi-Timeframe Analysis: true
Higher Timeframe: 2H
MTF Fast EMA: 8
MTF Slow EMA: 20
MTF RSI Length: 12
```

### Risk Management
```
Enable Risk Management: true
Max Risk Per Trade: 2%
Stop Loss ATR Multiplier: 1.8
Take Profit Ratio: 2.0
Max Drawdown Alert: 8%
Enable Trailing Stop: true
Trailing Stop ATR Multiplier: 1.5
```

---

## News Trading Configuration

### Basic Settings
```
Fast EMA: 6
Slow EMA: 15
RSI Length: 8
RSI Overbought: 75
RSI Oversold: 25
Bollinger Band Length: 12
BB Multiplier: 2.5
ATR Length: 8
ADX Length: 8
Min ADX Strength: 20
```

### Confidence Scoring
```
Enable Enhanced Confidence Scoring: true
Trend Weight: 20%
MACD Weight: 30%
RSI Weight: 15%
Volatility Weight: 30%
ADX Weight: 5%
Minimum Confidence Threshold: 70%
```

### Multi-Timeframe
```
Enable Multi-Timeframe Analysis: false
(Use single timeframe for rapid response)
```

### Risk Management
```
Enable Risk Management: true
Max Risk Per Trade: 1%
Stop Loss ATR Multiplier: 2.0
Take Profit Ratio: 1.5
Max Drawdown Alert: 5%
Enable Trailing Stop: false
(Use fixed targets for news events)
```

---

## Session-Based Configurations

### Asian Session (Low Volatility)
- Use Low Volatility Market Configuration
- Reduce position size by 50%
- Increase confidence threshold to 80%

### London Session (Medium-High Volatility)
- Use Conservative or Aggressive configuration
- Standard position sizing
- Monitor major news events

### US Session (High Volatility)
- Use High Volatility Market Configuration
- Consider reducing position size during FOMC announcements
- Enable all risk management features

---

## Implementation Notes

1. **Configuration Selection**: Choose based on:
   - Your risk tolerance
   - Current market volatility
   - Trading timeframe
   - Available trading time

2. **Parameter Adjustment**: Fine-tune based on:
   - Recent market performance
   - Personal trading results
   - Changing market conditions

3. **Testing Protocol**: 
   - Always backtest new configurations
   - Use paper trading before live implementation
   - Monitor performance for at least 2 weeks

4. **Switching Configurations**:
   - Don't change too frequently (max once per week)
   - Document reasons for changes
   - Track performance of each configuration

Remember: These are starting points. Always optimize parameters based on your specific trading goals and market conditions.