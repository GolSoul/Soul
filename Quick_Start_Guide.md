# Oracle Precision Pro - Quick Start Guide

## 🚀 Quick Setup (5 minutes)

### 1. Installation
1. Open [TradingView](https://tradingview.com) and log in
2. Open the Pine Editor (bottom panel)
3. Create a new script
4. Copy the entire content from `Oracle_Precision_Pro.pine`
5. Save the script as "Oracle Precision Pro"
6. Click "Add to Chart"

### 2. Basic Configuration
**For Beginners - Use These Settings:**
- Confidence Threshold: `0.65`
- Use Higher Timeframe Filter: `true`
- Higher Timeframe: `1D` (for intraday charts)
- ATR Stop Loss Multiplier: `2.0`
- ATR Take Profit Multiplier: `3.0`
- Risk Per Trade: `1.0%`

### 3. Chart Setup
1. Set your chart to 4H or 1D timeframe
2. Apply the strategy
3. Enable alerts if desired
4. Start monitoring signals!

## 📊 What You'll See

### Visual Elements:
- 🟢 **Green triangles**: Long entry signals
- 🔴 **Red triangles**: Short entry signals
- **Blue line**: Fast EMA (trend direction)
- **Red line**: Slow EMA (trend confirmation)
- **Background color**: Green (bullish) / Red (bearish)
- **Confidence table**: Real-time scoring (top-right)

### Sample Signal:
```
🟢 LONG SIGNAL
Price: 1,234.56
Confidence: 0.78
Time: 2024-01-15 09:30
Stop Loss: 1,210.23
Take Profit: 1,278.45
```

## ⚡ Quick Optimization

### Step 1: Run Default Backtest
1. Open Strategy Tester
2. Set date range (1-2 years)
3. Note profit factor and win rate

### Step 2: Quick Tuning (if needed)
**If too few signals:** Lower confidence threshold to `0.60`
**If too many signals:** Raise confidence threshold to `0.70`
**If poor win rate:** Enable HTF filter and increase ATR multipliers

### Step 3: Risk Management
- Start with 1% risk per trade
- Use ATR-based stops for dynamic risk management
- Monitor maximum drawdown (keep under 10%)

## 📱 Alert Setup (Optional)

1. Right-click chart → "Add Alert"
2. Condition: "Oracle Precision Pro"
3. Options: "Once Per Bar"
4. Choose notification method
5. Click "Create"

## 🎯 Best Practices

### Do's:
✅ Start with default settings
✅ Use on 4H or higher timeframes
✅ Enable higher timeframe filter
✅ Backtest before live trading
✅ Risk only 1-2% per trade

### Don'ts:
❌ Don't overtrade (wait for high confidence signals)
❌ Don't ignore stop losses
❌ Don't use on very low timeframes (<1H)
❌ Don't risk more than you can afford to lose

## 🔧 Common Settings by Trading Style

### Conservative Trader:
- Confidence Threshold: `0.75`
- HTF Filter: `true`
- Risk Per Trade: `0.5%`
- ATR Stop Multiplier: `2.5`

### Aggressive Trader:
- Confidence Threshold: `0.60`
- HTF Filter: `false`
- Risk Per Trade: `2.0%`
- ATR Stop Multiplier: `1.5`

### Swing Trader:
- Timeframe: `1D`
- HTF Filter: `1W`
- Confidence Threshold: `0.70`
- ATR Target Multiplier: `4.0`

## 📈 Next Steps

1. **Read Full Documentation**: `Oracle_Precision_Pro_Documentation.md`
2. **Practice**: Use paper trading first
3. **Optimize**: Fine-tune parameters for your market
4. **Monitor**: Review performance weekly
5. **Adapt**: Adjust settings based on market conditions

---

**⚠️ Risk Warning**: Trading involves risk. Always use proper risk management and never invest more than you can afford to lose.